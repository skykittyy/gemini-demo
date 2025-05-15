# Gemini API Demo

This is a simple demo project using the Gemini API in a frontend web app.

## 🚀 Features

- Makes API calls to Gemini
- Separates API logic into modular JS files
- Uses environment variables for API key security

## 🔧 Setup

1. Clone the repository
2. Run the app locally in your browser

## 🔐 Environment Variables

Create a `.env` file in the project root based on the provided `.env.example`:

```env
GEMINI_API_KEY=your_real_api_key_here



# ⚠️ Environment Warning

**Do not commit your `.env` file.** It contains sensitive credentials like your API keys and should be kept private.  
Use the provided `.env.example` file as a template and create your own local `.env` file.

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `index.html` | The main webpage |
| `app.js` | Core app logic |
| `frontendScript.js` | Frontend handlers |
| `gemini_api_call.js` | Gemini API logic |
| `.gitignore` | Specifies which files Git should ignore |
| `.env.example` | Template for environment variables |
