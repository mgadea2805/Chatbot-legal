# 🏛️ Chatbot Legal Laboral — Español & K'iche'
> Trabajo de Graduación USAC 2025 · Licda. Maria Fernanda Gadea Letona

Asistente virtual que ayuda a trabajadores guatemaltecos a conocer sus derechos según el **Código de Trabajo de Guatemala (Decreto 1441)**, con respuestas en español y K'iche'.

---

## ¿Qué hace?
- 🎙️ Reconoce voz en español y K'iche'
- 💬 Responde preguntas sobre 14 temas laborales
- 🔊 Lee las respuestas en el idioma que el usuario elija
- 📋 Muestra todo bilingüe en pantalla

## Temas que conoce
Despido injustificado · Horas extras · Vacaciones · Aguinaldo · Salario mínimo · Maternidad · Contratos · Renuncia · Jornada laboral · IGSS · Bono 14 · Discriminación · Días de asueto · Trabajo de menores

## Tecnologías
| Herramienta | Uso |
|-------------|-----|
| Whisper (OpenAI) | Voz a texto |
| Sentence Transformers + FAISS | Búsqueda semántica |
| espeak-ng | Texto a voz (ES y K'iche') |
| FastAPI | Servidor backend |
| HTML + JavaScript | Interfaz del chatbot |
| Google Colab + T4 GPU | Entorno de ejecución |

## Cómo ejecutar en Google Colab
1. Sube `Chatbot_mejorado.ipynb` a [colab.research.google.com](https://colab.research.google.com)
2. Activa **T4 GPU** en *Entorno de ejecución → Cambiar tipo de entorno*
3. Clic en **Ejecutar todo** y espera ~5 minutos
4. Abre el enlace `https://xxxxx.loca.lt` que aparece al final

---
> ⚠️ Este sistema es orientativo y académico. No reemplaza la asesoría de un abogado laboralista.
