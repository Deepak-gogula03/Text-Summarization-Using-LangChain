# 📄 Text Summarization System using LangChain and OpenAI

## 🚀 Project Overview

The **Text Summarization System** is a Generative AI application built using **LangChain** and **OpenAI GPT Models** to generate concise, meaningful, and context-aware summaries from large textual content.

The project demonstrates multiple summarization techniques available in LangChain, ranging from simple prompt-based summarization to advanced document processing pipelines such as **Stuff Documents Chain**, **Map Reduce Chain**, and **Refine Chain**.

This project provides a practical understanding of how Large Language Models (LLMs) can be leveraged to process lengthy documents efficiently while maintaining contextual accuracy.

---

## 🎯 Problem Statement

Large documents, research papers, articles, reports, and transcripts often contain thousands of words, making it difficult to extract key insights quickly.

This project addresses that challenge by:

* Processing large textual content efficiently
* Generating concise summaries
* Reducing information overload
* Preserving important contextual information
* Demonstrating scalable summarization workflows using LangChain

---

## 🏗️ Solution Architecture

<img width="1672" height="941" alt="architecture" src="https://github.com/user-attachments/assets/694e8e47-58da-419c-813e-5207c447111c" />


### Workflow

1. Input Document/Text
2. Text Preprocessing
3. Prompt Engineering
4. Document Chunking
5. Summarization Chain Execution
6. Context Aggregation
7. Summary Generation using OpenAI GPT Models
8. Final Consolidated Summary

---

## ✨ Key Features

### 📌 Prompt-Based Summarization

Generate summaries directly using custom prompts and OpenAI language models.

### 📌 Prompt Templates

Create reusable and dynamic prompts using LangChain PromptTemplate.

### 📌 LLMChain Integration

Build modular and reusable summarization workflows using LangChain chains.

### 📌 Stuff Documents Chain

Combine complete document content into a single prompt and generate summaries.

### 📌 Map Reduce Summarization

Handle large documents through:

* Document Splitting
* Individual Chunk Summarization
* Summary Aggregation
* Final Summary Generation

### 📌 Refine Summarization Chain

Generate summaries iteratively by refining previous outputs and improving contextual quality.

### 📌 Recursive Text Splitting

Process large documents efficiently using RecursiveCharacterTextSplitter.

### 📌 Multi-Language Summarization

Generate summaries in different languages using prompt-driven approaches.

---

## 🛠️ Technology Stack

| Category                | Technologies                   |
| ----------------------- | ------------------------------ |
| Programming Language    | Python                         |
| LLM Framework           | LangChain                      |
| Language Model          | OpenAI GPT-4o-mini             |
| Prompt Engineering      | LangChain PromptTemplate       |
| Text Splitting          | RecursiveCharacterTextSplitter |
| Summarization Chains    | Stuff, Map Reduce, Refine      |
| Environment Management  | Python Dotenv                  |
| Development Environment | Jupyter Notebook               |

---

## 📂 Project Structure

```text
Text-Summarization-System-Using-LangChain/
│
├── TextSummarization.ipynb
├── requirements.txt
├── .env
├── README.md
│
├── images/
│   ├── architecture.png
│   ├── prompt_summary.png
│   ├── map_reduce_output.png
│   ├── refine_output.png
│
└── sample_documents/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Deepak-gogula03/Text-Summarization-Using-LangChain.git
```

```bash
cd Text-Summarization-Using-LangChain
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Configuration

Create a `.env` file:

```env
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

---

## 📚 LangChain Concepts Implemented

This project demonstrates practical implementation of:

* Prompt Engineering
* Prompt Templates
* OpenAI Integration
* LLMChain
* Stuff Documents Chain
* Map Reduce Chain
* Refine Chain
* Document Chunking
* RecursiveCharacterTextSplitter
* Multi-Step LLM Workflows
* Context Management
* Text Summarization Pipelines


## 💼 Real-World Applications

* Research Paper Summarization
* Legal Document Analysis
* Financial Report Summarization
* Meeting Notes Generation
* News Article Summarization
* Enterprise Knowledge Management
* Educational Content Condensation
* Document Intelligence Systems

---

## 🎓 Skills Demonstrated

This project showcases expertise in:

* Generative AI
* LangChain Framework
* OpenAI API Integration
* Prompt Engineering
* LLM Application Development
* Natural Language Processing
* Document Intelligence
* Text Processing Pipelines
* AI Workflow Design
* End-to-End Summarization Systems
