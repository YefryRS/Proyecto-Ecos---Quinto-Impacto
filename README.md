# Ecosistema - Directorio de impacto

## Configuraciones Generales

### Requisitos Previos

- JDK (Java Development Kit) versión 17.x o superior.
- Maven versión 3.9.x o superior.

### Configuración del Entorno

2. **Configuración de las Variables de Entorno**: Asegúrate de que las variables de entorno `JAVA_HOME` y `PATH` estén configuradas correctamente para apuntar al directorio de instalación del JDK.

   Ejemplo (para Windows):

JAVA_HOME=C:\Program Files\Java\jdk-XX.X.X
PATH=%JAVA_HOME%\bin;%PATH%

3. **Instalación de Maven**: Si el proyecto utiliza Maven, descarga e instala Maven desde [el sitio oficial de Apache Maven](https://maven.apache.org/download.cgi).

4. **Configuración de Maven**: Asegúrate de que la variable de entorno `M2_HOME` esté configurada correctamente para apuntar al directorio de instalación de Maven, y añade `%M2_HOME%\bin` al `PATH`.

    Ejemplo (para Windows):

M2_HOME=C:\Program Files\Apache\maven
PATH=%M2_HOME%\bin;%PATH%

## Variables de entorno

Para facilitar la configuración del proyecto y garantizar que cada desarrollador tenga una configuración consistente, se establece la práctica de utilizar un archivo de variables de entorno. Este archivo se crea a partir de un archivo de ejemplo llamado .env.example.

1. Crear el Archivo .env a partir del .env.example:
2. Una vez creado el archivo .env, es importante revisar y modificar cada variable de entorno según sea necesario.
3. El archivo .env ya está ignorado en el .gitignore

