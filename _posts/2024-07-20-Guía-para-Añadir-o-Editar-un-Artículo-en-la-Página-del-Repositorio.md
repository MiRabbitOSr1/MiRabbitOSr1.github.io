---
tags: ["Guías y Tutoriales"]
---

Autor: [<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/afaces/48/2649_2.png" alt="Afaces" width="16" height="16">](https://community.rabbit.tech/u/afaces) [Afaces](https://community.rabbit.tech/u/afaces)

¡Gracias por tu interés en contribuir a nuestro sitio web! A continuación te explicamos cómo añadir o editar un artículo en el repositorio **MiRabbitOSr1.github.io**. Sigue estos pasos para asegurarte de que tu contribución sea clara y efectiva.

## Tabla de Contenidos
1. [Preparación](#preparación)
2. [Añadir un Nuevo Artículo](#añadir-un-nuevo-artículo)
3. [Editar un Artículo Existente](#editar-un-artículo-existente)
4. [Uso de Firmas y Distinciones en Contenido Creado por Inteligencias Artificiales](#uso-de-firmas-y-distinciones-en-contenido-creado-por-inteligencias-artificiales)
5. [Flujo de Trabajo de Git](#flujo-de-trabajo-de-git)
6. [Crear un Pull Request](#crear-un-pull-request)
7. [Abrir Issues](#abrir-issues)
8. [Previsualización del Artículo](#previsualización-del-artículo)

## Preparación

Antes de comenzar, asegúrate de tener una cuenta en [GitHub](https://github.com), tener Git instalado y haber clonado el repositorio. Si aún no lo has hecho, sigue estos pasos:

0. **Instala Git**: [Guía Completa de Iniciado con Git](https://medium.com/@axelfernandezcurros/tu-gu%C3%ADa-completa-de-iniciado-con-git-b6b475bb6991){:target="_blank"}.

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

    *Si no estás familiarizado con Markdown, puedes aprender cómo usarlo en el siguiente artículo:* [**Introducción al Formato Markdown**](https://medium.com/@axelfernandezcurros/introducci%C3%B3n-al-formato-markdown-0486e5b47809){:target="_blank"}.

3. **Guarda y Cierra el Archivo**.

## Editar un Artículo Existente

Para editar un artículo existente:

1. **Encuentra el Archivo a Editar**: Navega a la carpeta `_posts` y localiza el archivo Markdown que deseas editar.
2. **Haz los Cambios Necesarios**: Abre el archivo en tu editor de texto y realiza las modificaciones requeridas.
3. **Guarda y Cierra el Archivo**.

## Uso de Firmas y Distinciones en Contenido Creado por Inteligencias Artificiales

Es importante distinguir si el contenido ha sido creado por un autor humano o una inteligencia artificial (IA), como el r1. A continuación, se explica cómo añadir y personalizar las firmas para indicar la autoría del artículo.

### 🟠 Autor Humano

Para firmar un artículo escrito por un autor humano, añade lo siguiente después de los tags antes del contenido del artículo:

```plaintext
Autor: [<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/afaces/48/2649_2.png" alt="Afaces" width="16" height="16">](https://community.rabbit.tech/u/afaces) [Afaces](https://community.rabbit.tech/u/afaces)
```

### 🟠 Creado por r1

Para indicar que el artículo ha sido creado por r1, añade lo siguiente al principio del contenido del artículo:

```plaintext
created on <a href="https://community.rabbit.tech/u/afaces">
    <img src="/assets/images/r1.png" alt="Axel's r1" width="16" height="16">
</a> <a href="https://community.rabbit.tech/u/afaces">Axel's r1</a>
```

### 🟠 Personalización de Firmas

Los usuarios pueden personalizar estas firmas para mejorar la transparencia y la distribución de la información. Esto es especialmente importante para advertir al lector sobre la participación de la IA en la creación del contenido. Para personalizar la firma:

1. **Cambia el Nombre de Usuario y Enlaces**: Sustituye `afaces` y los enlaces asociados por tu propio nombre de usuario y los enlaces a tu perfil.
2. **Actualiza las Imágenes**: Si tienes una imagen personalizada para tu avatar o para la IA, cambia la URL de la imagen a la de tu elección.

### 🟠 Ejemplo Personalizado

```plaintext
Autor: [<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/tu_usuario/48/2649_2.png" alt="Tu Usuario" width="16" height="16">](https://community.rabbit.tech/u/tu_usuario) [Tu Nombre](https://community.rabbit.tech/u/tu_usuario)

created on <a href="https://community.rabbit.tech/u/tu_usuario">
    <img src="/assets/images/tu_r1.png" alt="Tu r1" width="16" height="16">
</a> <a href="https://community.rabbit.tech/u/tu_usuario">Tu r1</a>
```

### 🟠 Artículos con Varios Autores

Para artículos con varios autores, añade las firmas de todos los autores de la siguiente manera:

```plaintext
Autores: 
[<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/autor1/48/2649_2.png" alt="Autor1" width="16" height="16">](https://community.rabbit.tech/u/autor1) [Autor1](https://community.rabbit.tech/u/autor1), 
[<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/autor2/48/2649_2.png" alt="Autor2" width="16" height="16">](https://community.rabbit.tech/u/autor2) [Autor2](https://community.rabbit.tech/u/autor2)
```

Para ediciones del autor original por otro autor, agrega una sección de "Editado por":

```plaintext
Editado por: 
[<img src="https://sea2.discourse-cdn.com/flex002/user_avatar/community.rabbit.tech/editor1/48/2649_2.png" alt="Editor1" width="16" height="16">](https://community.rabbit.tech/u/editor1) [Editor1](https://community.rabbit.tech/u/editor1)
```

## Flujo de Trabajo de Git

Sigue estos pasos para confirmar tus cambios y preparar un pull request:

1. **Crea una Nueva Rama**: Antes de hacer cambios, crea una nueva rama para tu trabajo. Esto ayuda a mantener la rama principal limpia.
    ```plaintext
    git checkout -b nombre-de-tu-rama
    ```

2. **Añade los Cambios al Área de Staging**: Después de realizar los cambios en el archivo, agrégales al área de staging:
    ```plaintext
    git add _posts/2024-07-20-Actualizaciones-y-mejoras-de-software-en-Rabbit-R1.md
    ```

3. **Haz un Commit de los Cambios**: Realiza un commit con un mensaje descriptivo sobre los cambios que has hecho:
    ```plaintext
    git commit -m "Añadido nuevo artículo sobre actualizaciones y mejoras en Rabbit R1"
    ```

4. **Sube los Cambios a GitHub**: Sube tu rama con los cambios a tu repositorio forked:
    ```plaintext
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

## Previsualización del Artículo

Antes de crear un pull request, es recomendable previsualizar tu artículo para asegurarte de que se vea como esperas. 

Aquí te explicamos cómo hacerlo utilizando Jekyll:

### 🟠 Instalación de Ruby y Jekyll

#### En macOS

1. **Instala Homebrew** si aún no lo has hecho:
    ```plaintext
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

2. **Instala Ruby usando Homebrew** para obtener la última versión:
    ```plaintext
    brew install ruby git
    ```

3. **Configura tu shell** para utilizar la versión de Ruby instalada por Homebrew:
    ```plaintext
    echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile # O ~/.zshrc si usas zsh
    ```

4. **Instala Jekyll y Bundler**:
    ```plaintext
    gem install jekyll bundler
    ```

#### En GNU/Linux

1. **Instala las dependencias necesarias**:
    ```plaintext
    sudo apt-get update -y
    sudo apt-get install -y make gcc ruby-full build-essential zlib1g-dev git
    ```

2. **Evita instalar gems como el usuario root** configurando un directorio de instalación para tu usuario:
    ```plaintext
    echo '# Instalación de Ruby Gems en ~/gems' >> ~/.bashrc
    echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
    echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
    source ~/.bashrc
    ```

3. **Instala Jekyll y Bundler**:
    ```plaintext
    gem install jekyll bundler
    ```

#### En Windows

1. **Instalación via RubyInstaller**:
    - Descarga e instala Ruby+Devkit desde [RubyInstaller Downloads](https://rubyinstaller.org/downloads/).
    - Sigue las instrucciones del instalador y asegúrate de ejecutar `ridk install` al finalizar.

2. **Instala Jekyll y Bundler**:
    ```plaintext
    gem install jekyll bundler
    ```

### 🟠 Añadir Dependencias Faltantes

Para evitar errores comunes al correr Jekyll en ambientes nuevos, especialmente en Ruby 3.0 o superior, añade `webrick` a tu conjunto de gemas:
```plaintext
bundle add webrick
```

### 🟠 Modificar el Gemfile para Mejorar la Compatibilidad

Para mejorar la compatibilidad y rendimiento de Jekyll en Windows y garantizar una correcta ejecución del sitio en GitHub Pages, es esencial modificar el archivo Gemfile de tu proyecto Jekyll con las siguientes líneas:
```plaintext
source 'https://rubygems.org'

gem 'github-pages', group: :jekyll_plugins

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Mejora la detección de cambios en archivos en Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
```

### 🟠 Instalar Dependencias del Proyecto

Después de configurar tu entorno Ruby y Jekyll, así como de asegurarte de que tu Gemfile esté correctamente establecido con todas las dependencias necesarias, ejecuta:
```plaintext
bundle install
```

### 🟠 Ejecutar Jekyll

Inicia el servidor de Jekyll con:
```plaintext
bundle exec jekyll serve
```

Visita [http://localhost:4000](http://localhost:4000) para ver tu sitio en acción.

### 🟠 Importante: Seguridad y Uso de .gitignore

Es crucial mantener la seguridad de tu proyecto evitando subir información sensible como claves API o contraseñas privadas a los repositorios de Git. Asegúrate de que los archivos que contienen esta información, como los archivos `.env`, estén incluidos en tu archivo `.gitignore`.

1. **Crea un Archivo .gitignore** en la raíz de tu proyecto si no lo tienes ya:
    ```plaintext
    .env
    node_modules/
    .DS_Store
    ```
    Esto asegura que tu archivo `.env` nunca se suba accidentalmente a tu repositorio.

2. **Añade y Commitea el .gitignore**:
    ```plaintext
    git add .gitignore
    git commit -am "Añadir .gitignore para evitar subir información sensible"
    ```
