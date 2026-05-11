# Inventario Forestal

Proyecto desarrollado en Python y Google Colab para registrar información de fauna y flora mediante una interfaz interactiva usando `ipywidgets`.

## Integrantes
- Albert Yesid Rey Contreras — 01240372016
- Diego Fernando Rojas Arce — 01240372034

## Descripción
El programa permite gestionar un inventario forestal básico donde se pueden registrar animales y plantas/árboles, visualizar los datos almacenados y eliminar registros según el código ID.

La interfaz funciona con botones y formularios interactivos dentro de Google Colab o Jupyter Notebook.

## Funciones principales

### Registro de fauna
Permite guardar:
- Número de brigada
- Conglomerado
- Código ID
- Nombre común
- Nombre científico
- Cantidad
- Tipo de animal

### Registro de flora
Permite guardar:
- Número de brigada
- Conglomerado
- Código ID
- Nombre común
- Nombre científico
- Cantidad
- Tipo de árbol
- Propiedades

### Mostrar datos
Visualiza los registros guardados de fauna y flora en tablas usando `pandas`.

### Eliminar registros
Permite borrar registros mediante el código ID.

### Editar registros
Incluye una función de búsqueda por ID para localizar registros.

---

## Tecnologías usadas
- Python
- Google Colab
- ipywidgets
- pandas

## Librerías utilizadas

```python
import ipywidgets as wd
from IPython.display import display
import pandas as pd
from google.colab import files
```

## Cómo ejecutar el proyecto

1. Abrir el archivo en Google Colab o Jupyter Notebook.
2. Ejecutar todas las celdas.
3. Usar los botones interactivos:
   - FAUNA
   - FLORA
   - MOSTRAR DATOS
   - ELIMINAR
   - EDITAR

## Estructura general del programa
- Listas para almacenar datos de fauna y flora.
- Formularios interactivos con `ipywidgets`.
- Uso de `pandas.DataFrame` para mostrar la información.
- Validaciones básicas para evitar campos vacíos.

## Objetivo del proyecto
Facilitar el registro y organización de información forestal mediante una interfaz sencilla e interactiva.
