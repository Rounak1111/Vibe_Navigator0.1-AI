🌟 Vibe Navigator — Your AI-Powered City Explorer
Explore the vibes of your city, one place at a time. ☕🌿🎶🔥

🚀 Project Overview
Vibe Navigator is a modern web application designed to help users explore the atmosphere (“vibe”) of various public places like cafes, parks, and gyms across different cities.
It scrapes real user reviews from platforms such as Reddit, Google Maps, and TripAdvisor, then uses Generative AI (Google Gemini API) to summarize the vibe in a friendly, storytelling tone, making your city explorations fun and personal.

🎯 Key Features
🔍 Search by City & Category: Find places like "Cafes in Delhi" or "Parks in Bangalore".

🃏 Vibe Cards: See clean, emoji-filled summaries of each place with mood indicators and vibe tags.

✨ Personalized Queries: Ask questions like "Find me a quiet cafe with a floral theme in Mumbai."

🔗 Transparent Summaries: Each vibe summary references actual user reviews to build trust.

🌍 Optional Google Maps Integration: Visualize your favorite spots on an interactive map.

🤖 Powered by Google Gemini AI: Summaries are generated using Gemini’s cutting-edge LLM.

📱 Clean, Mobile-First Design: Fully responsive with a vibrant UI and modern animations.

🛠️ Tech Stack
Frontend	Backend	AI & Data	Database	Deployment
React.js (Vite)	Flask (Python)	Google Gemini API (RAG)	MongoDB	Render / Railway
Tailwind CSS	Flask-RESTful API	BeautifulSoup, Reddit API	-	-
Axios, React Router				

🔑 API & Integrations
Google Gemini API: For vibe summaries and natural language generation.

Reddit Scraper: For initial user review data. (Google Maps/TripAdvisor scraping optional.)

Google Maps API (Optional): For map views in the UI.

⚙️ Local Setup
Prerequisites
Node.js & npm

Python 3.9+

MongoDB (optional for production)

Google Gemini API Key

Backend Setup (Flask)
bash
Copy
Edit
cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt

# Set your Gemini API key
export GEMINI_API_KEY="YOUR_API_KEY"

# Run the Flask server
python app.py
Frontend Setup (React.js + Vite)
bash
Copy
Edit
cd frontend
npm install
npm run dev

🌐 Live Demo
👉 Web App: https://resonant-custard-99c1a5.netlify.app

🎥 Demo Video
👉 LinkedIn Demo Video:
Watch here

🏁 Future Scope
🤝 Add a chat-based GenAI agent for interactive city guide planning.

🧭 Integrate route planner and nearest-place recommendation features.

🗺️ Expand support for scraping from TripAdvisor, Google Maps.

🧠 Use RAG (Retrieval-Augmented Generation) for deeper citations.

💬 Contact
👨‍💻 Rounak Mishra
📧 Email: rounakmishra111@gmail.com
🔗 LinkedIn: linkedin.com/in/rounakmishra01

