# Editor híbrido de diapositivas

Aplicación web para transformar presentaciones de NotebookLM cuyas diapositivas están aplanadas como imágenes.

## Qué hace

- Conserva ilustraciones, iconos, efectos, marcos y composición como una base visual estable.
- Detecta textos confiables y los reconstruye como cuadros de texto editables.
- Permite corregir, mover, redimensionar, eliminar y agregar textos antes de exportar.
- Adapta los fondos y tonos oscuros a un color principal sin reemplazar toda la diapositiva por un color sólido.
- Exporta un nuevo archivo `.pptx` con la base visual y los textos editables.

## Uso

1. Abre la página de GitHub Pages.
2. Carga el `.pptx` exportado por NotebookLM.
3. Deja Poppins o escribe otra tipografía.
4. Elige el color principal.
5. Presiona **Preparar presentación editable**.
6. Revisa los cuadros de texto detectados.
7. Presiona **Descargar PowerPoint editable**.

## Privacidad

Los archivos se procesan dentro del navegador. No se guardan en GitHub ni se envían a un servidor propio.

## Enfoque híbrido

La aplicación no intenta convertir cada brillo, sombra o ilustración compleja en un vector. Mantiene esos elementos unidos para proteger la calidad visual y convierte en editable la parte que normalmente necesita cambios: texto, tipografía, ubicación y color principal.
