# Interactive Chatbot using LangChain and Groq

This repository contains an interactive chatbot implemented using the LangChain framework and Groq's ChatGroq model. The chatbot is designed to handle various types of queries, including web searches and academic research, by leveraging tools such as DuckDuckGo, Arxiv, and Wikipedia. The chatbot maintains conversational context and can provide informative responses based on user input.

## Features
- Contextual Conversations: Maintains context across multiple interactions to provide coherent and relevant responses.
- Integrated Tools: Uses DuckDuckGo for web searches, Arxiv for academic queries, and Wikipedia for general knowledge.
- Streamlined User Interface: Built with IPython widgets for seamless interaction in Jupyter Notebooks.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/interactive-chatbot-langchain.git
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Set up environment variables by creating a .env file with your API keys:

makefile
Copy code
GROQ_API_KEY=your_groq_api_key
Run the notebook in Jupyter:

bash
Copy code
jupyter notebook
Usage:
Start the Jupyter Notebook and run the provided code cells to interact with the chatbot.
Enter your queries into the provided text widget to receive responses.
Contributing:
Feel free to submit issues or pull requests if you have suggestions for improvements or bug fixes.
