---
tags: ["Resúmenes y Reportes"]
---

En julio de 2024, nuestra comunidad ha estado trabajando arduamente para explorar y maximizar las capacidades del Rabbit R1. A continuación, presentamos un resumen de los avances, descubrimientos y casos de prueba más destacados.

## Recursos Clave y Enlaces Útiles

### 🟠 Repositorios y Herramientas

- [Web de Mi Rabbitos](https://mirabbitosr1.github.io)
- [GitHub Repo: LAMatHome](https://github.com/dot-Justin/LAMatHome)
- [Magicam Prompter Tool](https://dotjust.in/tools/magicam_prompter/)
- [Awesome Rabbit R1](https://github.com/sayhiben/awesome-rabbit-r1)

### 🟠 Artículos Educativos en Español

1. **Introducción al Formato Markdown**
   - Aprende a utilizar Markdown para formatear tus documentos y publicaciones en la *rabbit community* de manera sencilla y eficiente.
   - [Leer Artículo](https://medium.com/@axelfernandezcurros/introducci%C3%B3n-al-formato-markdown-0486e5b47809)

2. **Programación en Python para Principiantes: Una Guía Integral**
   - Una guía completa para aquellos que quieren iniciarse en la programación con Python, uno de los lenguajes más populares y versátiles.
   - [Leer Artículo](https://medium.com/@axelfernandezcurros/programaci%C3%B3n-en-python-para-principiantes-una-gu%C3%ADa-integral-7e0b87016f84)

3. **Tu Guía Completa de Iniciado con Git**
   - Descubre los fundamentos de Git, el sistema de control de versiones más utilizado, y mejora tu flujo de trabajo de desarrollo.
   - [Leer Artículo](https://medium.com/@axelfernandezcurros/tu-gu%C3%ADa-completa-de-iniciado-con-git-b6b475bb6991)

## Guía para Configurar y Usar LAMatHome con Rabbit R1

### 🟠 Pasos para Configuración

1. **Instalación de Git y Python**
   - [Instrucciones para Git](https://community.rabbit.tech/t/r1-en-espana/9110/9?u=afaces)
   - [Instrucciones para Python](https://community.rabbit.tech/t/r1-en-espana/9110/9?u=afaces)

2. **Clonación del Repositorio**
   ```powershell
   cd Documentos\git
   git clone https://github.com/dot-Justin/LAMatHome
   ```

3. **Creación del Entorno Virtual de Python**
   ```powershell
   cd LAMatHome
   python -m venv venv
   ```

4. **Actualización de pip e Instalación de Dependencias**
   ```powershell
   .\venv\Scripts\python.exe -m pip install pip --upgrade
   .\venv\Scripts\python.exe -m pip install -r .\requirements.txt
   .\venv\Scripts\python.exe -m pip install open-interpreter
   .\venv\Scripts\python.exe -m playwright install
   ```

### 🟠 Archivo `.env`

Para que el sistema funcione correctamente, es necesario rellenar el archivo `.env` con las claves y credenciales apropiadas:
```powershell
RH_ACCESS_TOKEN=''
GROQ_API_KEY=''
DC_EMAIL=''
DC_PASS=''
FB_EMAIL=''
FB_PASS=''
G_HOME_EMAIL=''
G_HOME_PASS=''
```

### 🟠 Ejecución del Script Principal
```powershell
.\venv\Scripts\python.exe main.py
```
**Nota:** Las claves de Rabbit caducan a diario, asegúrate de actualizarlas regularmente.

### 🟠 Automatización en Windows
1. **Archivo `.bat`**
   ```powershell
   @echo off
   set powershellScriptPath=%USERPROFILE%\Documents\git\LAMatHome\runLAMatHome.ps1
   set powershellPath=C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
   start "" "%powershellPath%" "%powershellScriptPath%"
   ```

2. **Archivo `runLAMatHome.ps1`**
   ```powershell
   $LAMatHomePath = [System.IO.Path]::Combine([Environment]::GetFolderPath("Documents"), "git", "LAMatHome")
   cd $LAMatHomePath
   git fetch
   git pull
   .\venv\Scripts\python.exe -m pip install pip --upgrade
   .\venv\Scripts\python.exe -m pip install -r .\requirements.txt --upgrade
   .\venv\Scripts\python.exe main.py
   ```

3. **Añadir `.bat` al Inicio del Sistema**
   - Presiona `Win + R`, escribe `shell:startup` y presiona `Enter`.
   - Copia el archivo `.bat` en la carpeta que se abrirá.

4. **Permitir la Ejecución de Scripts de PowerShell**
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

## Notas Adicionales

- [Magic Camera Photos Thread](https://community.rabbit.tech/t/magic-camera-photos-thread/151)
- [Magic Camera Freestyle Photos Thread](https://community.rabbit.tech/t/magic-camera-freestyle-photos-thread/12429)
