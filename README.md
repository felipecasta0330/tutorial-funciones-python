# Tutorial de funciones básicas de Python

Proyecto colaborativo del curso **Ciencia de Datos** — Actividad 3  
**Fundación Universitaria Agraria de Colombia (UNIAGRARIA)** · 2026

Este repositorio contiene un tutorial, en Jupyter Notebooks, de **35 funciones integradas (*built-in*) de Python**. Cada función tiene una explicación de qué hace, su sintaxis y ejemplos prácticos que se pueden ejecutar.

## Integrantes y roles

| Integrante | Usuario de GitHub | Rol | Notebook |
|------------|-------------------|-----|----------|
| Juan Felipe Castañeda Rodríguez | [@felipecasta0330](https://github.com/felipecasta0330) | Coordinador: crea y administra el repositorio, escribe el README y consolida el informe | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb): salida, tipos de datos y conversiones |
| José Alejandro Ochoa | [@Jos38a](https://github.com/Jos38a) | Desarrollador de contenido y revisor del Notebook 3 | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb): listas, tuplas, conjuntos y diccionarios |
| Ricardo José Díaz | [@requiempax](https://github.com/requiempax) | Desarrollador de contenido y revisor del Notebook 1 | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb): programación funcional, matemáticas, texto y archivos |

## Estructura del repositorio

```
tutorial-funciones-python/
├── README.md          ← este archivo
├── .gitignore         ← archivos que Git no debe rastrear
└── notebooks/
    ├── 01_funciones_basicas_tipos_y_salida.ipynb
    ├── 02_funciones_para_colecciones.ipynb
    └── 03_funciones_utiles_y_programacion_funcional.ipynb
```

## Funciones documentadas

| # | Función | Notebook | Responsable |
|---|---------|----------|-------------|
| 1 | `print()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 2 | `type()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 3 | `int()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 4 | `float()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 5 | `str()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 6 | `bool()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 7 | `len()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 8 | `round()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 9 | `abs()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 10 | `isinstance()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 11 | `input()` | [Notebook 1](notebooks/01_funciones_basicas_tipos_y_salida.ipynb) | Juan Felipe |
| 12 | `list()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 13 | `tuple()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 14 | `set()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 15 | `dict()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 16 | `range()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 17 | `sorted()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 18 | `reversed()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 19 | `enumerate()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 20 | `zip()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 21 | `sum()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 22 | `max()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 23 | `min()` | [Notebook 2](notebooks/02_funciones_para_colecciones.ipynb) | José Alejandro |
| 24 | `map()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 25 | `filter()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 26 | `any()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 27 | `all()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 28 | `pow()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 29 | `divmod()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 30 | `ord()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 31 | `chr()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 32 | `format()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 33 | `dir()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 34 | `help()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |
| 35 | `open()` | [Notebook 3](notebooks/03_funciones_utiles_y_programacion_funcional.ipynb) | Ricardo José |

## Cómo ver y ejecutar los notebooks

- **En GitHub:** basta con hacer clic en cada archivo `.ipynb`; GitHub muestra el notebook con las salidas ya ejecutadas.
- **En Google Colab:** abrir [colab.research.google.com](https://colab.research.google.com), pestaña **GitHub**, pegar la URL de este repositorio y elegir el notebook.
- **En el computador:** con Python y Jupyter instalados (`pip install notebook`), clonar el repositorio y ejecutar `jupyter notebook` dentro de la carpeta.

Los notebooks solo usan funciones integradas de Python: no hace falta instalar librerías adicionales.

## Flujo de trabajo del equipo

1. El coordinador creó el repositorio en GitHub y agregó a los demás integrantes como **colaboradores** (*Settings → Collaborators*).
2. Cada integrante aceptó la invitación y **clonó** el repositorio en su computador:
   ```bash
   git clone https://github.com/felipecasta0330/tutorial-funciones-python.git
   ```
3. Antes de empezar a trabajar, cada integrante **trae los cambios** de los demás:
   ```bash
   git pull
   ```
4. Cada integrante trabaja **solo en su propio notebook**, para evitar conflictos.
5. Al terminar una parte del trabajo, la sube con su propia cuenta:
   ```bash
   git add notebooks/<su_notebook>.ipynb
   git commit -m "Mensaje descriptivo en imperativo"
   git push
   ```
6. El trabajo se hizo en varias sesiones y en días distintos: primero la mitad de las funciones de cada notebook y después el resto, con su revisión.

**Convención de mensajes de commit:** verbo en imperativo + qué se hizo. Ejemplo: `Agrega funciones zip, sum, max y min al notebook 2`.

## Referencias

- Python Software Foundation. (2024). *Built-in Functions*. https://docs.python.org/3/library/functions.html
- Chacon, S., & Straub, B. (2014). *Pro Git* (2.ª ed.). Apress. https://git-scm.com/book/es/v2
- Hutch Data Science. (s. f.). *Using GitHub in a workflow*. https://hutchdatascience.org/Tools_for_Reproducible_Workflows_in_R/using-github-in-a-workflow.html
