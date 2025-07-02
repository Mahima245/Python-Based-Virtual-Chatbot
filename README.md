Virtual Chatbot with Voice & Knowledge Integration
A Python-based desktop virtual assistant that supports both text and voice input, provides dynamic responses such as date/time and Wikipedia facts, and offers a graphical user interface for enhanced interaction. Developed as a personal project in June 2025.

💡 Features
🗣️ Voice & Text Communication
Interact with the bot using voice commands or text input.

🪟 Graphical User Interface
Built using Tkinter for easy and friendly interaction.

🧾 Dynamic Responses
Retrieves:

Real-time date and time

Instant Wikipedia summaries

Predefined responses from a custom JSON knowledge base

🎙️ Speech Output
Uses pyttsx3 for clear and responsive voice replies.

🧠 Chat History Logging
Maintains a record of conversations for future analysis.

🛠 Tech Stack
Purpose	Technology Used
GUI	Tkinter
Voice Recognition	speech_recognition
Text-to-Speech	pyttsx3
Knowledge Retrieval	Wikipedia API
Response Management	JSON
Language	Python

🖥️ Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/virtual-chatbot.git
cd virtual-chatbot
2. Install Required Packages
Make sure you have Python 3.6+ installed.

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not provided, install manually:

bash
Copy
Edit
pip install pyttsx3 speechrecognition wikipedia
3. Run the Chatbot
bash
Copy
Edit
python chatbot.py
📁 Project Structure
graphql
Copy
Edit
virtual-chatbot/
│
├── chatbot.py                  # Main application file
├── gui.py                      # GUI logic with Tkinter
├── responses.json              # Custom chatbot knowledge base
├── speech_engine.py            # Voice synthesis and recognition logic
├── chat_history.txt            # Logs user-bot interactions
└── README.md                   # Project overview
📌 Usage Tips
Use your microphone to give voice commands (e.g., "What is the capital of France?")

Click or type your question into the chat window for text input.

Ask for general information like:

"What's the time?"

"Who is Albert Einstein?"

"Tell me a joke" (if custom responses exist)

🔐 Permissions
Ensure your system microphone access is enabled for speech recognition to work properly.

📓 Example Commands
Command	Response Example
What's the date today?	"Today's date is July 2, 2025."
Who is Elon Musk?	"Elon Musk is a business magnate..." (wiki)
Tell me a fun fact	"Did you know...?" (from JSON)

📈 Future Enhancements
Integration with OpenAI/GPT for more intelligent conversations

Add voice command to control apps

Translate voice output to other languages

👩‍💻 Author
Mahima Kumari
B.Tech CSE | ML & AI Minor | MERN Stack Enthusiast
