# Tarea 2 Tópicos de ingeniería informática - Módulo de data science.

![Python](https://img.shields.io/badge/Python-3.12.9-blue)
![NumPy](https://img.shields.io/badge/NumPy-2.1.3-orange)
![conda](https://img.shields.io/badge/Conda-25.0.0-blue)
![Last Commit](https://img.shields.io/github/last-commit/GSGEdgardo/t2_topicos)
![Institution](https://img.shields.io/badge/institution-Universidad%20Cat%C3%B3lica%20del%20Norte-blue)

## Descripción
Este repositorio contiene dos Jupyter notebooks que implementan una regresión lineal y un clasificador bayesiano.

## Environment

Este proyecto utiliza un entorno de conda que está definido en `environment.yml`.

## Instalación del ambiente

Para poder crear el entorno de conda, es necesario ejecutar el comando en la terminal:

```bash
conda env create -f environment.yml
```
Esto instalará todas las dependencias necesarias para ejecutar los notebooks.

### Conda Dependencies
- `pip=25.0`
- `python=3.12.9`

### Pip Dependencies
- `black==25.1.0`
- `coloredlogs==15.0.1`
- `matplotlib==3.10.1`
- `numpy==2.2.5`
- `notebook==7.4.2`
- `pandas==2.2.3`
- `seaborn==0.13.2`
- `typeguard==4.4.2`
- `ydata-profiling==4.16.1`


## Estructura de archivos

```
t2_topicos/
│ 
├── data/                  # conjuntos de datos
│   ├── student-mat.csv
│   └── winequality-red.csv
│
├── libs/                  # modulos reutilizables
│   ├── benchmark.py
│   └── logger.py
│
├── notebooks/             # ubicación de los archivos ipynb
│   ├── naive_bayes.ipynb
│   └── regresion_lineal.ipynb
│
├── .gitignore
├── environment.yml
└── README.md
```
---

© 2025 Magister en Informática
