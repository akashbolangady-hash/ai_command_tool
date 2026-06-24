# AI Agent with Function Calling

A locally-run AI agent built using LLaMA and llama-cpp-python that can autonomously invoke external tools to answer user queries.

## Why I Built This

Most local LLMs are limited to generating text from their training data. I wanted to explore how a local model could interact with external tools and retrieve real-world information without relying on cloud APIs.

## Features

* Local inference using LLaMA
* Tool-calling architecture
* Weather retrieval
* Wikipedia search
* Date and time utilities
* Structured response handling

## Tech Stack

* Python
* llama-cpp-python
* Jupyter Notebook
* REST APIs

## Architecture

User Query
↓
LLaMA Model
↓
Tool Selection Logic
↓
External Tool Execution
↓
Structured Response

## Example

User: What's the weather in Pune?

Agent:
Current temperature: 31°C
Humidity: 64%

## What I Learned

* LLM integration
* Function-calling design
* API integration
* Prompt structuring
* Local model deployment

## Future Improvements

* RAG support
* Memory
* Additional tools
* Multi-agent workflows
