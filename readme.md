Es un asistente virtual inteligente para WhatsApp diseñado para agendar citas.

El chatbot utiliza OpenAI para entender las solicitudes del usuario (incluyendo mensajes de voz), identificar su intención y generar respuestas coherentes.

Todo el flujo de la conversación está orquestado con n8n y se conecta a WhatsApp usando Evolution API. Para mantener la continuidad y recordar interacciones pasadas, el chatbot guarda la memoria de la conversación en una base de datos PostgreSQL, todo alojado en un VPS de AWS.
