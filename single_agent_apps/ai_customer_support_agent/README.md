# 🛒 AI Customer Support Agent with Memory

A sophisticated Streamlit-based customer support chatbot that leverages OpenAI's GPT-4 model and maintains persistent memory of customer interactions using the Mem0 library with Qdrant vector database.

## ✨ Features

- **Intelligent Chat Interface**: Natural language conversations with AI-powered responses
- **Persistent Memory**: Remembers customer interactions, preferences, and history
- **Synthetic Data Generation**: Creates realistic customer profiles for testing and demonstration
- **Customer Profile Management**: View and manage customer information and order history
- **Real-time Memory Retrieval**: Contextual responses based on past interactions
- **Streamlit Web Interface**: User-friendly web application interface

## 🏗️ Architecture

- **Frontend**: Streamlit web application
- **AI Model**: OpenAI GPT-4 for natural language processing
- **Memory Store**: Mem0 with Qdrant vector database for persistent memory
- **Data**: Synthetic customer profiles and order histories

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- OpenAI API key
- Docker (for Qdrant vector database)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Mustafa-Shoukat1/Domain_AI_agents.git
cd Domain_AI_agents/single_agent_apps/ai_customer_support_agent
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Set up Qdrant vector database**
```bash
# Pull Qdrant Docker image
docker pull qdrant/qdrant

# Run Qdrant container
docker run -p 6333:6333 -p 6334:6334 \
    -v "$(pwd)/qdrant_storage:/qdrant/storage:z" \
    qdrant/qdrant
```

4. **Run the application**
```bash
streamlit run customer_support_agent.py
```

5. **Access the application**
   - Open your browser and navigate to `http://localhost:8501`
   - Enter your OpenAI API key when prompted
   - Start chatting with the AI customer support agent

## 📖 Usage

1. **Enter Customer ID**: Use the sidebar to input a unique customer identifier
2. **Generate Test Data**: Click "Generate Synthetic Data" to create a realistic customer profile
3. **View Customer Profile**: Check customer information and order history
4. **Start Chatting**: Ask questions about orders, returns, products, or any support-related queries
5. **Memory Persistence**: The agent remembers previous conversations and customer details

## 🔧 Configuration

The application uses the following default configuration:
- **Qdrant Host**: localhost
- **Qdrant Port**: 6333
- **OpenAI Model**: GPT-4
- **Memory Provider**: Qdrant vector store

To modify these settings, update the configuration in `customer_support_agent.py`.

## 📋 Example Use Cases

- Order status inquiries
- Product recommendations based on purchase history
- Return and refund requests
- Technical support for electronic products
- Account management and updates

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## 📄 License

This project is part of the Domain AI Agents collection.
