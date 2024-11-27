## Paso 1: Limpieza de datos

### Ejecución
Ejecuta el siguiente script para procesar el archivo PDF y generar preguntas y respuestas:

```bash
python scripts/generar_preguntas.py
```
## Resultado
El script generará un archivo llamado preguntas_respuestas.xlsx que contiene las preguntas y respuestas extraídas o definidas en base al contenido del PDF.

## Paso 2: Implementación del Chatbot

### Ejecución
Ejecuta el siguiente script para interactuar con el chatbot:

```bash
python scripts/chatbot.py
```

## Resultado
El script abrirá una consola interactiva donde puedes escribir preguntas y recibir respuestas generadas por el modelo GPT.

## Paso 3: Evaluación del Chatbot

### Ejecución
Ejecuta el siguiente script para evaluar las respuestas generadas por el chatbot:

```bash
python scripts/evaluacion_chatbot.py
```

## Resultado
El script comparará las respuestas generadas por el chatbot con las respuestas de referencia del archivo preguntas_respuestas.xlsx y calculará métricas como el ACCURACY.

## Paso 4: Creación de la Aplicación en Streamlit

### Ejecución
Ejecuta el siguiente comando para iniciar la aplicación de Streamlit:

```bash
streamlit run streamlit_app/app.py
```

## Resultado
La aplicación abrirá una interfaz visual en tu navegador donde podrás:

Interactuar con el Chatbot:
Escribe preguntas y obtén respuestas generadas por el modelo.
Evaluar Respuestas:
Visualiza los resultados de evaluación con métricas como el ACCURACY y una gráfica de similitud.