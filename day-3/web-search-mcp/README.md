# Web Search MCP Server Example

This directory demonstrates how to build a real-world MCP server and client for web, news, product search, and Q&A using SerpAPI.

## Code Navigation
- [server.py](./server.py): MCP server implementation (web, news, product search, Q&A)
- [client.py](./client.py): MCP client implementation (automated and interactive modes)

## Features
- Integrates external APIs (SerpAPI) securely
- Multi-tool orchestration: web, news, product search, Q&A
- Robust error handling and logging
- Interactive and automated client modes

## Quickstart

### Prerequisites
- Python 3.8+
- SerpAPI API Key ([Get one here](https://serpapi.com/))

### Installation
```bash
# Using uv (recommended)
uv pip install -r requirements.txt
# Or using pip
pip install -r requirements.txt
```

Add your SerpAPI key to a `.env` file:
```
SERPAPI_KEY=your_serpapi_key_here
```

### Running the Server
```bash
python server.py
```

### Running the Client
```bash
python client.py           # Automated tests
python client.py --interactive  # Interactive mode
```

## Tool Overview
| Tool            | Description                        | Parameter(s)         |
|-----------------|------------------------------------|----------------------|
| general_search  | General web search                 | query (string)       |
| news_search     | Recent news articles               | query (string)       |
| product_search  | Product search                     | query (string)       |
| qna             | Direct Q&A from search engines     | question (string)    |

## Example Usage
```python
from mcp import ClientSession, StdioServerParameters
from mcp.client.stdio import stdio_client

async def run_search():
    server_params = StdioServerParameters(command="python", args=["server.py"])
    async with stdio_client(server_params) as (reader, writer):
        async with ClientSession(reader, writer) as session:
            await session.initialize()
            result = await session.call_tool("general_search", arguments={"query": "open source LLMs"})
            print(result)
```

---

For full details, see [server.py](./server.py) and [client.py](./client.py).
