# 📘 AI Deep Research Agent

A sophisticated research assistant that leverages OpenAI's Agents SDK and Firecrawl's deep research capabilities to perform comprehensive web research and generate enhanced analytical reports on any topic.

## ✨ Features

- **🔍 Deep Web Research**: Automatically searches and analyzes multiple web sources
- **🤖 Multi-Agent Enhancement**: Two-phase research process with specialized agents
- **📊 Real-time Progress**: Live updates during the research process
- **📄 Enhanced Reports**: Comprehensive analysis with examples and case studies
- **💾 Export Functionality**: Download research reports as markdown files
- **🎯 Customizable Parameters**: Adjustable research depth and scope

## 🏗️ Architecture

The system employs a two-agent architecture:

1. **Research Agent**: Conducts initial deep web research using Firecrawl
2. **Elaboration Agent**: Enhances findings with additional context and insights

## 🚀 How It Works

1. **📝 Input Phase**: User provides research topic and API credentials
2. **🔍 Research Phase**: Firecrawl performs deep web crawling and content extraction
3. **📊 Analysis Phase**: Initial research report generated from findings
4. **✨ Enhancement Phase**: Second agent elaborates with examples and deeper insights
5. **📤 Output Phase**: Enhanced report presented and available for download

## 📋 Requirements

- Python 3.8 or higher
- OpenAI API key ([Get yours here](https://platform.openai.com/))
- Firecrawl API key ([Get yours here](https://firecrawl.dev/))

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mustafa-Shoukat1/Domain_AI_agents.git
   cd Domain_AI_agents/single_agent_apps/ai_deep_research_agent
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run deep_research_openai.py
   ```

4. **Access the application**
   - Open your browser and navigate to `http://localhost:8501`
   - Enter your API keys in the sidebar
   - Start your research!

## 📖 Usage Guide

### Basic Usage
1. **Enter API Keys**: Add your OpenAI and Firecrawl API keys in the sidebar
2. **Research Topic**: Enter your research question or topic
3. **Start Research**: Click the "Start Research" button
4. **Monitor Progress**: Watch real-time research updates
5. **Review Results**: Examine the enhanced research report
6. **Download**: Export your report as a markdown file

### Research Parameters
The system uses optimized default parameters:
- **Max Depth**: 3 levels (moderate depth research)
- **Time Limit**: 180 seconds (3 minutes)
- **Max URLs**: 10 sources (comprehensive coverage)

## 🎯 Example Research Topics

- "Latest developments in quantum computing and their commercial applications"
- "Impact of climate change on marine ecosystems and biodiversity"
- "Advancements in renewable energy storage technologies"
- "Ethical considerations and governance in artificial intelligence"
- "Emerging trends in remote work technologies and productivity tools"
- "Blockchain technology applications beyond cryptocurrency"
- "Gene therapy breakthroughs and clinical applications"

## 🔧 Technical Implementation

### Core Components

- **Firecrawl Integration**: Advanced web crawling and content extraction
- **OpenAI Agents SDK**: Intelligent research orchestration
- **Streamlit Interface**: User-friendly web application
- **Async Processing**: Efficient handling of research operations

### Research Process

1. **Web Crawling**: Firecrawl searches and extracts content from multiple sources
2. **Content Analysis**: AI agents analyze and synthesize information
3. **Report Generation**: Structured research reports with citations
4. **Enhancement**: Additional context, examples, and practical implications

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Bug fixes and improvements
- New features and enhancements
- Documentation updates
- Additional research capabilities

## 📄 License

This project is part of the Domain AI Agents collection.

## 🆘 Support

For support and questions:
- Check the documentation
- Open an issue on GitHub
- Review example topics and usage patterns

