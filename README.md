# FinSight-LLM-Driven-Market-Intelligence-Tool-
FinSight is an AI-driven research tool designed to summarize and analyze financial news articles for equity research analysts. It leverages LangChain, OpenAI embeddings, and FAISS to enable fast, contextual search and question-answering over web-scraped data.

# 🚀 Features
URL & File Input: Add news article URLs directly or upload a text file containing multiple URLs.
Automated Content Extraction: Fetch full article content using LangChain’s UnstructuredURLLoader.
Vector Embeddings: Convert article text into OpenAI embeddings for semantic understanding.
FAISS-Powered Search: Store and index embeddings with FAISS for lightning-fast similarity search.
Interactive Q&A: Query the system to receive precise answers backed by processed articles with source citations.
Streamlit Interface: Intuitive UI for loading URLs, processing content, and visualizing responses.

# 🧠 How It Works
Load Articles: Input URLs or upload a text file containing multiple URLs.
Content Extraction & Splitting: Fetch and split article content for processing.
Generate Embeddings: Convert text chunks into vector representations using OpenAI.
Indexing with FAISS: Store vectors in a FAISS index for efficient similarity search.
Query & Retrieve: Ask questions and get accurate answers with links to the source articles.

# 📦 Tech Stack
LangChain — for document processing and workflow orchestration
OpenAI API — for embeddings and LLM-based question answering
FAISS — for high-speed vector similarity search
Streamlit — for interactive web interface
Python — core programming language

# ⚡ Installation
1) Clone the repository:
   git clone https://github.com/AnkitAggrwal/FinSight-LLM-Driven-Market-Intelligence-Tool
   cd FinSight
2) Install dependencies:
   pip install -r requirements.txt
3) Set up OpenAI API key:
   Create a .env file in the project root:
   OPENAI_API_KEY=your_api_key_here

# ▶️ Usage
1) Run the Streamlit app:
   streamlit run main.py
2) In the sidebar:
   Input article URLs or upload a text file containing URLs.
   Click “Process URLs” to extract, split, embed, and index content.
3) Ask questions and get context-aware answers with source references.

# 📁 Project Structure
main.py — Streamlit application
requirements.txt — Python dependencies
faiss_store_openai.pkl — Pickle file storing FAISS index
.env — Configuration for OpenAI API key

# 📖 Example Articles Used
https://www.moneycontrol.com/news/business/tata-motors-mahindra-gain-certificates-for-production-linked-payouts-11281691.html
https://www.moneycontrol.com/news/business/tata-motors-launches-punch-icng-price-starts-at-rs-7-1-lakh-11098751.html
[Buy Tata Motors: Target of Rs 743](https://www.moneycontrol.com/news/business/stocks/buy-tata-motors-target-of-rs-743-kr-choksey-11080811.html)

# 📌 Key Highlights
Fast and accurate financial news summarization
Semantic search over large collections of articles
Clean interactive interface for querying and exploring results

<img width="1419" height="772" alt="image" src="https://github.com/user-attachments/assets/e6e0514e-d795-4c7d-b52f-c0116391c625" />
