# Fluxus-HTML https://discord.com/invite/bjqZtsqA5v

Este script permite descargar una página web en formato HTML junto con sus recursos asociados (CSS, imágenes, JavaScript, etc.). El propósito es guardar una copia local de la página que se especifique, manteniendo la estructura de la misma, para su análisis o para tener una referencia sin conexión.

**Características**
- **Descarga de la página HTML**: Guarda el HTML de la página web especificada.
- **Descarga de recursos**: La herramienta descarga archivos relacionados con la página (como imágenes, archivos CSS y JS) y los guarda en una carpeta organizada.
- **Interfaz interactiva**: Permite al usuario elegir qué página descargar e interactuar con un menú para realizar nuevas descargas o salir.

**Requisitos**
- Python 3.x
- Librerías: `requests`, `beautifulsoup4`, `colorama`, `tqdm`

**Uso**
1. Ejecuta el script.
2. Ingresa la URL de la página que deseas descargar.
3. La página HTML y sus recursos asociados se guardarán en una carpeta con el nombre del dominio de la URL.
