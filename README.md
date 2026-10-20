# Repositorio de SIC Chile 2026: Inteligencia Artificial

## Sobre el curso

**Nombre del curso:** SIC IA 2026 Chile (Samsung Innovation Campus)  
**Fechas de realización:** Desde octubre de 2026  
**Profesor:** David Leal Olivares [@davidlealo](https://github.com/davidlealo)  

Este repositorio contiene el material del curso de Inteligencia Artificial de Samsung Innovation Campus Chile 2026: notebooks de cada clase, datasets, soluciones del profesor y los ejercicios que entregan los estudiantes. El curso recorre desde las herramientas básicas (Git, NumPy, pandas) hasta machine learning, procesamiento de lenguaje natural y deep learning, y termina con un proyecto final.

### Versiones anteriores del curso

- [SIC AI 2024](https://github.com/davidlealo/sic_ai_2024)
- [SIC AI 2025 (junio)](https://github.com/davidlealo/sic_ai_2025_jun)
- [SIC AI 2025 (septiembre)](https://github.com/davidlealo/sic_ai_2025_sept)

## Clases

| Clase | Tema | Notebook |
|:-----:|------|----------|
| 1 | Git y GitHub: repositorios, commits, ramas, fork y pull requests | [clase_01.ipynb](./clases/clase_01.ipynb) |
| 2 | NumPy, pandas y primer modelo de machine learning | [SIC2026_IA_Clase02_NumPy_pandas_ML.ipynb](./clases/SIC2026_IA_Clase02_NumPy_pandas_ML.ipynb) |
| 3 | Capítulo 5: machine learning supervisado (clase presentada por grupos) | [SIC2026_IA_Clase03_Cap5_Grupos.ipynb](./clases/SIC2026_IA_Clase03_Cap5_Grupos.ipynb) |

> Esta tabla se irá actualizando a medida que avance el curso.

## Contenidos del programa

1. **Introducción a la Inteligencia Artificial:** historia, ámbitos de aplicación e impacto en la sociedad.
2. **Herramientas de trabajo:** Python, Jupyter/Colab, Git y GitHub.
3. **Preprocesamiento de datos:** NumPy, pandas, limpieza, transformación y visualización.
4. **Probabilidad y estadística:** distribuciones, medidas de tendencia y dispersión.
5. **Aprendizaje supervisado:** regresión, clasificación, validación y métricas con scikit-learn.
6. **Aprendizaje no supervisado:** clustering y reducción de dimensionalidad.
7. **Procesamiento de Lenguaje Natural (PLN):** tokenización, vectorización y clasificación de texto.
8. **Deep Learning:** redes neuronales, Keras/TensorFlow, visión por computador.
9. **Proyecto final:** aplicación de lo aprendido a un problema real.

## Estructura del repositorio

```
sic_ia_2026/
├── clases/                  # Notebooks de cada clase
├── datos/                   # Datasets usados en las clases (por capítulo)
├── ejercicios_profesor/     # Soluciones y material del profesor
├── ejercicios_estudiantes/  # Entregas de los estudiantes (vía pull request)
├── proyectos/               # Proyectos finales de los equipos
└── README.md
```

## Cómo usar este repositorio

### Opción 1: Google Colab (recomendada)

Abre cualquier notebook de la carpeta [`clases`](./clases/) en GitHub y cámbiale la URL de `github.com` a `githubtocolab.com`, o en Colab usa **Archivo → Abrir notebook → GitHub** y pega la URL del repositorio.

### Opción 2: En tu computador

```bash
git clone https://github.com/davidlealo/sic_ia_2026.git
cd sic_ia_2026
python -m venv venv
source venv/bin/activate        # En Windows: venv\Scripts\activate
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

## Cómo entregar tus ejercicios

1. Haz un **fork** de este repositorio (botón "Fork" en GitHub).
2. Clona tu fork:
   ```bash
   git clone https://github.com/TU_USUARIO/sic_ia_2026.git
   cd sic_ia_2026
   ```
3. Guarda tu notebook en `ejercicios_estudiantes/` con el formato `Nombre_Apellido_ClaseN.ipynb`.
4. Haz commit y push a tu fork:
   ```bash
   git add ejercicios_estudiantes/Nombre_Apellido_ClaseN.ipynb
   git commit -m "Ejercicio clase N - Nombre Apellido"
   git push origin main
   ```
5. En GitHub, abre un **Pull Request** desde tu fork hacia este repositorio.

Antes de empezar un ejercicio nuevo, sincroniza tu fork con el repositorio original (botón **Sync fork** en GitHub y luego `git pull`).

## Recursos adicionales

- [Documentación de NumPy](https://numpy.org/doc/)
- [Documentación de pandas](https://pandas.pydata.org/docs/)
- [Documentación de scikit-learn](https://scikit-learn.org/)
- [Tutoriales de Matplotlib](https://matplotlib.org/stable/tutorials/index.html)
- [Pro Git (libro gratuito en español)](https://git-scm.com/book/es/v2)

## Contacto

Para preguntas o comentarios, contacta a David Leal Olivares:

- [GitHub](https://github.com/davidlealo)
- [LinkedIn](https://www.linkedin.com/in/davidlealo/)
- [Instagram](https://www.instagram.com/davidlealo/)

## Organización

Este curso es realizado para Innovacien (partner local de SIC en Chile):

- [Sitio web](https://innovacien.org)
- [Instagram](https://www.instagram.com/innovacien/)
