# AI Personality Chatbot

An interactive chatbot built with **Streamlit** and the **Google Gemini API** that lets users have conversations with different fictional personalities.

## Features

- Choose from multiple personalities
- Interactive chat interface
- Powered by Google Gemini 2.5 Flash
- Loading animation while generating responses
- Input validation
- Simple and clean Streamlit UI

## Available Personalities

- A common Indian man frustrated by the Indian government
- A crazy Salman Khan fan
- A little boy who believes the world is a game that only adults play

## Technologies Used

- Python
- Streamlit
- Google Gemini API
- python-dotenv

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Personality-Chatbot.git
```

### 2. Navigate to the project directory

```bash
cd AI-Personality-Chatbot
```

### 3. Install the required packages

```bash
pip install streamlit google-genai python-dotenv
```

### 4. Create a `.env` file

Create a file named `.env` in the project directory and add your Gemini API key:

```env
api_key=YOUR_GEMINI_API_KEY
```

### 5. Run the application

```bash
streamlit run app.py
```

## How It Works

1. Select a personality from the dropdown menu.
2. Enter a message.
3. Click **Send**.
4. The application sends your prompt to the Gemini API.
5. Gemini responds while staying in the selected character.
6. The response is displayed on the screen.

## Project Structure

```
AI-Personality-Chatbot/
│
├── app.py
├── .env
├── requirements.txt
└── README.md
```

## Requirements

- Python 3.10+
- Streamlit
- Google Gemini API Key
- python-dotenv

## Note

Do not upload your `.env` file or API key to GitHub.

Add the following to your `.gitignore` file:

```
.env
```

## Author

Abhishek Jha
