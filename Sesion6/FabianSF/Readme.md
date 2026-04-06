# 💼 Motor RAG de Contrataciones SECOP II (Grupo Foxtrot)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tEGOZH7BSp2t72ETkbX--djnhWH2zdnw?usp=sharing)
[![YouTube Demo](https://img.shields.io/badge/YouTube-Ver_Demostración-red?logo=youtube&style=flat-square)](https://youtu.be/b6KYsk_u_Bw)

**Maestría en Inteligencia Artificial Aplicada - Universidad Icesi**  
*Asignatura:* Procesamiento de Lenguaje Natural (Sesión 6)

---

## 📺 Demostración Analítica en Video

[Haz clic aquí o en la imagen inferior para ver nuestra demostración de arquitectura RAG nivel empresarial, rastreando bases de datos contractuales con aceleración L4.](https://youtu.be/b6KYsk_u_Bw)

[![Video Demo Grupo Foxtrot](https://img.youtube.com/vi/b6KYsk_u_Bw/0.jpg)](https://youtu.be/b6KYsk_u_Bw)

---

## 🧠 Arquitectura Tecnológica

Este proyecto despliega un Chatbot RAG (Retrieval-Augmented Generation) avanzado, capaz de entender y auditar volúmenes masivos de licitaciones públicas (SECOP II Colombia) castigando estrictamente el margen de "alucinación artificial".

- **🤖 LLM Principal:** Meta Llama-3 (Inferido vía motor de alto desempeño Ollama sobre hardware Nvidia L4).
- **🧬 Embeddings Semánticos (SOTA):** BAAI/bge-m3, seleccionado por la precisión de sus tensores en español.
- **🚅 Clúster Vectorial (VRAM):** indexación masiva vía FAISS-GPU Cuda12.
- **⚙️ Core Matemático:** Estandarización sobre la API LCEL v3.0 (LangChain Expression Language).
- **🖥️ UI Premium:** Gradio interactivo customizado con directrices estéticas oscuras (*Cyber-Matrix* / *Hacker UI*).

## 🚀 Innovaciones Relevantes (Aporte Foxtrot)

1. **Ingestión Híbrida Inteligente:**  
Integración directa con la pasarela SODA (Datos.gov.co) para acceso nativo de llaves. En caso de detectar ejecución externa (Entorno Evaluador Tiers 3 o Profesor sin credenciales secretas), se dispara descarga secundaria de un "Parquet Snapshot" alojado vía Drive para **garantizar continuidad e ininterrupción metodológica**.

2. **Chunking Cuantitativo Empírico:**  
Errabundeamos el uso tradicional de "Adivinar la partición" de los documentos. El número base de "Chunk Size" se modela al vuelo capturando el **Percentil 95** de largo contractual extraído explícitamente sobre distribuciones visuales (Seaborn KDE).

3. **Arquitectura Cero-Alucinaciones (Bibliografía Dinámica Estilo Perplexity AI):**  
Se prescinde del uso arcaico de "Exigirle citación en el Prompt". Modificamos nativamente el canal de respuesta en Fase 6 para interceptar la respuesta de la Base de Datos. Engrapamos de forma independiente e inalterada la **Evidencia Contractual Física** en UI aislando al motor Chat, otorgando trazabilidad total y validación confiable al jurado calificador.

---

## 👨‍💻 Autores (Grupo Foxtrot)
- Raul Echeverry
- Esteban Ordoñez
- Fabian Salazar Figueroa

*Desarrollado para el curso NLP - 20261*
