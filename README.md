# LLM-Practical-Portfolio

PUSL3205 – Large Language Models and Generative AI Practical Portfolio

**Student:** Rathnayaka Mudiyanselage Amasha Udani Rathnayaka  
**Student Number:** 10965297 
**Module Code:** PUSL3205  
**Assessment:** P1 – Individual Practical Portfolio (20%)

## About This Portfolio

This repository contains my completed practical work for the PUSL3205 Large Language Models and Generative AI module.

The portfolio documents five laboratory activities covering sentiment analysis, Transformer models, parameter-efficient fine-tuning, Retrieval-Augmented Generation (RAG), and tool-using AI agents.

Each laboratory includes implementation files, supporting notebooks, screenshots of results, and documentation explaining the objectives, methods, challenges, and learning outcomes.

The practical activities were completed using Python, Google Colab, and other relevant AI development tools.

## Laboratory Index

| Lab | Laboratory Title | Main Focus | Status |
|---|---|---|---|
| 01 | Sentiment Analysis Using Traditional Machine Learning | Text preprocessing, classification, model evaluation | Completed |
| 03 | Developing a Tiny Transformer Language Model | Tokenization, Transformer training, text generation | Completed |
| 04 | Fine-Tuning an LLM Using LoRA | Parameter-efficient fine-tuning and model comparison | Completed |
| 05 | RAG Architecture | PDF processing, embeddings, document retrieval, question answering | Completed |
| 06 | Building a Tool-Using AI Agent | Calculator, SQLite memory, RAG integration, Google Calendar | Completed |

**Note:** Lab Sheet 2 is not included in this portfolio.

## Overview of Completed Laboratories

### Lab Sheet 1 – Sentiment Analysis

Developed a sentiment analysis model using traditional machine learning techniques.

The implementation involved text preprocessing, dataset preparation, model training, and evaluation using classification metrics.

**Key learning:** Understanding how machine learning models classify text and how their performance can be evaluated.

### Lab Sheet 3 – Tiny Transformer

Implemented and trained a small Transformer language model.

The practical work covered tokenization, model architecture, training, loss monitoring, and text generation.

**Key learning:** Understanding how Transformer models process sequences and generate text.

### Lab Sheet 4 – LoRA Fine-Tuning

Explored parameter-efficient fine-tuning using Low-Rank Adaptation (LoRA).

The implementation included preparing training data, configuring the fine-tuning process, comparing model responses, and saving the resulting model files.

**Key learning:** Understanding how pretrained language models can be adapted for specific tasks without updating every model parameter.

### Lab Sheet 5 – Retrieval-Augmented Generation

Developed a RAG-based question-answering system using information retrieved from PDF documents.

The implementation involved document loading, text splitting, embeddings, vector storage, and retrieval-based question answering.

**Key learning:** Understanding how external knowledge sources can improve the relevance of language model responses.

### Lab Sheet 6 – Tool-Using AI Agent

Developed a tool-using AI agent in Google Colab.

The implementation included four parts:

- **Part A:** Calculator and utility tools.
- **Part B:** Conversation memory using SQLite.
- **Part C:** Integration of calculator, memory search, and RAG search tools.
- **Part D:** Google Calendar integration for retrieving events, checking schedules, and creating events with user confirmation.

**Key learning:** Understanding how AI agents can combine multiple tools, retrieve stored information, and interact with external services.

## Technologies Used

| Area | Technologies |
|---|---|
| Programming | Python |
| Development environments | Google Colab, Jupyter Notebook, VS Code |
| Machine learning | scikit-learn, PyTorch |
| Language models | Hugging Face Transformers |
| Fine-tuning | PEFT, LoRA |
| Retrieval-Augmented Generation | LangChain, ChromaDB, sentence-transformers |
| Conversation memory | SQLite |
| External integrations | Google Calendar API |
| Version control | Git, GitHub |
| Documentation | Markdown, screenshots, notebooks |

## Repository Structure

```text
LLM-Practical-Portfolio/
│
├── Lab Sheet 1/
│   ├── notebooks/
│   ├── screenshots/
│   └── README.md
│
├── Lab Sheet 3/
│   ├── models/
│   ├── notebooks/
│   ├── screenshots/
│   └── README.md
│
├── Lab Sheet 4/
│   ├── models/
│   ├── notebooks/
│   ├── screenshots/
│   └── README.md
│
├── Lab Sheet 5/
│   ├── notebooks/
│   ├── screenshots/
│   └── README.md
│
├── Lab Sheet 6/
│   ├── notebooks/
│   ├── screenshots/
│   └── README.md
│
├── Final-Reflection.md
└── README.md
```

## Results and Evidence

Each laboratory folder contains evidence of the completed practical activities.

The evidence includes:

- Python notebooks containing the implementations.
- Screenshots showing successful execution and outputs.
- Model evaluation results where applicable.
- Documentation describing the implementation and observations.
- Saved model files where applicable.

The individual laboratory README files provide further details about the tasks performed and the results obtained.

## Challenges and Problem-Solving

During the practical activities, I encountered challenges involving software installation, package dependencies, model training, runtime errors, and API authentication.

For Lab Sheet 6, I used Google Colab as an alternative to a local development environment. I also resolved issues related to notebook execution order, SQLite memory, and Google Calendar authentication.

These experiences helped me improve my debugging skills and develop a better understanding of AI development workflows.

## Final Reflection

The practical portfolio helped me develop knowledge and skills in Natural Language Processing, Transformer architectures, fine-tuning, RAG, and AI agent development.

It also provided experience in implementing AI applications, evaluating results, troubleshooting technical problems, and documenting practical work.

My complete reflection is available in [Final-Reflection.md](Final-Reflection.md).

## Conclusion

This portfolio demonstrates my practical learning and development throughout the PUSL3205 Large Language Models and Generative AI module.

The completed laboratory activities provided valuable experience in developing and experimenting with AI models and applications, while strengthening my Python programming, problem-solving, and technical documentation skills.