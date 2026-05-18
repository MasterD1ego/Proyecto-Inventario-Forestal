# README - Inventario Forestal en Google Colab

## Descripción del Proyecto

Este proyecto consiste en un sistema interactivo de **Inventario Forestal** desarrollado en Python utilizando **Google Colab**, **ipywidgets** y **pandas**.  
El programa permite registrar, visualizar, editar y eliminar información relacionada con especies de **fauna** y **flora** presentes en diferentes conglomerados de Colombia.

La interfaz gráfica se construye mediante widgets interactivos, facilitando el ingreso y manejo de datos directamente desde Colab sin necesidad de utilizar consola tradicional.

---

## Autores

- Albert Yesid Rey Contreras — 01240372016  
- Diego Fernando Rojas Arce — 01240372034  

---

## Tecnologías Utilizadas

- Python 3
- Google Colab
- ipywidgets
- pandas
- IPython Display

---

## Librerías Utilizadas

```python
import ipywidgets as wd
from IPython.display import display
import pandas as pd
from google.colab import files
```

---

# Objetivo del Programa

El sistema tiene como finalidad facilitar el registro y administración de datos de especies forestales mediante una interfaz interactiva.

## Funcionalidades Principales

- Registrar especies de fauna y flora.
- Validar información ingresada.
- Mostrar datos almacenados en tablas.
- Editar registros existentes.
- Eliminar registros.
- Gestionar IDs únicos para evitar duplicados.

---

# Registro de Fauna

Permite ingresar información sobre animales encontrados en el inventario forestal.

### Datos solicitados:
- Número de brigada
- Conglomerado
- Código ID
- Nombre común
- Nombre científico
- Cantidad
- Tipo de animal

### Tipos de animales:
- Mamífero
- Ave
- Pez
- Reptil
- Anfibio
- Invertebrado
- Otro

---

# Registro de Flora

Permite registrar información de árboles y plantas.

### Datos solicitados:
- Número de brigada
- Código ID
- Conglomerado
- Nombre común
- Nombre científico
- Cantidad
- Tipo de árbol
- Propiedades

### Tipos de árboles:
- Fustales
- Latizales
- Brinzales

### Propiedades:
- Tóxico
- Medicinal
- Alimenticio
- Maderable

---

# Validaciones Implementadas

El programa incluye múltiples validaciones para garantizar la integridad de los datos:

- IDs únicos entre fauna y flora.
- Campos obligatorios.
- Valores positivos.
- Verificación de listas desplegables.
- Prevención de registros vacíos.

---

# Funciones Principales

| Función | Descripción |
|---|---|
| `mostrarBotones()` | Muestra u oculta botones según existan datos |
| `fauna()` | Registro de animales |
| `flora()` | Registro de árboles |
| `mostrarDatos()` | Visualización de datos |
| `editarDatos()` | Edición de registros |
| `eliminar()` | Eliminación de registros |

---

# Ejecución del Programa

## Paso 1
Abrir el archivo en Google Colab.

## Paso 2
Ejecutar todas las celdas del notebook.

## Paso 3
Utilizar los botones interactivos para administrar el inventario.

---

# Posibles Mejoras Futuras

- Exportar datos a Excel o CSV.
- Implementar búsqueda avanzada.
- Guardar información en bases de datos.
- Agregar gráficos estadísticos.
- Incorporar autenticación de usuarios.

---

# Conclusión

Este proyecto demuestra el uso de Python y widgets interactivos en Google Colab para desarrollar un sistema básico de gestión de inventario forestal.
