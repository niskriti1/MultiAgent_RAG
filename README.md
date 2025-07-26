# 🧠 Multi-Agent RAG System

This project implements a **Multi-Agent Retrieval-Augmented Generation (RAG) system**, where each agent is specialized in a specific domain and powered by its own RAG pipeline. The agents work independently to answer domain-specific queries using relevant document retrieval and LLM-based generation.

## 🔧 Overview

- ✅ **Multi-Agent Architecture**: The system is composed of multiple autonomous agents.
- 🔍 **Each Agent is a RAG System**: Each agent performs domain-specific retrieval from its own vector store and augments the context for a language model to generate accurate answers.
- 🧠 **LLM-Powered Reasoning**: Responses are generated using an LLM, based on the most relevant retrieved chunks.

## 🧩 Agents

1. **HR Policy Agent**

   - Answers queries related to company HR policies (e.g., leave structure, benefits, code of conduct).
   - Uses HR policy documents as knowledge base.

2. **School Leave Policy Agent**

   - Specializes in handling questions about student and teacher leave rules, absence guidelines, and school-specific policies.
   - Uses documents from school administration or education boards.

3. **Cooking Recipe Agent**
   - Assists users with cooking instructions, substitutions, timing, and related questions.
   - Retrieves context from a collection of structured recipe documents.
