# 🎤 **Proyecto de Síntesis de Texto a Voz con Google Cloud Text-to-Speech**

Este proyecto utiliza la API de Google Cloud Text-to-Speech para convertir texto a voz y reproducirlo como archivo de audio.

## 🎯 Objetivo

Integrar la tecnología de Google Cloud para convertir texto escrito en voz natural, facilitando la creación de interfaces interactivas y aplicaciones de accesibilidad.

---

## 🔧 Requisitos

- `google-cloud-texttospeech`: Interactuar con la API.
- `playsound`: Reproducir el archivo de audio.

Instala las dependencias:
```
pip install google-cloud-texttospeech playsound
```

## ⚙️ Configuración

Para utilizar la API de Google Cloud Text-to-Speech, sigue estos pasos:

1. Crea un proyecto en [Google Cloud Console](https://console.cloud.google.com/).
2. Habilita la API de Text-to-Speech.
3. Crea una clave de servicio en formato JSON y descarga el archivo.
4. Configura la variable de entorno `GOOGLE_APPLICATION_CREDENTIALS` con la ruta de tu archivo de credencial descargado:

```
import os
os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = "ruta/a/tu/credencial.json"
```

## 🗣️ Listar Voces Disponibles
Puedes obtener una lista de todas las voces disponibles para la conversión de texto a voz en español. Esto te permitirá elegir una voz adecuada para tu proyecto.

## 🔊 Sintetizar y Reproducir
Este proyecto convierte cualquier texto escrito en voz utilizando la API de Google Cloud. Puedes elegir la voz que prefieras, configurar la velocidad y el tono de la voz, y generar un archivo de audio con la salida. Luego, se reproduce el audio generado de forma automática.
