# Procesamiento de archivos JSON

Este repositorio contiene un cuaderno de Jupyter con códigos en Python para procesar archivos JSON. El cuaderno incluye funciones para:

- Copiar archivos JSON a diferentes carpetas.
- Formatear archivos JSON para mejorar su legibilidad.
- Modificar campos específicos en archivos JSON.
- Realizar búsquedas y reemplazos en masa de valores en archivos JSON.

## Instrucciones de uso

1. Clona este repositorio en tu computadora: `git clone <URL_del_repositorio>`
2. Abre el cuaderno `procesamiento_archivos_json.ipynb` en Google Colab o Jupyter Notebook.
3. Modifica las variables `ruta_base` y `ruta_destino` con las rutas correctas a tus archivos.
4. Ejecuta las celdas de código en el cuaderno para procesar los archivos JSON.

## Ejemplo de uso

```python
# Ejemplo de cómo utilizar la función procesar_archivos_json
procesar_archivos_json(ruta_base, ruta_destino)
