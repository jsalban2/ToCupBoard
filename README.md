# ToCupBoard


## Guía de Documentación del Proyecto

# Reporte Técnico
He generado un informe técnico clave para el proyecto:

Descripción: Este informe PDF proporciona herramientas utilizadas en el sitio WordPress.
Ubicación: reportes/reporte técnico.pdf
Este informe está disponible en la carpeta reportes dentro del repositorio. Además habra un documento que detalla mejor las herramientas usadas (reportes/herramientas)


# Carpeta de ESCANEOS
La carpeta escaneos en el repositorio contiene resultados de las vulnerabilidades o monitoreo realizado, a partir de las cuales se realizaron modificaciones detalladas en los documentos del reporte técnico, por ejemplo, la edición en .htaccess para redireccionar de http a https y las cabeceras Http.

# Configuración del Workflow de CI
El archivo ci.yml en el directorio .github/workflows está configurado para realizar respaldos automáticos diarios del archivo XML de mi sitio WordPress. A continuación, se detalla la función del workflow:

Creación de Directorio de Respaldo: Se crea un directorio llamado backup en el repositorio para almacenar el archivo de respaldo.
Copia del Archivo XML: El archivo XML de WordPress se copia al directorio de respaldo con una marca de fecha en el nombre del archivo.
Commit y Push: El archivo de respaldo se añade al repositorio, se realiza un commit con un mensaje que incluye la fecha actual, y se sube a GitHub.
Propósito del Workflow
El propósito principal del workflow es mantener una copia de seguridad actualizada del archivo XML del sitio WordPress, lo que permite una gestión eficiente y conservación del respaldo del contenido del sitio.

# Cómo Utilizar
Para visualizar y descargar el informe, navega a la carpeta reportes en este repositorio. El workflow de CI está configurado para ejecutarse automáticamente y realizar respaldos del archivo XML diariamente. No es necesario realizar ninguna acción adicional para mantener el respaldo actualizado.
