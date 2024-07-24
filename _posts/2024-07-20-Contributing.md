---
tags: ["Comunidad y Contribuciones"]
---

# Contribuyendo a MiRabbitOSr1.github.io

¡Nos alegra que quieras contribuir al proyecto MiRabbitOSr1! Colaborar nos ayuda a mejorar los recursos y la información disponible para la comunidad de Rabbit R1. Esta guía te ayudará a entender cómo contribuir de manera efectiva.

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Cómo Crear y Enviar Pull Requests](#cómo-crear-y-enviar-pull-requests)
3. [Crear Nuevos Archivos](#crear-nuevos-archivos)
4. [Flujo de Trabajo Clásico de GitHub](#flujo-de-trabajo-clásico-de-github)
5. [Abrir Problemas (Issues)](#abrir-problemas-issues)
6. [Contacto](#contacto)

## Introducción

1. **Haz un Fork del Repositorio**: Haz clic en el botón 'Fork' en la parte superior derecha de la página del repositorio para crear tu propia copia del repositorio.
  - Enlace al repositorio en GitHub ➡ [MiRabbitOSr1.github.io](https://github.com/MiRabbitOSr1/MiRabbitOSr1.github.io)
2. **Clona el Repositorio Forkeado**: Clona tu fork en tu máquina local usando el comando:
    ```powershell
    git clone https://github.com/tu-usuario/MiRabbitOSr1.github.io.git
    ```
3. **Navega al Directorio**: Cambia al directorio del repositorio:
    ```powershell
    cd MiRabbitOSr1.github.io
    ```

## Cómo Crear y Enviar Pull Requests

### 🟠 Guía Paso a Paso para Pull Requests

1. **Crea una Nueva Rama**: Es importante crear una nueva rama para cada característica o corrección en la que trabajes. Esto mantiene tu rama principal limpia.
    ```powershell
    git checkout -b nombre-de-tu-rama
    ```
2. **Haz Tus Cambios**: Agrega o modifica archivos en el repositorio.
3. **Añade los Cambios al Área de Staging**: Una vez que hayas hecho tus cambios, agrégales al área de staging:
    ```powershell
    git add .
    ```
4. **Haz un Commit de Tus Cambios**: Comenta tus cambios con un mensaje descriptivo:
    ```powershell
    git commit -m "Descripción breve de los cambios"
    ```
5. **Sube los Cambios a GitHub**: Sube tus cambios a tu repositorio forked:
    ```powershell
    git push origin nombre-de-tu-rama
    ```
6. **Crea un Pull Request**: Ve al repositorio original y verás un aviso para crear un pull request desde tu nueva rama. Sigue las instrucciones para abrir un pull request.

### 🟠 Nombrar Nuevos Archivos

Cuando crees nuevos archivos, usa la siguiente convención de nombres para incluir la fecha y un título descriptivo:
```plaintext
YYYY-MM-DD-Titulo-de-Tu-Artículo.md
```
Ejemplo:
```plaintext
2024-07-20-Actualizaciones-y-mejoras-de-software-en-Rabbit-R1.md
```

⚠️ Guarda estos archivos en la carpeta `_posts` dentro del repositorio para que se integren correctamente con el sitio web. ⚠️

## Flujo de Trabajo Clásico de GitHub

1. **Haz un Fork del Repositorio**: Esto crea una copia del repositorio bajo tu cuenta de GitHub.
2. **Clona el Repositorio**: Descarga el repositorio en tu máquina local.
3. **Crea una Rama**: Siempre crea una nueva rama para trabajar en una característica específica o una corrección.
4. **Haz Cambios**: Agrega, modifica o elimina archivos según sea necesario.
5. **Haz un Commit de los Cambios**: Realiza un commit con un mensaje claro y conciso.
6. **Sube los Cambios**: Sube tus cambios a tu repositorio forked.
7. **Crea un Pull Request**: Envía un pull request al repositorio original para revisión.

## Abrir Problemas (Issues)

Si encuentras errores o tienes sugerencias para nuevas características, puedes abrir un problema. Aquí te explicamos cómo:

1. **Navega a la Pestaña de Problemas**: Ve a la pestaña [Issues](https://github.com/MiRabbitOSr1/MiRabbitOSr1.github.io/issues) en el repositorio.
2. **Haz Clic en Nuevo Problema**: Haz clic en el botón 'New Issue'.
3. **Completa la Plantilla del Problema**: Proporciona una descripción clara y concisa del problema o sugerencia. Si es un error, incluye pasos para reproducirlo, el comportamiento esperado y capturas de pantalla si es aplicable.
4. **Envía el Problema**: Haz clic en 'Submit new issue' para crear el problema.
