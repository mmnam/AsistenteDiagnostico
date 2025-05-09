Medical Diagnosis Assistant – Capstone Project

This repository contains the implementation of a Retrieval-Augmented Generation (RAG)-based medical assistant that suggests likely medical diagnoses from structured symptom data. It is built using LangChain, FAISS, and a local LLM model hosted via Ollama.

Project Overview

This assistant receives a natural language question (e.g., “What condition is associated with chest pain and fatigue?”), retrieves the most relevant medical records from a vector store, and generates a context-grounded diagnostic suggestion.

Key Features

RAG Architecture: Retrieval from a structured clinical dataset
LangChain: For chaining embedding + retrieval + LLM interaction
FAISS: Efficient local vector similarity search
LLaMA 3.2:1b via Ollama: Lightweight, fully offline language generation
Manual symptom enrichment for accurate symptom matching
Optional Streamlit demo app for interactive querying
