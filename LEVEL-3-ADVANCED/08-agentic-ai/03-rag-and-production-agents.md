# RAG & Productionizing Agents

## Overview
Combines retrieval-augmented generation (RAG) with agent architectures for building production-ready conversational or task-oriented agents.

## Learning Objectives
- Build a RAG pipeline using embeddings and a vector store
- Integrate RAG into agent loops for tool use and memory
- Handle document chunking, embedding updates, and freshness
- Deploy agents with safety and rate-limiting considerations

## Sections
1. RAG pipeline architecture and components
2. Vector stores (FAISS, Weaviate, Pinecone) and chunking strategies
3. Agent orchestration: tools, memory, and action selection
4. Production concerns: caching, rate limits, monitoring

## Example: high-level RAG flow
1. Query -> embed -> nearest neighbors in vector store
2. Retrieve documents -> build context window
3. Prompt LLM with context -> generate answer
4. Log retrievals and model outputs for auditing

## Exercises
- Build a small RAG demo using FAISS + Hugging Face embeddings
- Implement caching and freshness checks for retrievals
- Add a tool to the agent that triggers a job (e.g., search DB) and test end-to-end
