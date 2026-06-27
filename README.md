# PantryPilot
PantryPilot AI 🍳

Turn what's already in your kitchen into delicious meals using Agentic AI.

PantryPilot AI is a modern, intelligent web application that acts as your personal chef. Instead of functioning as a simple chatbot, PantryPilot uses an Agentic Workflow powered by the Google Gemini API to coordinate multiple AI tasks automatically: extracting ingredients from images, planning optimal recipes, calculating nutrition, minimizing food waste, and generating smart shopping lists.

✨ Features

📸 Vision-Powered Extraction: Upload a photo of your fridge or pantry, and the AI will automatically detect and clean up a list of available ingredients.

🧠 Agentic Orchestration: The app coordinates multiple AI "agents" in the background (Vision Agent, Recipe Agent, Logistics Agent, Waste Agent).

🎲 "Surprise Me" Mode: Ask the AI to act as a Michelin-star chef and generate the single best recipe based on least food waste, fastest cooking time, and highest ingredient match.

👨‍🍳 Interactive Chef Mode: A distraction-free, step-by-step interactive cooking guide with a progress bar.

🥗 Health & Dietary Filters: Support for Vegetarian, Vegan, Keto, Halal, Gluten-Free, and more, complete with macro estimates and health scores.

♻️ Food Waste Reduction: Automatically identifies highly perishable items and suggests prioritizing them in your meals.

🛒 Smart Shopping Lists: Generates categorized grocery lists containing only the ingredients you are missing.

🛠️ Tech Stack

Frontend: HTML5, Vanilla JavaScript (ES6+), Tailwind CSS (via CDN)

Icons: Lucide Icons

AI / LLM: Google Gemini API (gemini-2.5-flash) for both text and vision capabilities.

🚀 How to Run Locally

Because PantryPilot AI is built as a highly optimized, client-side application, running it is incredibly simple. No complex backend or build tools are required.

Clone the repository:

git clone [https://github.com/yourusername/PantryPilot-AI.git](https://github.com/yourusername/PantryPilot-AI.git)
cd PantryPilot-AI


Get a Gemini API Key:

Go to Google AI Studio.

Generate a free API key.

Add your API Key:

Open index.html in your favorite code editor.

Locate the <script> tag near the bottom of the file.

Replace the empty string in const apiKey = ""; with your actual API key:

const apiKey = "YOUR_ACTUAL_API_KEY_HERE";


Launch the App:

Simply double-click index.html to open it in any modern web browser.

Alternatively, use a local server like VS Code's Live Server extension.

⚠️ Security Warning for GitHub

DO NOT commit your actual Gemini API key to a public GitHub repository.
If you plan to host this publicly (e.g., on GitHub Pages or Vercel), it is highly recommended to move the API calls to a secure backend (like Node.js, Python/Streamlit, or Serverless functions) so your API key remains hidden in a .env file.

For the Streamlit/Python backend version of this code, check the project's commit history!

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📝 License

This project is MIT licensed.
