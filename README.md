# Medi2Mind – AI-Powered Medical Diagnosis Assistant

**Medi2Mind** is a hybrid AI medical assistant that combines **multimodal medical image analysis Using Agentic AI** with a **Mixture of Experts (MoE)**-based large language model to simulate real-time consultations across five medical domains: Mental Health, Radiology, General Consultation, Veterinary Medicine, and Medical Imaging.

## Project Objective

To build an intelligent, scalable system that:
- Analyzes medical queries and CT/MRI/X-ray images via specialized expert agents.
- Routes queries to domain-specific experts using a dynamic keyword-scoring engine.
- Generates accurate, contextual, and patient-friendly responses.
- Handles high concurrency and cross-domain healthcare scenarios efficiently.

## Tech Stack

- **Languages & Frameworks:** Python, PyTorch, Transformers, CUDA  
- **UI/Frontend:** Gradio  
- **Vision/Image Analysis:** OpenCV, PIL  
- **Agentic Capabilities:** Agno Agents (File Upload, Vision, OCR, Prompt Enrichment, LLM Reasoning)  
- **Deployment:** Google Cloud Platform  
- **Model Backbone:** `deepseek-ai/deepseek-llm-7b-base`

---

## Results

| Module             | Routing Accuracy | Domain Knowledge Accuracy | Response Relevance | Diagnostic Accuracy | Inference Time (s) |
|--------------------|------------------|----------------------------|---------------------|---------------------|--------------------|
| Mental Health      | 94%              | 91%                        | 87%                 | –                   | 1.21               |
| Radiology          | 89%              | 94%                        | 92%                 | –                   | 1.35               |
| General Consultation | 85%            | 88%                        | 90%                 | –                   | 1.18               |
| Veterinary Medicine| 91%              | 89%                        | 85%                 | –                   | 1.25               |
| Image Analysis     | 92%              | 95%                        | 89%                 | **95%**             | 2.34               |

> System handled **100 concurrent queries with 97% success rate**.

---

## Key Achievements

- Designed a **modular expert-routing engine** with 91% average accuracy using keyword probability scoring.
- Implemented **Agentic AI pipeline** to interpret CT/MRI/X-ray scans with 95% diagnostic precision.
- Delivered real-time consultation and second-opinion capabilities for both patients and professionals.
- Validated system across unit, integration, and system testing with high performance under load.

---

> *Medi2Mind aims to democratize access to reliable medical advice using scalable, AI-powered healthcare solutions.*

