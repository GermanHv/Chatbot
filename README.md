# Chatbot
Este es un chatbot básico en python utilizando las siguientes librerías:

## 1. Transformers (de Hugging Face)

  ¿Qué es?: Una biblioteca poderosa para el procesamiento de lenguaje natural (NLP) que proporciona acceso a modelos preentrenados de última generación como BERT, GPT, T5, etc.

  Uso en el código: Se utiliza pipeline para cargar y usar el modelo FLAN-T5-base, que permite generar respuestas a partir de una pregunta usando el tipo de tarea "text2text-generation".

## 2. Gradio

¿Qué es? Una herramienta para crear interfaces web interactivas de forma sencilla, útil para probar y compartir modelos de machine learning.

Uso en el código: Se usa gr.Interface para construir una interfaz gráfica donde el usuario puede introducir una pregunta y ver la respuesta generada por el modelo directamente en el navegador.

## ¿Qué es FLAN-T5?

FLAN-T5 es una variante mejorada del modelo T5 (Text-to-Text Transfer Transformer) desarrollado por Google. "FLAN" significa "Fine-tuned LAnguage Net", y representa una serie de técnicas de ajuste fino (fine-tuning) que mejoran la capacidad del modelo para seguir instrucciones en lenguaje natural.

## ¿Por qué es útil?
  No necesitas entrenarlo desde cero. Puede resolver muchas tareas de NLP sin cambiar el modelo: solo cambia el prompt (la entrada). Es rápido y eficiente, especialmente en su versión “base” (como la que usas).

Inputs
![Image](https://github.com/user-attachments/assets/367f7154-464c-4b37-9f55-8279d637f126)

Prueba de pregunta

![imagen](https://github.com/user-attachments/assets/fc267ab8-5d83-4583-a3f4-496fc059d28c)



