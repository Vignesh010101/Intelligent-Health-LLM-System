# An Intelligent Health LLM System for Personalized Medication Guidance and Support

## Abstract

Technology integration for personalized treatment plans involves multi-faceted approaches. One of the key areas of focus is to extract information on patient care using the latest Artificial Intelligence (AI) and Large Language Models (LLM) that might not be apparent with traditional methods. For example, using multiple medications often poses problems for users, and it is not easy to interpret the drug interactions or overlapping components that carry a potential risk.

Many AI-driven medical support systems are in place nowadays, and the current study uses pretrained and fine-tuned LLMs, specifically optimized for medical and pharmaceutical tasks. The study used models such as ChatGPT-3, ChatGPT-3.5 Turbo, LLaMA 3.1 8B, LLaMA 3.2 11B Vision, Meditron-7B, and Mistral-7B. Out of the different models used, Meditron-7B showed the highest accuracy of **95.7%** after fine-tuning the models with health-related datasets. Using **EvalLM**, the system demonstrated a performance score **18.57%** higher than existing models like Med-PaLM and ChatGPT’s healthcare APIs.

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
- [Fine-tuned Models](#fine-tuned-models)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Introduction

The rapid increase in polypharmacy highlights the need for intelligent tools to safely manage multiple medications, especially for chronic patients who face an increased risk of drug interactions. Patients often receive prescriptions from different doctors, leading to confusion, non-compliance, and potential medication errors. The complexities of drug interactions, varied medication schedules, and lack of knowledge about prescription components contribute to these challenges.

Traditionally, healthcare technology focused on digitizing medical records and improving diagnostic accuracy. Electronic Health Records (EHRs) revolutionized patient data management, while advancements in diagnostic imaging, such as MRI and CT scans, enhanced disease detection. However, many existing healthcare platforms provide only general information and fail to offer personalized, real-time advice, particularly for managing complex medication regimens.

In recent years, Artificial Intelligence (AI) and Machine Learning (ML) have transformed healthcare. AI-powered platforms like Med-PaLM and ChatGPT APIs have improved patient query responses and medical knowledge distribution. However, these systems often lack personalization, real-time adaptability, and multimodal input capabilities, limiting their effectiveness in intricate patient scenarios.

Our approach aims to deliver personalized health advice while minimizing medication risks. By leveraging multiple Large Language Models (LLMs), including ChatGPT-3, ChatGPT-3.5 Turbo, LLaMA-3.1-8B, LLaMA-3.2-11B-Vision, Meditron-7B, and Mistral-7B, we enable deep learning-based interpretation of multimodal inputs and generate human-like responses. The system processes vast amounts of medical data, extracts contextual insights, and delivers highly accurate, personalized healthcare recommendations.

### Key Contributions:
- **Multimodal Input Support**: Accepts text, PDFs, scanned documents, and voice inputs for comprehensive healthcare guidance.
- **Fine-Tuned Medical LLMs**: Uses advanced language models trained on medical datasets to detect medication interactions and provide precise recommendations.
- **Real-Time Adaptability**: Continuously updates with the latest medical guidelines and user data to ensure accurate, context-aware healthcare assistance.

This intelligent Health LLM System bridges the gap between AI-driven healthcare solutions and real-world patient needs. It enhances accessibility, ensures patient safety, and delivers trusted medical insights, empowering individuals to manage their health more effectively.


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

## Datasets Used
- [**A to Z Medicines**](https://www.kaggle.com/datasets/shudhanshusingh/az-medicine-dataset-of-india)
- [**250k Medicines Usage, Side Effects and Substitutes**](https://www.kaggle.com/datasets/shudhanshusingh/250k-medicines-usage-side-effects-and-substitutes)
- [**MIMIC-IV**](https://github.com/MIT-LCP/mimic-code/tree/main/mimic-iv)
- [**MIMIC-IV-ED**](https://github.com/MIT-LCP/mimic-code/tree/main/mimic-iv-ed)
- [**MIMIC-IV-on-FHIR**](https://physionet.org/content/mimic-iv-ext-cdm/1.1/)
- [**MIMIC-IV-Ext-BHC**](https://physionet.org/content/labelled-notes-hospital-course/1.1.0/)
- [**MIMIC-CXR**](https://opendatalab.com/OpenDataLab/MIMIC-CXR)

---

## System Architecture
![IMG_0465](https://github.com/user-attachments/assets/a09b61dd-fe2a-45d0-82ed-5a2b910f41d5)

![IMG_0466](https://github.com/user-attachments/assets/e902c896-51ee-4b73-a7a9-1c90e713c681)


---


## Installation
```bash
# Clone the repository
git clone https://github.com/Vignesh010101/Intelligent-Health-LLM.git
cd Intelligent-Health-LLM
```

---

## Usage
- Run the [**Model Inference**](https://github.com/Vignesh010101/Intelligent-Health-LLM-System/blob/main/Direct_My_HF_Model_infrncs.ipynb) file to infer the **Intelligent Health LLM System** directly from my fine-tuned model which are uploaded on HuggingFace platform.
- Run the [**MultiModal-Input-Output**](https://github.com/Vignesh010101/Intelligent-Health-LLM-System/blob/main/Multi_Modal_input_checking_by_Vignesh1.ipynb) file to directly ask queries and you can also upload images & documents and get the responses.


---

## Evaluation & Performance
- **Fine-Tuned Model Accuracy**: 95.7%
- **Performance Gain over other existing top LLM models**: +18.57%
- **Response Time Optimization**: Efficient real-time response with Meditron, LLaMA 3.2 Vision, Mistral and even GPT models.

<!-- Include graphs or evaluation metrics if required) -->

---


## Fine-tuned Models
- [LLaMA 3.2 11B Vision Instruct Finetuned (GGUF)](https://huggingface.co/Sci-fi-vy/Llama-3.2-11B-Vision-Instruct-GGUF)
- [LLaMA 3.2 11B Vision Instruct Finetuned](https://huggingface.co/Sci-fi-vy/Llama-3.2-11B-Vision-Instruct-finetuned)
- [Meta-Llama-3.1-8B-finetuned](https://huggingface.co/Sci-fi-vy/Meta-Llama-3.1-8B-finetuned)
- [Meditron-7b-finetuned](https://huggingface.co/Sci-fi-vy/Meditron-7b-finetuned)
- [Mistral-7B-Instruct-v0.3-finetuned](https://huggingface.co/Sci-fi-vy/Mistral-7B-Instruct-v0.3-finetuned)


---


## Future Enhancements
- **More Models getting Fine-tuned on Medical Data**
- **Mobile App Integration (Coming-soon)**
- **Expanded Drug Interaction Database**
- **Enhanced Patient Data Privacy Mechanisms**

---

## License
**Apache License**

---


