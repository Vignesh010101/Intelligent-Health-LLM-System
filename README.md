# An Intelligent Health LLM System for Personalized Medication Guidance and Support

## Abstract

Technology integration for personalized treatment plans involves multi-faceted approaches. One of the key areas of focus is to extract information on patient care using the latest Artificial Intelligence (AI) and Large Language Models (LLM) that might not be apparent with traditional methods. For example, using multiple medications often poses problems for users, and it is not easy to interpret the drug interactions or overlapping components that carry a potential risk.

Many AI-driven medical support systems are in place nowadays, and the current study uses pretrained and fine-tuned LLMs, specifically optimized for medical and pharmaceutical tasks. The study used models such as ChatGPT-3, ChatGPT-3 Turbo, LLaMA 3.2 11B Vision, Meditron-7B, and Mistral. Out of the different models used, Meditron-7B showed the highest accuracy of **95.7%** after fine-tuning the models with health-related datasets. Using **Evallms**, the system demonstrated a performance score **18.57%** higher than existing models like Med-PaLM and ChatGPT’s healthcare APIs.

Integrating online pre-trained models helps the system grow and expand alongside the evolution of AI and medical knowledge. The system remains responsive to individual user needs by processing data from multi-modal electronic records such as text, PDFs, scans, and voice notes. It categorizes user queries and leverages user profiles and memory (historical records) for personalized assessments. The system performs actions like **data analysis, medication guidance, and precautionary alerts**, ultimately providing outputs such as medical guides, tailored suggestions, and detailed explanations to enhance healthcare delivery and ensure medication safety. This approach bridges the critical gap in personalized healthcare, driving the future of **AI-powered medical support systems** accessible through handheld mobile devices.

---

## Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
- [Models Used](#models-used)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation & Performance](#evaluation--performance)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Introduction
The **Intelligent Health LLM System** leverages state-of-the-art **Large Language Models (LLMs)** to provide **personalized medication guidance and support**. By integrating **text, PDFs, scans, and voice-based inputs**, the system ensures a holistic approach to **medication safety, drug interaction analysis, and personalized healthcare insights**.

---

## Key Features
- **Multi-Modal Data Processing**: Accepts text, PDFs, medical images, and voice inputs.
- **AI-Driven Medication Guidance**: Identifies potential drug interactions and provides safe usage recommendations.
- **Personalized Assessments**: Adapts based on patient history and health records.
- **Fine-Tuned Medical LLMs**: Optimized models for pharmaceutical and clinical tasks.
- **High Accuracy (95.7%)**: Outperforms existing AI-driven medical models.
- **Multi-Model Integration**: Uses Evallms, and other top current LLM's for evaluation and scoring.

---

## Models Used
- **ChatGPT-3** & **ChatGPT-3 Turbo** (for general medical Q&A)
- **LLaMA 3.1 8B** (for general text responses)
- **LLaMA 3.2 11B Vision** (for image-based diagnosis)
- **Meditron-7B** (highest accuracy model for medical NLP tasks)
- **Mistral** (for efficient real-time responses)
- **OpenAI Whisper** (for real-time voice text conversion)
- **EvalLM & GPT-4o** (benchmark for performance comparison and accuracy)

---

## System Architecture
*(Add a system diagram or flowchart if required)*

---

## Installation
```bash
# Clone the repository
git clone https://github.com/Vignesh010101/Intelligent-Health-LLM.git
cd Intelligent-Health-LLM
```

---

## Usage
*(Provide detailed instructions on how to use the system, run inference, or interact with the models)*

---

## Evaluation & Performance
- **Fine-Tuned Model Accuracy**: 95.7%
- **Performance Gain over other existing top LLM models**: +18.57%
- **Response Time Optimization**: Efficient real-time response with Meditron, LLaMA 3.2 Vision, Gemma 2, Mistral and even GPT models.

*(Include graphs or evaluation metrics if required)*

---

## Fine-tuned Models 
- [LLaMA 3.2 11B Vision Instruct Finetuned (GGUF)](https://huggingface.co/Sci-fi-vy/Llama-3.2-11B-Vision-Instruct-GGUF)
- [LLaMA 3.2 11B Vision Instruct Finetuned](https://huggingface.co/Sci-fi-vy/Llama-3.2-11B-Vision-Instruct-finetuned)
- [Meta-Llama-3.1-8B-finetuned](https://huggingface.co/Sci-fi-vy/Meta-Llama-3.1-8B-finetuned)
- [gemma-2-9b-it Finetuned (GGUF)](https://huggingface.co/Sci-fi-vy/gemma-2-9b-it-GGUF)
- [gemma-2-9b-it-finetuned](https://huggingface.co/Sci-fi-vy/gemma-2-9b-it-finetuned)
- [Meditron-7b-finetuned](https://huggingface.co/Sci-fi-vy/Meditron-7b-finetuned)
- [Mistral-7B-Instruct-v0.3-finetuned](https://huggingface.co/Sci-fi-vy/Mistral-7B-Instruct-v0.3-finetuned)

## Future Enhancements
- **More Models getting Fine-tuned**
- **Mobile App Integration (Coming-soon)**
- **Expanded Drug Interaction Database**
- **Enhanced Patient Data Privacy Mechanisms**

---

## License
**(Apache License)**

---


