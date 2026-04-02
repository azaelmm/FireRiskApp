# 🔥 FireRiskNet  
**Sistema inteligente para estimar el riesgo de incendios forestales usando LangChain + FastAPI + Angular**  
Combina datos ambientales con modelos de lenguaje (LLMs) para generar predicciones explicadas y visualizarlas en un mapa interactivo.

---

## 🌲 Descripción del proyecto  
**FireRiskNet** es una plataforma que analiza variables ambientales y genera una estimación del riesgo de incendios forestales.  
A diferencia de los modelos tradicionales basados en redes neuronales simples, este proyecto utiliza:

- **LangChain** para orquestar un modelo de lenguaje (LLM)
- **RAG (Retrieval-Augmented Generation)** para enriquecer predicciones con datos reales
- **FastAPI** como backend para exponer la API
- **Angular + Leaflet** para mostrar mapas interactivos con el nivel de riesgo

El sistema no solo predice, sino que también **explica** el razonamiento detrás de cada predicción.

---

## 🧠 Tecnologías utilizadas

### 🔧 Backend (Python)
- **FastAPI** — API moderna y rápida  
- **LangChain** — orquestación del modelo de lenguaje  
- **LLM (OpenAI, HuggingFace, o local)** — motor de predicción  
- **Pandas / NumPy** — manejo de datos  
- **Uvicorn** — servidor ASGI  

### 🎨 Frontend (Angular + TypeScript)
- **Angular 17+** — framework robusto para aplicaciones web  
- **Leaflet** — mapas interactivos  
- **OpenStreetMap** — mapas gratuitos  
- **RxJS** — manejo de datos reactivos  
