# Market Trend Analysis Crew

## Overview
This project uses the `crewai` library to create a multi-agent system for analyzing market industry trends. The system leverages AI agents to identify top market trends, analyze sentiments, perform competitive analysis, and develop strategic recommendations for a specified target audience and year.

## Prerequisites
- Python 3.12+
- Required packages: `crewai`, `crewai-tools`, `python-dotenv`, `pydantic`
- API keys:
  - OpenAI API key (`OPENAI_API_KEY`)
  - Serper API key (`SERPER_API_KEY`)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivamGoyal03/Azure-AI-Foundry-Webinar/
   cd Azure-AI-Foundry-Webinar/day-2/code/market-trend
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project root and add your API keys:
   ```
   OPENAI_API_KEY=your_openai_api_key
   SERPER_API_KEY=your_serper_api_key
   ```

## Usage
1. Run the notebook:
2. The script initializes a `Crew` with agents for trend analysis, sentiment analysis, competitive analysis, and strategy planning. It outputs a list of top market trends and related insights for the specified audience (e.g., millennials) and year (e.g., 2025).

## Project Structure
- `market_trend_analyst.ipynb`: Main script defining agents, tasks, and the crew.
- `.env`: Environment file for storing API keys (not tracked in git).
- `requirements.txt`: To install all the dependencies.
- `README.md`: This file.

## Agents and Tasks
- **Trend Analyst**: Identifies top market trends using web search and scraping tools.
- **Sentiment Analyst**: Analyzes sentiment around market trends (requires definition).
- **Competitive Analyst**: Performs competitive analysis (requires definition).
- **Strategy Planner**: Develops strategic recommendations (requires definition).

## Notes
- Replace placeholder variables `{year}` and `{target_audience}` in task descriptions with actual values (e.g., "2025", "millennials").
- The custom `CalculatorTools` class is included but not used by default. Add it to agent tools if needed.
- For issues with `crewai`, ensure compatibility with `pydantic==2.5.0` and `crewai==0.30.11`.

## Troubleshooting
- **TypeError in FlowTrackable**: Ensure all agents and tasks are defined, and update `crewai` to a stable version.
- **API Key Errors**: Verify `OPENAI_API_KEY` and `SERPER_API_KEY` in the `.env` file.
- **Tool Issues**: Test `SerperDevTool` and `ScrapeWebsiteTool` independently to confirm functionality.
