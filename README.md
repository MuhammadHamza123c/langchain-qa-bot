Multi-LLM Question Answering Bot
This project provides a simple, yet effective, way to build a question-answering bot that leverages two distinct Large Language Models (LLMs): Groq and Gemini. The bot takes a user's question as input and returns an AI-generated answer. It's designed to be a straightforward demonstration of how to integrate and switch between different LLMs for generating responses.

🚀 Features
Dual-Model Support: Easily switch between Groq and Gemini models for generating responses.

Simple Implementation: The bot is built with clean and easy-to-understand Jupyter Notebooks (main_groq.ipynb and main_gemini.ipynb), making it great for learning and experimentation.

📁 Project Structure
.
├── main_gemini.ipynb       # Notebook for using the Gemini API
├── main_groq.ipynb         # Notebook for using the Groq API
├── .gitignore              # Hides sensitive files like .env
└── README.md               # Project documentation
🛠️ Setup and Installation
Clone the repository:

Bash

git clone https://github.com/MuhammadHamza123c/langchain-qa-bot.git
cd langchain-qa-bot
Set up API keys: Create a .env file in the project's root directory and add your API keys. You can get these from the respective Groq and Gemini developer platforms.

GROQ_API_KEY=your_groq_api_key_here
GEMINI_API_KEY=your_gemini_api_key_here
💡 Usage
Open the notebook: Open either main_gemini.ipynb or main_groq.ipynb in a Jupyter Notebook environment or Google Colab.

Run the cells: Follow the instructions within the notebook to install dependencies and run the code.

Ask a question: Once the notebook is set up, you can input a question and get an AI-generated answer.

Example
Input:
Question: What is Machine Learning?

Output (from either model):
Machine Learning is a subset of Artificial Intelligence that enables systems to learn from data and improve performance over time without being explicitly programmed.

📚 Tech Stack
Python: The primary programming language used.

Jupyter Notebook: The environment for the bot's implementation.

Groq API: For accessing the Groq language model.

Gemini API: For accessing the Gemini language model.

🤝 Contributing
Contributions are always welcome! If you find a bug or have an idea for an improvement, feel free to open an issue or submit a pull request.

📜 License
This project is licensed under the MIT License. For more details, see the LICENSE file in the repository.
