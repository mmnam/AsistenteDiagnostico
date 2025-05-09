Medical Diagnosis Assistant – Capstone Project

This repository contains the implementation of a Retrieval-Augmented Generation (RAG)-based medical assistant that suggests likely medical diagnoses from structured symptom data. It is built using LangChain, FAISS, and a local LLM model hosted via Ollama.

Project Overview

This assistant receives a natural language question (e.g., “What condition is associated with chest pain and fatigue?”), retrieves the most relevant medical records from a vector store, and generates a context-grounded diagnostic suggestion.
