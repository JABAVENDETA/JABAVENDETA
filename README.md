## Hola soy Jesus Barroso 👋
![github](https://github.com/user-attachments/assets/3b2bb236-7a67-45e2-a6e7-66f8e1793b1a)

👤 Sobre mí
Soy Analista de Datos con formación en Administración de Empresas, Ingeniería Industrial y Ciencias Navales. Me especializo en transformar grandes volúmenes de datos en insights accionables, combinando herramientas de análisis, visualización y desarrollo de aplicaciones web.

🛠️ Stack principal: Python · SQL · Power BI · ArcGIS · Excel
📍 Colombia
🎓 Formación complementaria en ciencia de datos — TripleTen


🚀 Proyectos Destacados

1. 🚗 Aplicación Web — Análisis de Mercado de Vehículos
Objetivo: Explorar y visualizar datos del mercado automotor para identificar patrones en precios, kilometraje y modelos, facilitando la toma de decisiones de compradores y vendedores.
¿Qué hice?

Realicé una exploración y limpieza de datos con Pandas
Construí visualizaciones interactivas (histogramas y gráficos de dispersión) con Plotly
Desarrollé y desplegué una aplicación web con Streamlit, publicada en Render

Herramientas: Python Pandas Plotly Streamlit GitHub Render
Resultados y aprendizajes:

La app permite filtrar visualmente el inventario por kilometraje y año del modelo mediante casillas de verificación interactivas
Aprendí el flujo completo de despliegue de una aplicación de datos: desde el análisis hasta producción

🔗 Ver aplicación en vivo
<img width="760" alt="App Vehículos" src="https://github.com/user-attachments/assets/1dbfb202-bc26-4161-8093-6a7020cc5494" />

2. 🗺️ Mapa Interactivo — Incidencia de Factores de Riesgo en Colombia
Objetivo: Visualizar geográficamente la correlación entre violencia, narcotráfico, pobreza y homicidios en distintos puntos del territorio colombiano, para apoyar el análisis de seguridad y política pública.
¿Qué hice?

Integré bases de datos nacionales con información geoespacial de Colombia
Construí un mapa interactivo con capas activables/desactivables por índice
Desplegué la aplicación como herramienta de consulta visual pública

Herramientas: Python ArcGIS / Librerías de mapas Bases de datos nacionales
Resultados y aprendizajes:

Permite activar o desactivar capas de índices (violencia, narcotráfico, pobreza, homicidios) para analizar su incidencia por región
Reforcé habilidades en visualización geoespacial y en el uso de datos abiertos gubernamentales

🔗 Ver mapa interactivo
<img width="760" alt="Mapa de incidencia Colombia" src="https://github.com/JABAVENDETA/Mapa-de-correlacion/blob/main/Captura%20de%20pantalla%202026-05-27%20130351.png" />

3. 🔍 Análisis de Delitos en Colombia (2020–2025)
Objetivo: Analizar patrones delictivos en Colombia a partir de ~2.38 millones de registros de la Policía Nacional, identificando tendencias temporales, geográficas y perfiles de víctimas para generar conclusiones útiles para la seguridad ciudadana.
¿Qué hice?

Cargué y procesé el dataset v_delitos.csv (~2.38M registros) con Pandas
Realicé análisis univariado, temporal, geográfico y de víctimas
Analicé medios y armas utilizados, así como patrones cruzados entre variables
Generé visualizaciones estáticas e interactivas con Matplotlib, Seaborn y Plotly
Documenté el proceso siguiendo la metodología profesional de ciencia de datos de TripleTen

Herramientas: Python Pandas NumPy Matplotlib Seaborn Plotly Jupyter Notebook / Google Colab Git & GitHub
Fuente de datos: Policía Nacional de Colombia — Período: 2020–2025
Resultados y aprendizajes:

Identifiqué los municipios y períodos con mayor concentración de delitos
Construí un mapa interactivo de calor para visualizar la distribución geográfica de incidentes
Mejoré mis habilidades en manejo de grandes volúmenes de datos y en la comunicación visual de hallazgos

## Acceso al proyecto
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19yfQmaxqShAU6KJTKyvukhiolWnh3hkQ#scrollTo=PIn1ewwtJZPH)

[![Dataset en Google Drive](https://img.shields.io/badge/Dataset-Google%20Drive-blue?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1Gztg7C3cCjtqJ49Drabo6dp9z3zQVsmR)


## Vista previa del proyecto

![Mapa Interactivo](https://raw.githubusercontent.com/JABAVENDETA/Proyecto_delitos/main/mapa_inetractivo1.png)

🛠️ Tecnologías y Herramientas
CategoríaHerramientasLenguajesPython · SQLAnálisis de datosPandas · NumPyVisualizaciónMatplotlib · Seaborn · Plotly · Power BIAplicaciones webStreamlit · RenderGeoespacialArcGISEntornosJupyter Notebook · Google Colab · VS CodeControl de versionesGit · GitHubOfimática avanzadaExcel

### 4. 🧠 Inteligencia Conductual — Segmentación de Hábitos Alimenticios

**Objetivo:** Identificar perfiles de comportamiento alimenticio en una muestra de 824 personas mediante clustering, para generar recomendaciones estratégicas diferenciadas por segmento.

**¿Qué hice?**
- Procesé y limpié un dataset de 53 variables con tipos mixtos usando **Pandas**
- Apliqué One-Hot Encoding a 45 variables categóricas y estandarización con **StandardScaler**
- Determiné el número óptimo de clústeres mediante el **Método del Codo** y el **Coeficiente de Silueta**
- Construí un modelo **K-Means (k=2)** que identificó dos perfiles conductuales diferenciados
- Integré la API de **Groq (LLaMA 3.3 70B)** para generar perfiles descriptivos y recomendaciones estratégicas en lenguaje ejecutivo
- Documenté los hallazgos en un **Informe Ejecutivo** orientado a la toma de decisiones

**Herramientas:** `Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn` `Groq API` `Google Colab`

**Resultados y aprendizajes:**
- Se identificaron 2 segmentos: **"Comedores Balanceados"** (mayor riesgo nutricional, peso promedio 161 lb) y **"Delicias Saludables"** (hábitos más conscientes, peso promedio 154 lb)
- Ambos clústeres presentan predominancia femenina (60-62%), lo que orienta las estrategias de intervención
- Aprendí a integrar modelos de machine learning con IA generativa para comunicar hallazgos técnicos en lenguaje ejecutivo

🔗 [Ver Notebook en Google Colab](https://colab.research.google.com/drive/1xFN2MsZRBkO4NdjyzfMZF9pgIT6MEPUh)
📄 [**Ver Informe Ejecutivo**](#) *[]((https://docs.google.com/document/d/1RptDtWPrgioUa5LvkHl4pdEFqok0Dj2X/edit?usp=sharing&ouid=105770855580010600310&rtpof=true&sd=true))*

<img width="760" alt="Mapa de incidencia Colombia" src="https://github.com/JABAVENDETA/proyecto-human-clustering/blob/main/Captura%20de%20pantalla%202026-06-04%20214432.png" />

## 🎬 Inteligencia de Clientes — Segmentación Estratégica de Usuarios Netflix

**Objetivo:** Identificar perfiles de comportamiento de usuarios de Netflix mediante técnicas de reducción de dimensionalidad y clustering, con el fin de generar estrategias diferenciadas de retención, monetización y experiencia de usuario.

### ¿Qué hice?

- Realicé la limpieza y transformación de variables demográficas, de consumo y satisfacción utilizando Pandas.
- Codifiqué variables categóricas mediante Label Encoding y normalicé los datos con StandardScaler.
- Exploré patrones de comportamiento mediante análisis visual y estadístico.
- Determiné la estructura de segmentación utilizando el Método del Codo sobre los datos escalados.
- Implementé una arquitectura Autoencoder para reducir dimensionalidad y capturar patrones latentes de comportamiento.
- Construí un modelo K-Means sobre las representaciones comprimidas generadas por la red neuronal.
- Utilicé PCA para visualizar los segmentos identificados en dos dimensiones.
- Analicé cada clúster desde una perspectiva de negocio, generando recomendaciones orientadas a retención, experiencia de usuario y optimización de ingresos.
- Elaboré un informe ejecutivo traduciendo hallazgos técnicos en acciones estratégicas.

### Herramientas

**Python · Pandas · NumPy · Scikit-Learn · Keras · TensorFlow · PCA · K-Means · Matplotlib · Seaborn · Google Colab**

### Resultados y aprendizajes

- Se identificaron **4 segmentos diferenciados de usuarios** con comportamientos, niveles de satisfacción y patrones de consumo claramente distintos.
- Se detectaron perfiles de alto riesgo de abandono, usuarios altamente fidelizados y segmentos con potencial de crecimiento de ingresos.
- El uso combinado de **Autoencoders y K-Means** permitió capturar relaciones complejas que no son evidentes mediante segmentación tradicional.
- Aprendí a integrar técnicas de Deep Learning y Machine Learning para construir perfiles de clientes con enfoque estratégico.
- Fortalecí la capacidad de transformar resultados analíticos en recomendaciones ejecutivas orientadas a la toma de decisiones.

🔗 [Ver Notebook en Google Colab](https://colab.research.google.com/drive/1bhqO3pzVCh4Fgqfn1VBcpzo3dgNSJ_Uv)

# 🎖️ ATLAS — Agente Táctico de Análisis Estratégico Local

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Ollama](https://img.shields.io/badge/Ollama-llama3.1-black?logo=ollama)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-RAG-orange)
![Gradio](https://img.shields.io/badge/Gradio-UI-green?logo=gradio)
![ChromaDB](https://img.shields.io/badge/ChromaDB-VectorStore-purple)
![Local](https://img.shields.io/badge/100%25-Local-red)

> **Agente de inteligencia artificial 100% local para análisis táctico-militar, consulta doctrinal y planeamiento estratégico basado en una biblioteca de manuales militares y textos de estrategia.**

---

## 📸 Capturas de pantalla / Screenshots

| Interfaz principal | Respuesta del Coronel ATLAS |
|---|---|
| ![Screenshot 1](assets/screenshot1.png) | ![Screenshot 2](assets/screenshot2.png) |

---

## 🇪🇸 Español

### ¿Qué es ATLAS?

ATLAS es un agente de IA local que actúa como el **Coronel ATLAS**, analista estratégico-militar con acceso a una biblioteca de manuales tácticos, doctrina clásica y textos de ciencia política. Utiliza arquitectura **RAG (Retrieval-Augmented Generation)** para responder preguntas, comparar doctrinas y generar planes de acción basados exclusivamente en los documentos indexados.

**Corre 100% en tu computador — sin internet, sin APIs externas, sin costos.**

### ✨ Capacidades

- **Consulta doctrinal** — Responde preguntas con citas directas de los manuales
- **Análisis comparativo** — Contrasta doctrinas entre autores (Sun Tzu vs Clausewitz, etc.)
- **Planeamiento táctico** — Genera Cursos de Acción (COA) paso a paso con respaldo doctrinal
- **Memoria de conversación** — Mantiene contexto entre turnos de la misma sesión
- **Citas de fuentes** — Cada respuesta indica qué manual fue consultado

<!--
**JABAVENDETA/JABAVENDETA** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:



- 🔭 I’m currently working on Navy
- 🌱 I’m currently learning Data Analysis

