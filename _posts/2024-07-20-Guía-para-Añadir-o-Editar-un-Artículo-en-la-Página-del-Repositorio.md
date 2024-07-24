---
tags: ["Guías y Tutoriales"]
---

Author: [<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/afaces/48/2649_2.png" alt="Afaces" width="16" height="16">](https://community.rabbit.tech/u/afaces) [Afaces](https://community.rabbit.tech/u/afaces)

¡Gracias por tu interés en contribuir a nuestro sitio web! A continuación te explicamos cómo añadir o editar un artículo en el repositorio **MiRabbitOSr1.github.io**. Sigue estos pasos para asegurarte de que tu contribución sea clara y efectiva.

## Tabla de Contenidos
1. [Preparación](#preparación)
2. [Añadir un Nuevo Artículo](#añadir-un-nuevo-artículo)
3. [Editar un Artículo Existente](#editar-un-artículo-existente)
4. [Flujo de Trabajo de Git](#flujo-de-trabajo-de-git)
5. [Crear un Pull Request](#crear-un-pull-request)
6. [Abrir Issues](#abrir-issues)
7. [Contacto](#contacto)

## Preparación

Antes de comenzar, asegúrate de tener una cuenta en [GitHub](https://github.com) y haber clonado el repositorio. Si aún no lo has hecho, sigue estos pasos:

1. **Haz un Fork del Repositorio**: Ve a [MiRabbitOSr1.github.io](https://github.com/MiRabbitOSr1/MiRabbitOSr1.github.io) y haz clic en el botón 'Fork' en la parte superior derecha para crear tu propia copia del repositorio.
2. **Clona el Repositorio Forkeado**: Clona tu fork en tu máquina local usando el siguiente comando:
    ```powershell
    git clone https://github.com/tu-usuario/MiRabbitOSr1.github.io.git
    ```
3. **Navega al Directorio**: Cambia al directorio del repositorio clonado:
    ```powershell
    cd MiRabbitOSr1.github.io
    ```

## Añadir un Nuevo Artículo

Para añadir un nuevo artículo, sigue estos pasos:

1. **Crea un Nuevo Archivo**: Dentro de la carpeta `_posts`, crea un nuevo archivo con el nombre en el formato `YYYY-MM-DD-Titulo-Del-Artículo.md`. Por ejemplo, para un artículo publicado el 20 de julio de 2024 con el título "Actualizaciones y mejoras de software en Rabbit R1", el nombre del archivo será:
    ```plaintext
    2024-07-20-Actualizaciones-y-mejoras-de-software-en-Rabbit-R1.md
    ```

2. **Añade el Contenido del Artículo**: Abre el archivo nuevo en tu editor de texto y añade la categoría o categorías del artículo siguiendo el formato de Markdown. Asegúrate de incluir un encabezado adecuado y el contenido necesario. Por ejemplo:
    ```plaintext
    ---
    tags: ["Actualizaciones y Mejoras", "Rabbit R1"]
    ---

    # Actualizaciones y mejoras de software en Rabbit R1

    Aquí va el contenido del artículo...
    ```

3. **Guarda y Cierra el Archivo**.

## Editar un Artículo Existente

Para editar un artículo existente:

1. **Encuentra el Archivo a Editar**: Navega a la carpeta `_posts` y localiza el archivo Markdown que deseas editar.
2. **Haz los Cambios Necesarios**: Abre el archivo en tu editor de texto y realiza las modificaciones requeridas.
3. **Guarda y Cierra el Archivo**.

## Flujo de Trabajo de Git

Sigue estos pasos para confirmar tus cambios y preparar un pull request:

1. **Crea una Nueva Rama**: Antes de hacer cambios, crea una nueva rama para tu trabajo. Esto ayuda a mantener la rama principal limpia.
    ```powershell
    git checkout -b nombre-de-tu-rama
    ```
   
2. **Añade los Cambios al Área de Staging**: Después de realizar los cambios en el archivo, agrégales al área de staging:
    ```powershell
    git add _posts/2024-07-20-Actualizaciones-y-mejoras-de-software-en-Rabbit-R1.md
    ```
   
3. **Haz un Commit de los Cambios**: Realiza un commit con un mensaje descriptivo sobre los cambios que has hecho:
    ```powershell
    git commit -m "Añadido nuevo artículo sobre actualizaciones y mejoras en Rabbit R1"
    ```

4. **Sube los Cambios a GitHub**: Sube tu rama con los cambios a tu repositorio forked:
    ```powershell
    git push origin nombre-de-tu-rama
    ```

## Crear un Pull Request

1. **Ve al Repositorio Original**: Navega al repositorio original en GitHub.
2. **Abre un Pull Request**: Verás un aviso para crear un pull request desde tu nueva rama. Haz clic en el botón 'Compare & pull request'.
3. **Completa el Pull Request**: Añade una descripción detallada de los cambios que has realizado y haz clic en 'Create pull request'.

## Abrir Issues

Si encuentras problemas o deseas sugerir mejoras:

1. **Navega a la Pestaña de Issues**: Ve a la pestaña [Issues](https://github.com/MiRabbitOSr1/MiRabbitOSr1.github.io/issues) en el repositorio.
2. **Haz Clic en Nuevo Problema**: Haz clic en el botón 'New Issue'.
3. **Completa la Plantilla del Problema**: Describe claramente el problema o la sugerencia. Si es un error, incluye pasos para reproducirlo y cualquier otra información relevante.
4. **Envía el Problema**: Haz clic en 'Submit new issue'.
