# Asistente para Productores Agrícolas - Hugging Face Space (Docker)

## Cómo desplegar:

1️⃣ Conecta este repo en Hugging Face Space (Docker).

2️⃣ Hugging Face hará el build automático.

3️⃣ En Settings → Secrets agrega:

OPENAI_API_KEY = sk-xxxxxxxxxxxxxxxxxxxxxxx

4️⃣ App disponible en: https://huggingface.co/spaces/gescaffs/boletin-odepa-chatbot

---

Estructura del proyecto:

- Dockerfile
- chatbot_rag.py
- requirements.txt
- /documentos/ (con PDFs)
- .env.example
- README.md
