# Conversational Memory: Agent-Driven Multi-Step Retrieval in RAG Applications

![Project Logo](path/to/logo.png)  
*An intelligent Q&A system that leverages conversation memory and agent-driven multi-step retrieval.*

## Overview

**Conversational Memory** is a state-of-the-art Retrieval-Augmented Generation (RAG) application designed to enhance conversational AI. This project integrates two key capabilities:

1. **Conversational Memory:** The system stores and utilizes past user interactions (chat history) to ensure that follow-up questions are interpreted with full context.
2. **Agent-Driven Multi-Step Retrieval:** Using an LLM-powered agent (e.g., via the `create_react_agent` mechanism), the application autonomously determines when to perform additional retrieval steps. This enables it to iteratively refine queries and gather more comprehensive context from external sources.

By combining these elements, the system delivers precise, context-aware responses that make the AI assistant much more effective in multi-turn conversations.

## Features

- **Conversational Memory:** Retains a history of user and AI messages to provide context for current queries.
- **Agent-Driven Retrieval:** Empowers the LLM to decide on multiple retrieval steps when needed, dynamically refining its search queries.
- **RAG Architecture:** Merges external document retrieval with advanced language model generation to produce accurate answers.
- **Easy Integration:** Built with modular components from LangChain and LangGraph, making it flexible and scalable.
- **Interactive and Iterative:** Supports both simple one-step retrieval chains and complex multi-step retrieval via agent discretion.


