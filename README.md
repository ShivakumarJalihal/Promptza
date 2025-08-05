Promptza – Local Pizza Review AI Assistant
Promptza is a fully local AI assistant that answers natural language questions about a pizza restaurant based on realistic customer reviews.

It uses:

🧠 Ollama – to run LLaMA 3 or other LLMs locally

🔗 LangChain – for prompt chaining and agent logic

🔍 ChromaDB – for fast vector-based semantic search

📄 CSV Data – real restaurant reviews as the knowledge base

No API keys. No cloud. 100% offline and free.

🚀 Features:

🔎 Ask questions like "How’s the service?" or "Is the pizza spicy?"

🧠 LLM finds relevant reviews and generates smart answers

💾 All runs locally – perfect for learning and privacy

🛠️ Easily customizable for other datasets/domains

.
├── main.py                      # Chat interface and LangChain logic
├── vector.py                    # Handles embedding + vector search
├── realistic_restaurant_reviews.csv   # Dataset of customer reviews
├── requirements.txt             # Python dependencies
├── README.md                    # This file


🛠 Setup Instructions
1. Clone the repo
git clone https://github.com/ShivakumarJalihal/Promptza.git
cd Promptza

3. Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows
# source venv/bin/activate  # On Mac/Linux

3. Install dependencies
pip install -r requirements.txt

5. Run the assistant
python main.py
Make sure Ollama is installed and the model (e.g., llama3) is pulled.

🧠 Sample Questions to Ask
- "What do people say about the staff?"

- "Are the prices reasonable?"

- "How’s the taste of the cheese pizza?"

📌 To-Do / Improvements
 - Add a basic GUI using Tkinter or Streamlit

 - Add logging or analytics

 - Support multiple datasets
