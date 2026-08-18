# 📊 EdTech Review Sentiment Intelligence

## English

### Overview

This repository analyzes public Google reviews from an EdTech institution that provides online English courses. It combines structured information—such as star ratings and institutional responses—with unstructured customer feedback.

The analysis applies natural language processing (NLP), text mining, topic modeling with Non-negative Matrix Factorization (NMF), and sentiment classification using a pretrained Spanish-language model.

### Business objective

Transform customer reviews into actionable insights to support:

- Student experience management.
- Digital reputation monitoring.
- Identification of the most valued service attributes.
- Detection of potential improvement opportunities.
- Prioritization of low-rating reviews.
- Comparison between written sentiment and star ratings.

### Analytical approach

1. Data structure and quality assessment.
2. Descriptive analysis of ratings, comments, and institutional responses.
3. Text cleaning and normalization.
4. Word and bigram frequency analysis.
5. Topic modeling using TF-IDF and NMF.
6. Sentiment classification using a pretrained language model.
7. Referential comparison between textual sentiment and star ratings.
8. Development of business conclusions and recommendations.

### Key findings

- **156 reviews** were analyzed.
- **147 reviews (94.23%)** contain written comments.
- **150 reviews (96.15%)** received five stars.
- The average rating was **4.90 out of 5**.
- The institution responded to **125 reviews (80.13%)**.
- The sentiment model identified:
  - **143 positive comments**
  - **2 neutral comments**
  - **2 negative comments**
- Textual sentiment and rating-based categories showed a **97.96% descriptive agreement**.

### Topics identified with NMF

| Topic | Reviews | Share |
|---|---:|---:|
| Classes, teachers, and platform | 54 | 36.73% |
| Experience, guidance, and support | 41 | 27.89% |
| Quality, professionalism, and service | 24 | 16.33% |
| Program, learning, and results | 14 | 9.52% |
| Language learning and practice | 14 | 9.52% |

The two most frequent topics account for approximately **64.62%** of the analyzed comments. This highlights the importance of the educational experience and the support provided throughout the student journey.

### Business recommendations

- Preserve and monitor the educational attributes most valued by students.
- Strengthen support before, during, and after student enrollment.
- Prioritize responses to reviews with ratings between one and three stars.
- Review discrepancies between written sentiment and star ratings individually.
- Use the five identified topics as customer experience monitoring dimensions.
- Capture exact review dates in future datasets to support trend analysis.

### Technologies

- Python
- pandas and NumPy
- Matplotlib and WordCloud
- spaCy and Unidecode
- scikit-learn
- TF-IDF and NMF
- PyTorch and Transformers
- Hugging Face pretrained models
- Jupyter Notebook

### Repository structure

```text
edtech_review_sentiment_intelligence/
├── edtech_customer_feedback_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

### Methodological considerations

Google reviews are voluntarily published by users and may not represent the entire student population. The strong concentration of five-star ratings also limits the evidence available for analyzing dissatisfaction.

The comparison between textual sentiment and star ratings is descriptive. It should not be interpreted as a formal evaluation of the pretrained model.

The original dataset is not included in this repository.

---

## Español

### Descripción

Este repositorio analiza reseñas públicas de Google correspondientes a una institución EdTech que ofrece cursos de inglés en modalidad online. El análisis combina información estructurada —como las estrellas y las respuestas de la institución— con los comentarios escritos por los usuarios.

Se aplican técnicas de procesamiento de lenguaje natural, minería de texto, modelado de temas mediante Non-negative Matrix Factorization (NMF) y clasificación de sentimiento con un modelo preentrenado en español.

### Objetivo de negocio

Transformar las reseñas de clientes en información accionable para apoyar:

- La gestión de la experiencia del estudiante.
- El monitoreo de la reputación digital.
- La identificación de los atributos más valorados.
- La detección de oportunidades de mejora.
- La priorización de reseñas con baja calificación.
- La comparación entre el sentimiento escrito y las estrellas otorgadas.

### Enfoque analítico

1. Revisión de la estructura y calidad de los datos.
2. Análisis descriptivo de estrellas, comentarios y respuestas de la institución.
3. Limpieza y normalización del texto.
4. Análisis de palabras y bigramas frecuentes.
5. Modelado de temas mediante TF-IDF y NMF.
6. Clasificación de sentimiento mediante un modelo de lenguaje preentrenado.
7. Comparación referencial entre sentimiento textual y estrellas.
8. Elaboración de conclusiones y recomendaciones de negocio.

### Principales resultados

- Se analizaron **156 reseñas**.
- **147 reseñas (94,23%)** contienen comentarios.
- **150 reseñas (96,15%)** tienen cinco estrellas.
- La calificación promedio fue de **4,90 sobre 5**.
- La institución respondió **125 reseñas (80,13%)**.
- El modelo de sentimiento identificó:
  - **143 comentarios positivos**
  - **2 comentarios neutrales**
  - **2 comentarios negativos**
- El sentimiento textual y las categorías derivadas de las estrellas presentaron una **coincidencia descriptiva de 97,96%**.

### Temas identificados mediante NMF

| Tema | Reseñas | Participación |
|---|---:|---:|
| Clases, profesores y plataforma | 54 | 36,73% |
| Experiencia, asesoría y acompañamiento | 41 | 27,89% |
| Calidad, profesionalismo y servicio | 24 | 16,33% |
| Programa, aprendizaje y resultados | 14 | 9,52% |
| Aprendizaje y práctica del idioma | 14 | 9,52% |

Los dos temas con mayor presencia concentran aproximadamente el **64,62%** de los comentarios analizados. Esto destaca la importancia de la experiencia educativa y del acompañamiento brindado durante el proceso del estudiante.

### Recomendaciones de negocio

- Mantener y monitorear los atributos educativos mejor valorados.
- Fortalecer el acompañamiento antes, durante y después de la inscripción.
- Priorizar las respuestas a reseñas de una a tres estrellas.
- Revisar individualmente las discrepancias entre sentimiento y calificación.
- Utilizar los cinco temas identificados como dimensiones de seguimiento.
- Incorporar fechas exactas en futuras bases para analizar tendencias.

### Tecnologías

- Python
- pandas y NumPy
- Matplotlib y WordCloud
- spaCy y Unidecode
- scikit-learn
- TF-IDF y NMF
- PyTorch y Transformers
- Modelos preentrenados de Hugging Face
- Jupyter Notebook

### Estructura del repositorio

```text
edtech_review_sentiment_intelligence/
├── edtech_customer_feedback_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

### Consideraciones metodológicas

Las reseñas de Google son publicadas voluntariamente por los usuarios y no necesariamente representan a toda la población de estudiantes. La fuerte concentración de calificaciones de cinco estrellas también limita la evidencia disponible para analizar la insatisfacción.

La comparación entre el sentimiento textual y las estrellas es descriptiva. No debe interpretarse como una evaluación formal del desempeño del modelo preentrenado.

La base de datos original no se incluye en este repositorio.

---

**Author / Autora:** Carolina Caycho