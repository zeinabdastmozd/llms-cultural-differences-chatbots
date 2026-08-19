![Research Project](research_pipeline.png)
# 🌍 Do Large Language Models Differentiate and Adapt to Cultural Differences in Chatbots?

### A Large-Scale Study of Cultural Differentiation, Persona-Based Conversations, and Linguistic Patterns in LLMs

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![LLM](https://img.shields.io/badge/AI-Large%20Language%20Models-purple)](#)
[![NLP](https://img.shields.io/badge/NLP-Linguistic%20Analysis-green)](#)
[![Research](https://img.shields.io/badge/Project-AI%20Research-orange)](#)

---

## 📌 Overview

This repository contains the research, code, datasets, notebooks, and statistical analyses for my dissertation:

> **"Do Large Language Models Differentiate and Adapt to Cultural Differences in Chatbots?"**

The project investigates whether Large Language Models (LLMs) can generate conversational behaviour that differs according to cultural context and persona.

The research focuses on **cultural differentiation in LLM-generated conversations**, examining whether linguistic patterns vary between cultural conditions and conversational relationships.

The analysis combines:

- Large Language Models - Open-source models (Hugging Face platform)
- Persona-based conversation generation - Characters, Topics: challenging topics like religion, homosexuality, politics; temperature: the freedom given to LLM models for creativity; agreement/disagreement.
- Natural Language Processing (NLP)
- Linguistic feature extraction
- LIWC analysis
- ELFeN analysis
- Statistical analysis
- Significant-feature identification
- Cross-cultural comparison

---

# 🎯 Research Question

### Main Question

> **Do Large Language Models differentiate and adapt to cultural differences when generating chatbot conversations?**

The research investigates whether LLM-generated conversations contain measurable linguistic differences associated with cultural context and persona.

---

# 🔬 Research Pipeline

```text
                ┌──────────────────────┐
                │ Cultural Personas    │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │ LLM Conversation     │
                │ Generation (UK,IR)   │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │ Conversation Dataset │
                └──────────┬───────────┘
                           │
                           ▼
              ┌───────────────────────────┐
              │ Linguistic Feature        │
              │ Extraction                │
              │                           │
              │ • LIWC                    │
              │ • ELFeN                   │
              └────────────┬──────────────┘
                           │
                           ▼
              ┌───────────────────────────┐
              │ Statistical Analysis      │
              │                           │
              │ • Feature comparison      │
              │ • Correlation analysis    │
              │ • Statistical testing     │
              └────────────┬──────────────┘
                           │
                           ▼
              ┌───────────────────────────┐
              │ Cultural Differentiation  │
              │ & Model Comparison        │
              └───────────────────────────┘
```

## 🤖 LLM & Persona-Based Conversation Generation

A central component of this research is the generation of conversations using **persona-based prompts** designed to represent different cultural contexts, interpersonal relationships, and conversational conditions.

The repository includes Python code for generating these persona-based conversations, this should be run via the command line on a server, as the models used have up to 14B parameters.


## 🌍 Cultural Comparison

The research includes comparisons between:

🇬🇧 UK cultural conditions

and

🇮🇷 Iranian cultural conditions

The repository contains separate analyses and datasets for the two cultural conditions, including significant linguistic features and statistical outputs.

## 👥 Conversational Personas

The research investigates different persona relationships and conversational conditions.

Examples represented in the analysis include:

Father ↔ Daughter
Father ↔ Son
Mother ↔ Daughter
Mother ↔ Son
Daughter ↔ Father
Daughter ↔ Mother
Son ↔ Father
Son ↔ Mother

The research also includes different conversational stances such as:

Agreement
Disagreement
Neutral interactions

This allows the study to investigate whether linguistic behaviour changes depending on both cultural context and interaction/persona conditions.

## 🧠 Natural Language Processing

The generated conversations are analysed using linguistic feature extraction techniques.

LIWC

The project uses LIWC-based linguistic analysis to examine language patterns within the generated conversations.
The project also includes ELFeN-based analysis.
These analyses provide additional linguistic information for evaluating differences in generated language.

## 📊 Statistical Analysis

A major part of the project is the statistical analysis of the generated language.

The repository contains statistical outputs and significant-feature analyses for

The objective is to identify linguistic features that show meaningful differences across experimental conditions.

## 🔎 Significant Feature Analysis

The repository contains multiple datasets identifying statistically significant linguistic features.

Examples include:
```text

Significant_Features_Comparison_UK_vs_Iran.csv

Significant_Features_Iran.csv

Significant_Features_agreement_UK.csv

Significant_Features_disagreement_UK.csv

Significant_Features_Mother_and_Daughter_UK.csv

Significant_Features_Father_and_Son_Iran.csv
```

These datasets support detailed investigation of which linguistic characteristics differ between cultural and conversational conditions.

🧪 Model-Specific Analysis

The repository includes dedicated analysis of Llama 8B, including:
```text
Model-level analysis
Generation-level analysis
Temperature-related analysis
LIWC analysis
Significant-feature analysis
```
This allows the research to investigate not only cultural differences, but also how generated outputs behave under different model-related conditions.

## 🛠️ Technologies & Methods
```text
Programming
Python
Jupyter Notebooks
Pandas
NumPy
Artificial Intelligence
Large Language Models (LLMs)
Persona-based prompting- prompting engineering
LLM conversation generation
LLM evaluation
Natural Language Processing (NLP)
LIWC
ELFeN
Linguistic feature extraction
Text analysis
Data Science & Statistics
Data preprocessing
Exploratory analysis
Statistical testing
Correlation analysis
Feature analysis
Significant-feature identification
Cross-cultural comparison
```
## 📈 Research Outputs

The repository contains a substantial collection of:

Generated conversation datasets
Processed datasets
Linguistic feature datasets
LIWC statistical outputs
ELFeN statistical outputs
Significant-feature comparisons
UK/Iran cultural comparisons
Persona-specific analyses
Llama 8B analyses

This makes the repository both a research archive and a reproducible analysis resource for the dissertation.

## 💡 Why This Research Matters

As LLMs become increasingly integrated into conversational systems, understanding how they represent different cultural contexts is important.

A chatbot may interact with users from very different cultural backgrounds.

If an LLM generates essentially the same conversational behaviour regardless of cultural context, this raises questions about:

Cultural representation
Cultural adaptation
AI bias
Inclusivity
Human-AI interaction
Responsible AI

This research therefore investigates whether measurable linguistic differences emerge when LLMs operate under different cultural and persona conditions.

🔍 Key Research Areas

This project sits at the intersection of:
```text

          Artificial Intelligence
                  │
                  ▼
        Large Language Models
                  │
                  ▼
       Natural Language Processing
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
   Linguistic          Cultural AI
    Analysis           & Adaptation
        │                   │
        └─────────┬─────────┘
                  ▼
          Responsible AI
```
## 📚 Academic Context

The work focuses on the evaluation of LLM-generated language for building a chatbot applications.

The project therefore combines:

LLM experimentation + NLP + statistical analysis + cultural comparison

to investigate the behaviour of AI-generated conversations.

## 👩‍💻 Researcher
Zeinab Dast Mozd

MSc Artificial Intelligence | AI & Machine Learning Engineer

Research Interests
Large Language Models
Natural Language Processing
AI Evaluation
Cultural AI
Machine Learning
Statistical Analysis
Human-AI Interaction
Responsible AI

## ⚠️ Research & Data Disclaimer

This repository is provided for academic and research purposes.

The generated conversations and analysis outputs should not be interpreted as representing the behaviour, beliefs, or characteristics of real individuals or entire cultures.

The findings should be understood within the experimental design and limitations of the research.

## 📌 Project Status

Research Project / Dissertation

The repository contains the research code, datasets, notebooks and analysis outputs associated with the study.

## ⭐ If You Find This Research Useful

Feel free to explore the notebooks, datasets and analysis files in this repository.

For questions or research collaboration, please connect with me on LinkedIn.

