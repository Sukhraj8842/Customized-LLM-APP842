---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
The code creates an interactive chat application using Gradio and HuggingFace's Inference API to provide information and answer questions about stress management. The MyApp class processes a PDF file on stress, extracts text, builds a searchable vector database using SentenceTransformers and FAISS, and retrieves relevant document excerpts based on user queries. The respond function integrates these excerpts into contextually relevant responses to user questions. The Gradio interface, configured with example queries and a title, launches the application, allowing users to interact with the chatbot and receive informed answers about stress management and related topics.
