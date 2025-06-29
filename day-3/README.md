# Day 3: MCP & Deployment

Welcome to Day 3 of the **Azure AI Foundry Agent Webinar Series**! Today, you'll learn about MCP (Model Context Protocol) prebuilt servers, how they simplify agent deployment, and how to use them in real-world scenarios.

---

## 🎯 Objectives

By the end of Day 3, you will:
- Understand what MCP (Model Context Protocol) is and why it matters
- Explore prebuilt MCP servers and their use cases
- Learn how to deploy and connect agents to MCP servers
- Get hands-on with a deployment workflow

---

## 🧩 What is MCP?

MCP (Model Context Protocol) is a standard for connecting AI agents and applications to a variety of models and tools, enabling flexible, modular, and scalable AI solutions.

- **Prebuilt MCP servers** provide ready-to-use endpoints for common AI tasks (e.g., retrieval, summarization, Q&A)
- They allow you to quickly integrate advanced capabilities into your agents without building everything from scratch

For a deep dive into MCP architecture and concepts, see [mcp.md](./mcp.md).

---

## 🚀 Hands-on: Using MCP Prebuilt Servers

1. **Explore available MCP servers** in Azure AI Foundry or via the [MCP Servers GitHub](https://github.com/modelcontextprotocol/servers)
2. **Connect your agent** to a prebuilt server using the Azure AI Foundry portal or SDK
3. **Test your agent** with the new capabilities (e.g., retrieval-augmented generation, document Q&A)

> For a step-by-step guide, see the [MCP for Beginners repository](https://github.com/microsoft/mcp-for-beginners)

---

## 🗂️ Code Samples in This Directory

| Directory         | Description                                                                                   | Client/Server | Navigation                          |
|-------------------|-----------------------------------------------------------------------------------------------|---------------|-------------------------------------|
| `code/`           | Live AI agent system: GitHub profile analysis, project ideation, and event recommendations    | Both          | [README](../day-3/code/README.md)        |
| `simple-mcp/`     | Minimal MCP server and client example                                                         | Both          | [README](./simple-mcp/README.md)    |
| `web-search-mcp/` | MCP server/client for web search integration                                                  | Both          | [README](./web-search-mcp/README.md)|

Each subdirectory contains its own README with setup and usage instructions for the respective MCP code sample.

---

## 🛠️ Example Workflow

- Select a prebuilt MCP server (e.g., retrieval, summarization)
- Configure your agent to use the MCP endpoint
- Deploy and test the agent in the playground
- Monitor and iterate as needed

---

## 📚 Resources
- [MCP for Beginners (GitHub)](https://github.com/microsoft/mcp-for-beginners)
- [MCP Servers (GitHub)](https://github.com/modelcontextprotocol/servers)
- [MCP Introduction (Official Site)](https://modelcontextprotocol.io/introduction)
- [MCP Architecture and Concepts](./mcp.md)

---

## 📝 Recent Contributions

Here are some recent contributions and related work you may find useful:

- [web-search-mcp (Advanced Topics)](https://github.com/microsoft/mcp-for-beginners/tree/main/05-AdvancedTopics/web-search-mcp)
- [HTTP Streaming Solution (Python)](https://github.com/microsoft/mcp-for-beginners/tree/main/03-GettingStarted/06-http-streaming/solution/python)
- [Practical Implementation Samples (Python)](https://github.com/microsoft/mcp-for-beginners/tree/main/04-PracticalImplementation/samples/python)
- [Case Study Scenarios 3, 4, 5](https://github.com/microsoft/mcp-for-beginners/blob/main/09-CaseStudy/README.md)
- [GitHub MCP Sample](https://github.com/microsoft/ai-agents-for-beginners/tree/main/11-mcp/code_samples/github-mcp)

---

Navigate to the code samples above for hands-on practice, and use the resources to deepen your understanding of MCP and agent deployment!
