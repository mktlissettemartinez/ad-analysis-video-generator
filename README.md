# NotebookLM Layerizer

Aplicación web estática que transforma presentaciones de NotebookLM con una imagen plana por diapositiva en un PowerPoint reconstruido por capas.

## Uso

1. Abre la página.
2. Carga un archivo `.pptx` exportado por NotebookLM.
3. Elige tipografía, nivel de separación y, opcionalmente, un color de fondo.
4. Presiona **Separar y crear PPT editable**.
5. La presentación se descarga automáticamente.

## Privacidad

Los archivos se procesan en el navegador. No se envían a un servidor propio ni se almacenan en GitHub.

## Capas generadas

- Texto detectado: cuadros de texto editables.
- Bloques de color simples: formas editables.
- Iconos, ilustraciones y objetos: imágenes PNG transparentes independientes.
- Fondo: imagen reconstruida sin los elementos detectados.

## Limitaciones

Las capas originales no existen dentro del PPT de NotebookLM. La aplicación las infiere a partir de la imagen. Los degradados complejos, efectos 3D, luces, sombras y elementos superpuestos pueden requerir correcciones posteriores.

## Tecnologías

- JSZip
- Tesseract.js
- PptxGenJS
- Canvas API

Las dependencias se cargan desde jsDelivr y el procesamiento se realiza en el cliente.
