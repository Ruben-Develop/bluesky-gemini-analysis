# bluesky-gemini-analysis

# Análisis de perfiles de Bluesky con Gemini

Extrae el feed de un perfil de Bluesky, lo guarda en MongoDB y lo analiza con Gemini.

## Características
- Extracción de posts con atproto
- Limpieza de texto (URLs, emojis)
- Almacenamiento en MongoDB
- Análisis con Gemini 2.5 Flash

## Tecnologías
Python, atproto, google-genai, pymongo, python-dotenv

## Requisitos previos
Python 3.10+, MongoDB, cuenta de Bluesky y clave de API de Gemini

## Instalación
git clone ...
python -m venv venv
pip install -r requirements.txt
Crear .env con BSKY_IDENTIFIER, BSKY_PASSWORD, GEMINI_API_KEY, MONGO_URI

## Uso
python 1_3_Apellido1_Apellido2_Nombre.py

## Autor
Tu nombre

## Licencia
MIT
