# Natural Language Processing Project

This repository presents an end-to-end implementation of a **Retrieval-Augmented Generation (RAG)** system for question answering using a custom-built dataset. It is the result of combining natural language understanding, deep learning, and efficient information retrieval.

---

## Project Summary

The goal of this project is to explore and implement a system that can effectively **retrieve relevant information** from a given corpus and **generate accurate answers** to natural language questions. The approach is rooted in the RAG paradigm, which combines the strengths of traditional retrieval techniques with generative models like transformers.

I built and trained models that simulate real-world NLP scenarios, such as:

- Open-domain Question Answering  
- Context-aware Generation  
- Retrieval-based Query Handling  

---

## Dataset: (Hugging Face Based)

I used a custom dataset named **RAG 12000**, designed to support advanced RAG-based modeling. It includes:

- **12,000 samples** in total  
- **80/20 train-test split**  

Each entry contains:
- `context`: a paragraph sourced from the Falcon RefinedWeb corpus  
- `question`: generated using GPT-4, based on the context  
- `answer`: also generated with GPT-4, matching the context and question  

The dataset enables both **retriever training** (finding relevant contexts) and **reader training** (answering based on retrieved context).

---

## Project Structure & Features

The project is organized across two notebooks:

### `Notebook.ipynb`
- Google Drive integration (for dataset and output storage)  
- Data loading and cleaning  
- Tokenization and formatting  
- Model definition (likely using Hugging Face Transformers)  
- Training loop with evaluation metrics  
- Visualizations of loss and performance  

### `DEMO.ipynb`
- Focuses on demonstrating the model  
- Example queries and outputs  
- Walkthrough of retrieval + answer generation pipeline  
- Intended for presentation or user testing  

---

## Dependencies

- [Hugging Face Transformers](https://huggingface.co/transformers/)  
- [Weights & Biases (wandb.ai)](https://wandb.ai)  
- Google Colab  
- Google Drive  

---


## Contact

For questions, clarifications, or feedback, feel free to reach out:

Email: [michael.alibeaj@mail.polimi.it]
GitHub: [MikeTech01]
