# Finance Agent

A modern AI-powered finance assistant built with [Agno](https://www.agno.com/) and Nebius AI Studio. It provides real-time stock information, financial analysis and market insights through a friendly web interface.

## Features

- **Real-time stock data:** Fetch current and historical stock prices from major markets.
- **Analyst recommendations:** Access buy/sell/hold recommendations and key fundamentals.
- **Web search integration:** Pull the latest financial news using DuckDuckGo tools.
- **Interactive UI:** An intuitive, live-updating interface built with the Agno playground.
- **Structured output:** Tables for numeric data and concise bullet lists for textual information.

## Getting Started

### Prerequisites

- Python 3.10 or higher
- Nebius AI Studio API key

### Installation

```bash
# clone your fork of this repository
git clone https://github.com/AbdullahRasheed45/ai-projects-finance-agent.git
cd ai-projects-finance-agent

# install dependencies
pip install -r requirements.txt
```

### Configuration

Create a `.env` file in the project root and add your Nebius API key:

```env
NEBIUS_API_KEY=your_nebius_api_key_here
```

### Running the app

Run the agent locally:

```bash
python main.py
```

By default the web playground will be available at `http://localhost:8000`.

## Example queries

- "What’s the current price of AAPL stock?"
- "Show me analyst recommendations for TSLA."
- "Get the latest news about Bitcoin."
- "Compare the performance of Google and Amazon over the last month."

## License

This project is licensed under the MIT License as part of the [Awesome AI Apps](https://github.com/Arindam200/awesome-ai-apps) collection.
