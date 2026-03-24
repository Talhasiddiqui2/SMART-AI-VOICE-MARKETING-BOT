🎙️ Smart AI Voice Marketing Bot (University Final Year Project)
Developed by Talha as a Final Year Project, this is an advanced AI-driven voice assistant designed for automated telephony and marketing. It leverages the power of Google Gemini 2.5 Flash and Twilio ConversationRelay to provide human-like, real-time voice interactions.

🚀 Overview
This project enables businesses (like SignsVerse) to automate customer interactions over phone calls. Unlike traditional IVR systems ("Press 1 for..."), this bot understands natural language and responds instantly using state-of-the-art LLMs.

Key Features:
Real-time Voice Interaction: Low-latency communication using WebSockets.

LLM Integration: Powered by Google Gemini 2.5 Flash for intelligent, context-aware responses.

Automated Telephony: Fully integrated with Twilio Voice for handling incoming/outgoing calls.

Natural Speech: Uses high-quality Text-to-Speech (TTS) to maintain a natural conversational flow.

Dynamic Configuration: Easily manageable through environment variables.

🛠️ Tech Stack
Language: Python 3.10+

Framework: FastAPI (High-performance ASGI framework)

AI Model: Google Gemini 2.5 Flash

Telephony: Twilio (ConversationRelay)

Server/Tunnel: Uvicorn & Ngrok

📂 Project Structure
main.py: The core engine handling WebSockets, Twilio TwiML, and Gemini API integration.

requirements.txt: List of Python dependencies.

.env.example: Template for API keys and configuration.

AI_Voice_Assistant_User_Manual.docx: Comprehensive documentation for setup and usage.

⚙️ Setup Instructions
1. Clone the Repository
Bash
git clone https://github.com/your-username/smart-ai-voice-bot.git
cd smart-ai-voice-bot
2. Install Dependencies
Bash
pip install -r requirements.txt
3. Environment Configuration
Create a .env file in the root directory and add your credentials:

Code snippet
GOOGLE_API_KEY="your_google_gemini_api_key"
NGROK_URL="your_ngrok_url.ngrok-free.app"
PORT=8080
4. Run the Application
Start the FastAPI server:

Bash
python main.py
Configure your Twilio number's Voice Webhook to:
https://your-ngrok-url.ngrok-free.app/twiml

📝 Usage & Testing
Once the server is live, call your Twilio phone number.

The bot will greet you: "Hi! I am a voice assistant powered by Twilio and Google Gemini. Ask me anything!"

You can speak naturally, and the bot will respond based on the System Prompt defined in main.py.
If you have any problem in this project you can contact me Thanks 
