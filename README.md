# AI-AGENT

# Multitool AI Agent for Reasoning and Information Extraction
# Project Overview
This project implements a simple but powerful AI Agent that simulates reasoning over multiple tools to answer natural language queries. The agent selects from a predefined set of tools like mathematical calculation, string operations, capital city retrieval, and factual lookups to compute the final answer in a step-by-step format, mimicking the behavior of interpretable autonomous AI systems.

# Objectives
Understand how agents use tools to solve multi-step problems.

Implement a modular and interpretable AI agent in Python.

Demonstrate reasoning using real-world data (e.g., countries, capitals, dog breeds).

Practice chaining logic and tool-based reasoning.

# Features
Tool-based reasoning: Agent chooses relevant tools like get_capital, calculate, string_length, and average_dog_weight.

Chain-of-thought output: Each question is answered step-by-step showing the agent’s internal thoughts, actions, and observations.

Customizable tools: Easily extendable by adding more tools to the registry.

# Tools Used
Python 3

No external libraries required – only core Python functions

# File Structure
├── ai_agent.py # Main agent logic and tools ├── README.md # Project overview and setup

# How to Run
Open ai_agent.py or copy the code into a Python script or Jupyter/Colab notebook.

Modify or use the query() function with natural language inputs.

Observe how the agent decomposes the query and uses tools to find answers.

# Example:
query("What is the capital of France and how long is its name?")

# Example Output
Question: What is the capital of France and how long is its name? Thought: I need the capital of the country. Action: get_capital: France Observation: Paris Action: string_length: Paris Observation: 5 Answer: The capital of France is Paris and its name is 5 characters long.

# Future Improvements
Integrate LLMs (like GPT or Claude) to generate tool usage plans dynamically.

Add support for PDF/text document parsing.

Connect with real APIs (e.g., RESTful knowledge bases).

Build a Streamlit UI for live question answering.

# Output:
<img width="1084" height="299" alt="image" src="https://github.com/user-attachments/assets/f15e1ee5-6bf1-4f62-bf8a-4d6e86e40bbf" />
