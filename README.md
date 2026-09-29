# PocketSmart AI

A smart budget and recommendation assistant. Enter a budget and preferences, and get suggestions for home interiors, party planning and jewelry from Amazon, Flipkart, IKEA, Swiggy, Zomato and OYO. Built for the Naan Mudhalvan program.

**Author:** _your name, register number, college_

## Features
- Home, Party and Jewelry planners with budget-aware AI recommendations
- Optional outfit photo for jewelry (multimodal Gemini)
- Register, login, session handling and history (web app)
- Fallback suggestions if the AI is unavailable

## Repository structure
| Folder | Contents |
|---|---|
| `backend/` | FastAPI + Gemini web app (see its README to run) |
| `flutter_app/` | Android app source in Flutter |
| `docs/` | Project report (Word), presentation (PPT) and a single-page web demo |

## Run the web app
```
cd backend
pip install -r requirements.txt
copy .env.example to .env and add your Gemini API key
python main.py
```
Open http://127.0.0.1:8000

## Tech stack
FastAPI, Google Gemini (google-genai), SQLite, Jinja2, HTML/CSS/JS, Flutter.

## Screenshots
_Add screenshots of your running app here._

## Note
Never commit your `.env` file. It contains your secret API key.
