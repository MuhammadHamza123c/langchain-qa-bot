Multi-LLM Question Answering Bot

A simple project that demonstrates how to build a question-answering bot using two different Large Language Models (LLMs): Groq and Gemini.
The bot takes a user’s question as input and returns an AI-generated answer.

🚀 Features

Uses Groq and Gemini models for generating responses.

Easy to switch between different LLMs.

Clean Jupyter Notebook implementations (main_groq.ipynb and main_gemini.ipynb).

.
├── main_gemini.ipynb   # Notebook using Gemini API  
├── main_groq.ipynb     # Notebook using Groq API  
├── .gitignore          # Hides .env and other sensitive files  
└── README.md           # Project documentation

git clone https://github.com/MuhammadHamza123c/langchain-qa-bot.git
cd langchain-qa-bot



Create a .env file and add your API keys:

GROQ_API_KEY=your_groq_api_key_here
GEMINI_API_KEY=your_gemini_api_key_here


Open either notebook (main_gemini.ipynb or main_groq.ipynb) in Jupyter or Google Colab.

Run the cells and ask questions!


📌 Example Usage

Input:

Question: What is Machine Learning?


Output (Gemini or Groq):

Machine Learning is a subset of Artificial Intelligence that enables systems to learn from data and improve performance over time without being explicitly programmed.

📚 Tech Stack

Python

Jupyter Notebook

Groq API

Gemini API

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📜 License

This project is licensed under the MIT License.



