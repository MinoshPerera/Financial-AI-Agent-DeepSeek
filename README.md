# DeepSeek-Powered AI Agent for Financial Intelligence

An advanced AI assistant that automates financial research by integrating real-time market data, company fundamentals, news analysis, and web search — powered by [DeepSeek](https://platform.deepseek.com/). This intelligent agent combines Yahoo Finance tools and DuckDuckGo search within a multi-agent system for comprehensive, data-backed financial insights.

## 🎯 What This Agent Does

- **📈 Stock Analysis**: Real-time prices, fundamentals, analyst recommendations
- **📰 News Integration**: Latest financial news and market updates  
- **🔍 Web Search**: Context-aware financial research and explanations
- **🤝 Multi-Agent System**: Specialized agents working together
- **💻 Interactive Interface**: Both CLI and web-based playground

Built with the [PHI SDK](https://github.com/phidatahq/phidata) and powered by DeepSeek's LLMs, this solution serves as your AI financial co-pilot.

## ✨ Key Features

- ✅ **Free to Use**: DeepSeek API offers generous free limits
- ✅ **High Performance**: GPT-4 level reasoning capabilities
- ✅ **Real-time Data**: Live stock prices, news, and market data
- ✅ **Multi-modal Research**: Combines quantitative data with qualitative insights
- ✅ **Web Playground**: Interactive browser interface
- ✅ **Secure**: Environment variable handling for API keys

## 🚀 Quick Start

### 1. Clone & Setup
```bash
git clone https://github.com/yourusername/AI-Powered-Financial-Research-Agent.git
cd AI-Powered-Financial-Research-Agent

# Create virtual environment
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### 2. Configure API Keys
Create a `.env` file in the root directory:
```env
DEEPSEEK_API_KEY=your_deepseek_api_key_here
PHI_API_KEY=your_phi_api_key_here  # Optional
```

### 3. Run the Agent
**Command Line Interface:**
```bash
python financial_agent.py
```

**Web Interface:**
```bash
python playground.py
```
Then open http://localhost:7777 in your browser.

## 🔑 API Keys Required

### DeepSeek API (Required - Free)
- Get your free API key: https://platform.deepseek.com/
- Generous free tier with high rate limits
- No credit card required for basic usage

### PHI API (Optional)
- Enhanced features: https://phidata.com/
- Not required for basic functionality

## 💡 Example Queries

Try these sample queries to explore the agent's capabilities:

```
"Get current stock price and analyst recommendations for AAPL"
"Compare NVDA vs AMD fundamentals and recent performance"
"What's the latest news about Tesla's earnings?"
"Search for information about AI chip market trends"
"Analyze Microsoft's financial health and growth prospects"
```

## 🛠️ How It Works

| Component | Description |
|-----------|-------------|
| **DeepSeek LLM** | Core reasoning engine with tool calling support |
| **Yahoo Finance Tools** | Real-time stock data, fundamentals, recommendations |
| **DuckDuckGo Search** | Web search for recent news and context |
| **Multi-Agent System** | Specialized agents for different tasks |
| **PHI Framework** | Orchestrates agent interactions and workflows |

## 📁 Project Structure

```
AI-Powered-Financial-Research-Agent/
├── venv/                    # Virtual environment
├── .env                     # API keys (create this)
├── .gitignore              # Git ignore rules
├── requirements.txt        # Python dependencies
├── financial_agent.py      # Main CLI agent
├── playground.py           # Web interface
└── README.md              # This file
```

## 🎨 Sample Output

**Query:** "Summarize analyst recommendations for AAPL"

**Response:**
```
🍎 Apple Inc. (AAPL) Analysis

📊 Current Price: $185.25 (+2.1%)
🎯 Average Target: $195.20
📈 Analyst Ratings:
   • 24 Buy ratings
   • 5 Hold ratings  
   • 1 Sell rating

📰 Recent News:
   • Apple unveils M4 chip lineup [TechCrunch]
   • iPhone sales exceed expectations [Reuters]
   • Services revenue hits record high [Bloomberg]

💡 Summary: Strong buy consensus with upside potential to $195
```

## 🧠 Why DeepSeek?

- **🆓 Free API**: Generous limits without upfront costs
- **⚡ Fast**: Quick response times for real-time analysis  
- **🎯 Accurate**: GPT-4 level performance on financial tasks
- **🔧 Tool Support**: Native function calling for data integration
- **📈 Scalable**: Handles complex multi-step financial research

## 🔧 Dependencies

Core requirements (auto-installed via `requirements.txt`):
```
phi
python-dotenv
yfinance
duckduckgo-search
```

## 🤝 Contributing

We welcome contributions! Here's how:

1. Fork this repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Add feature"`
4. Push to branch: `git push origin feature-name`
5. Submit a Pull Request

## 🐛 Troubleshooting

**Common Issues:**

- **API Key Error**: Ensure your `.env` file has valid DeepSeek API key
- **Import Error**: Check virtual environment is activated
- **Connection Error**: Verify internet connection for real-time data
- **Rate Limits**: DeepSeek free tier has generous but finite limits

## 📄 License

This project is open source. Feel free to use, modify, and distribute.

## 📬 Contact & Support

**Author**: Minosh Perera  
**GitHub**: [@MinoshPerera](https://github.com/MinoshPerera/)  
**LinkedIn**: [@minoshperera](https://linkedin.com/in/minoshperera/) 
**Email**: sithijaperera3@gmail.com

---

### 🚀 Ready to Get Started?

1. **Get your free DeepSeek API key** → https://platform.deepseek.com/
2. **Clone this repo** and follow the setup steps above
3. **Start analyzing stocks** with AI-powered insights!

*Empower your financial research with AI. Dive into markets, trends, and fundamentals — all in seconds.*
