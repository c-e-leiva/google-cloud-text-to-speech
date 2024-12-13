# 🎤 **Proyecto de Síntesis de Texto a Voz con Google Cloud Text-to-Speech**

Este proyecto utiliza la API de Google Cloud Text-to-Speech para convertir texto a voz y reproducirlo como archivo de audio.

## 🎯 Objetivo

Integrar la tecnología de Google Cloud para convertir texto escrito en voz natural, facilitando la creación de interfaces interactivas y aplicaciones de accesibilidad.

---

## 🔧 Requisitos

- `google-cloud-texttospeech`: Interactuar con la API.
- `playsound`: Reproducir el archivo de audio.

Instalar las dependencias:
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
Se Puede obtener una lista de todas las voces disponibles para la conversión de texto a voz en español. Esto permite elegir una voz adecuada para el proyecto.

## 🔊 Sintetizar y Reproducir
Este proyecto utiliza la API de Google Cloud para transformar texto escrito en voz de manera eficiente. Permite seleccionar la voz deseada, ajustar la velocidad y el tono según las necesidades, y generar un archivo de audio con el resultado. Finalmente, el audio se reproduce automáticamente, proporcionando una experiencia fluida y personalizada.
