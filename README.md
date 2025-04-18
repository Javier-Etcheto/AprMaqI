# Aprendizaje de Máquina 1 - TP Final

Este repositorio contiene el material utilizado para el trabajo práctico final para la materia *Aprendizaje de Máquina 1* de la Carrera de Especialización en Inteligencia Artificial (CEIA) de FIUBA.

Integrantes:

* Alejandro Le Mehaute
* Gustavo Ramoscelli
* Javier Etcheto
* Martín Errázquin

## Temática elegida

El dataset seleccionado es un conjunto de datos sobre rendimiento académico en estudiantes a lo largo de un curso, acompañado por diferentes métricas como asistencia, niveles de estrés, nivel de educación de padres, etc.

## Referencias

* [Fuente de dataset principal](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset)

## Integración con `uv`

Para gestión de dependencias se provee un archivo `pyproject.toml` y se prefiere el uso de [uv](https://docs.astral.sh/uv/).

Actualizar las dependencias requiere una simple linea

```bash
$ uv sync
```

Y levantar una instancia local de Jupyter Lab, con un kernel con las dependencias del proyecto, también:

```bash
$ uv run --with jupyter jupyter lab
```