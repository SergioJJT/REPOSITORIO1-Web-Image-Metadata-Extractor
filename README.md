# 📷 Web Image Metadata Extractor  

Este script en Python realiza dos funciones principales:  

1. 📥 Descarga imágenes desde una página web.  
2. 🔍 Extrae los metadatos (incluyendo coordenadas GPS si están disponibles) de las imágenes descargadas.  

## 🛠 Requisitos  

Antes de ejecutar el script, asegúrate de tener instaladas las siguientes dependencias. Puedes instalarlas con:  


## 🚀 Uso  

Ejecuta el script desde la terminal proporcionando la URL de la página web que contiene las imágenes:  


### 🔹 Explicación de argumentos  

- `-h` → Muestra la ayuda y descripción del script.  
- `-link [URL]` → Especifica la URL desde la cual descargar las imágenes.  

## 📂 Salida  

Después de ejecutar el script, se generarán los siguientes archivos y carpetas:  

- 📁 **Carpeta `Imagenes_descargadas/`** → Contendrá todas las imágenes extraídas de la web.  
- 📝 **Archivos `.txt`** → Cada imagen con metadatos generará un archivo `.txt` con información extraída.  

## 📌 Notas  

- ✅ El script solo extrae metadatos de imágenes en formato `.jpg` y `.jpeg`.  
- 🌍 Si las imágenes contienen coordenadas GPS, también serán extraídas y guardadas en los archivos `.txt`.  
- 🛠 Puede ser útil para análisis forense digital y extracción de metadatos en imágenes obtenidas de la web.  

## ⚖️ Licencia  

Este proyecto se distribuye bajo la licencia MIT.  

🚀 **Desarrollado para análisis de imágenes en la web.**  


