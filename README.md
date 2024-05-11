## Descripcion del proyecto

- Proyecto grupal con la empresa Quinto Impacto que se realizo durante los meses de febrero 2024 - mayo 2024. El cual es un directorio de empresas de impacto para proveernos de servicios a los usuarios interesados en consumir este tipo de plataformas
- Para la creacion del proyecto se usaron tecnologias Java,Spring Boot y MariaDB. Ademas se implemento spring security y ouath para darle seguridad a nuestra app. 
- Entre algunas buenas practicas que se usaron para desarrollar fue el uso de dtos, mappers, manejo de los ResponseEntity y una buena separacion de capas. 
- Cada dos semanas se realizaaban sprints, y teniamos dailys 3 dias con el fin de mantener al tanto los avances del proyecto.
- Se hizo uso de la metodologia scrum y de herramientas como trello, figma y gititea para mostrar y estar al tanto de los avances grupales del proyecto

## Configuraciones Generales

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




