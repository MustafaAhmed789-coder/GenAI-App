# Islamic Mental Health Application

A Flask-based web application that provides Islamic guidance, daily verses, and emotional support through an AI-powered chatbot.

## Features

- 🌙 Daily Quranic Verses with translations
- 😊 Mood-based Islamic guidance
- 📿 Relevant Duas and Hadiths
- 🤖 AI-powered Islamic counseling chat
- 🎨 Beautiful dark theme UI

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd mental-health-chatbot
```

2. Create a virtual environment (recommended):
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Set up your API key:
- Get an API key from OpenRouter (https://openrouter.ai/)
- Replace the API_KEY in `templates/index.html` with your key

## Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://127.0.0.1:5000
```

## Usage

1. **Daily Verse**: View and refresh random Quranic verses with translations

2. **Mood Selection**: 
   - Choose your current mood from the available options
   - Receive relevant Islamic guidance based on your selection

3. **Content Types**:
   - Quran: View verses related to your mood
   - Hadith: Read relevant prophetic traditions
   - Dua: Access appropriate supplications

4. **AI Chat**:
   - Click the chat icon to open the AI assistant
   - Ask questions about Islamic guidance and mental health
   - Receive responses based on Quran and authentic hadiths

## Technology Stack

- Backend: Flask (Python)
- Frontend: HTML, CSS, JavaScript
- APIs: 
  - Quran Cloud API (for verses)
  - OpenRouter API (for AI chat)

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 