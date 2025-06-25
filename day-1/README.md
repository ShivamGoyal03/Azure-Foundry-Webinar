# Day 1: Introduction to AI Agents + Azure AI Foundry Overview

Welcome to Day 1 of the **Azure AI Foundry Agent Webinar Series**! Today we focus on understanding what AI Agents are, why they matter, and how to get started with Azure AI Foundry.

---

## 📄 Contents

- [AI Agents: Concepts and Types](./ai-agents.md)
- [What is Azure AI Foundry?](./what-is-foundry.md)

---

## 🎯 Objectives

By the end of Day 1, you will:

- Understand the fundamentals of AI agents and their real-world applications.
- Explore different types of agents and when they are most effective.
- Get introduced to Microsoft’s Azure AI Foundry platform.
- Learn how to create and test a basic AI Agent using GPT-4o-mini.

---

## 📚 Theoretical Foundations

### 💡 What Are AI Agents?

An **AI Agent** is an intelligent system that can:
- **Reason** about its environment
- **Plan** actions based on goals
- **Act** autonomously to achieve desired outcomes

It interacts dynamically with its environment, unlike traditional models that only respond to input.

> **Example**: A travel agent that books flights, answers questions, and improves over time.

---

## 🧱 Core Components of an Agent

| Component      | Description |
|----------------|-------------|
| **Environment** | The world in which the agent operates (e.g., flight data, weather APIs) |
| **Sensors**     | Tools to perceive the environment (e.g., data inputs, APIs) |
| **Actuators**   | Mechanisms to act on the environment (e.g., output responses, service calls) |
| **LLM (Brain)** | A large language model (e.g., GPT-4o-mini) that reasons and makes decisions |

These components work together to **create a feedback loop**, enabling the agent to learn and improve.

### 🧠 Types of Agents

- **Simple Reflex Agents**: React to current situations based on condition-action rules.
- **Model-Based Reflex Agents**: Maintain internal state models to inform decisions.
- **Goal-Based Agents**: Plan actions to achieve defined goals.
- **Utility-Based Agents**: Choose actions based on preferences and trade-offs.
- **Learning Agents**: Learn from experience and improve performance.
- **Multi-Agent Systems (MAS)**: Multiple agents working together or independently.

---

## 🤔 When Are AI Agents Effective?

AI agents excel in:

- **Open-Ended Problems**: Dynamic problem-solving without predefined paths.
- **Multi-Step Processes**: Tasks requiring tool interactions and sequential actions.
- **Continuous Improvement**: Scenarios where agents learn from feedback.

---

## 🏗️ Azure AI Foundry Introduction

Azure AI Foundry is a platform for building, customizing, and deploying intelligent agents.

- Supports agentic design patterns: ReAct prompting, memory management, self-reflection.
- Enables rapid development of robust, scalable AI agents.

---

## 🧰 Key Design Patterns

| Pattern               | Purpose |
|-----------------------|---------|
| **ReAct**             | Reasoning + Acting using internal thought steps |
| **Self-reflection**   | Agents analyze past decisions to improve |
| **Memory Management** | Track context across sessions |
| **Tool-Use Pipelines**| Connect to APIs or databases for real-world tasks |

---

## ⏭️ Next Steps

- Continue to [Day 2: Azure AI Foundry Hands-on](../day-2/README.md) for a practical guide.
- Or jump directly to the [How to Create an Agent (Step-by-Step Guide)](../day-2/how-to-create-agent.md).