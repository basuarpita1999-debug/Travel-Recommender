# Travel-Recommender
Travel Recommendation using AI

# AI Travel Buddy

Lightweight Streamlit app that helps users discover travel ideas, fetches LLM-generated recommendations and global events, and keeps a small personal history. Built to demo a travel UX with a Chatbot, curated suggestions and simple UI theming via a custom CSS file.

## Features
- Discover page: enter Destination, Budget, Experience type (multi-select) and get structured AI recommendations (title, description, links).
- Chatbot: conversational travel assistant with streaming responses.
- Your Journeys: past trips with visuals and suggested next-destinations (adds prompts to Chatbot).
- What's Happening: fetches notable global events for a selected month (title, date, location, hook, details).
- Custom CSS in `assets/custom.css` to style the app (background, cards, buttons, colors).

## Quick start

1. Clone / open the project folder:
   - /Users/shbabane/Desktop/Python-travel-ai

2. Create a virtualenv and install deps:
python -m venv .venv source .venv/bin/activate # macOS / Linux pip install -r requirements.txt


3. Configure API key (Streamlit secrets):- Create `.streamlit/secrets.toml` with:  ```  GROQ_API_KEY = "your_groq_api_key_here"  ```- Or set the environment/CI variable referenced in your deployment.4. Run the app:


3. Configure API key (Streamlit secrets):
- Create `.streamlit/secrets.toml` with:
  ```
  GROQ_API_KEY = "your_groq_api_key_here"
  ```
- Or set the environment/CI variable referenced in your deployment.

4. Run the app:

