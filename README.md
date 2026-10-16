# Amplify Fusion - Websocket Voice Chat Demo Using Mistral AI

A AI voice chatbot demo project created by Axway colleague, [Sebastien MORENO](https://github.com/SebM0), based on my [Fusion AI Conversation Project](https://github.com/lbrenman/fusion-ai-chat-conversation-api) but with a major update to support a Fusion Websocket connection for streaming audio and using Mistral Text to Speech and Speech to Text and AI Chat Fusion connections.

I refactored it a bit to comply with my Postgres DB conversation table and I also added a Push To Talk feature to the included web app for having natural language conversations with the bot. Prior, you used prerecoded audio or recorded audio in the web app and sent to the websocket API.

## Getting Started

* Configure a Postgres DB as described in [Fusion AI Conversation Project](https://github.com/lbrenman/fusion-ai-chat-conversation-api)
* Export the Fusion project zip file in the Fusion Manager Module
* Update the project connectors with your Postgres, Lakera, Gemini (Fallback LLM) and Mistral credentials
* Start the Websocket Server and the Webapp HTTP Server
* Copy the Web app URL and launch it
* Copy the Websocket server url, and add /speech to it and paste it into the web app and click connect
* Use the app for a voice chat with the Mistral LLM