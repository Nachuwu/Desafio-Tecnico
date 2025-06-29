# 📰 Análisis de Noticias Locales por Comuna (Chile)

Este proyecto realiza un análisis automatizado de contenido noticioso a nivel comunal en Chile, aplicando técnicas de procesamiento de lenguaje natural (NLP) como análisis de sentimiento, modelado de tópicos y visualización mediante nubes de palabras. La información se extrae de diversas fuentes de prensa regional y nacional, entre julio de 2024 y mayo de 2025.

## 📌 Comunas Analizadas

- Los Andes  
- Calle Larga  
- Til Til  
- Colina

## 🧰 Herramientas Utilizadas

- **Python** (Pandas, Numpy, Matplotlib, Seaborn)
- **NLP**: SpaCy, NLTK, TextBlob
- **Modelado de tópicos**: LDA (Latent Dirichlet Allocation)
- **Visualizaciones**: WordCloud, gráficos de barras y líneas
- **Jupyter Notebook**


## 🔍 Metodología

1. **Carga y limpieza de datos**: Se normaliza el contenido, fechas y campos relevantes (`titulo`, `cuerpo`, `fecha`, `nombre_medio`, etc.).
2. **Análisis de palabras clave**: Se generan nubes de palabras por comuna a partir del contenido de noticias.
3. **Análisis de sentimiento**: Se calcula el sentimiento promedio por noticia y se visualiza su evolución temporal.
4. **Modelado de tópicos**: Se aplica LDA para identificar temas dominantes en cada comuna y se visualiza la distribución.
5. **Interpretación contextual**: Se comparan los resultados con el contenido observado en cada comuna.

## 📊 Resultados Destacados

- **Los Andes** tiene la mayor cobertura noticiosa y una fuerte concentración temática en comunidad y gestión local (Tópico 3).
- **Colina** presenta diversidad temática, destacando temas de seguridad y justicia penal.
- **Calle Larga** se enfoca en eventos comunitarios, con un tono predominantemente neutro o positivo.
- **Til Til** tiene baja cobertura pero altamente técnica, centrada en infraestructura (túneles, aguas, proyectos).

### Ejemplo: Nubes de Palabras
![image](https://github.com/user-attachments/assets/c3e394c7-361e-4105-bf9f-e6a251f2195d)
![image](https://github.com/user-attachments/assets/26535dc2-d40f-44b6-9f7a-8d8a50ec4ab9)

### Ejemplo: Distribución de Tópicos
![image](https://github.com/user-attachments/assets/04764cc6-e03d-47d5-8bbb-d3876a35b1e3)

## 🧪 Cómo Reproducir

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
