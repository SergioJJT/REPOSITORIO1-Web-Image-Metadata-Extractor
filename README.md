# 📷 Web Image Metadata Extractor  

Este script en Python realiza dos funciones principales:  
1. Descarga imágenes desde una página web.  
2. Extrae los metadatos (incluyendo coordenadas GPS si están disponibles) de las imágenes descargadas.  

## 🛠 Requisitos  

Antes de ejecutar el script, asegúrate de tener instaladas las siguientes dependencias:  

```bash
pip install requests beautifulsoup4 lxml pillow

🚀 Uso
Ejecuta el script desde la terminal con la URL de la página web que contiene las imágenes:

python E11_metadata_images_web.py -link https://www.ejemplo.com

🔹 Explicación de argumentos

-h → Muestra la ayuda y descripción del script.
-link [URL] → Especifica la URL desde la cual descargar las imágenes.

📂 Salida
Carpeta Imagenes_descargadas/ → Contendrá todas las imágenes extraídas de la web.
Archivos .txt → Cada imagen con metadatos generará un archivo .txt con información extraída.

📝 Notas
El script solo extrae metadatos de imágenes en formato .jpg y .jpeg.
Si las imágenes contienen coordenadas GPS, también serán extraídas.



