# Virtual Teaching Assistant with RAG

This project provides a tutorial on building a Virtual Teaching Assistant using Retrieval-Augmented Generation (RAG) with a quantized Mistral 7B model. The implementation uses Google Colab for model loading and fine-tuning, and Gradio for deployment as a chat interface. This is strictly for educational purposes.

## Features
- **Quantization**: Utilizes `bitsandbytes` to load Mistral 7B efficiently into Colab's T4 GPU RAM.
- **Retrieval-Augmented Generation (RAG)**: Enhances responses with domain-specific knowledge from two key resources.
- **Prompt Optimization & Guardrails**: Uses `langchain` to refine prompts and enforce necessary safeguards.
- **Gradio UI Deployment**: A simple interactive chat interface for easy access to the model.

---
## Data Sources
This RAG implementation retrieves content from the following:

1) **MIT Open Courseware** – *Introduction to C++ Lecture Notes* (January IAP 2011, Undergraduate)
   - Instructors: Jesse Dunietz, Geza Kovacs, John Marrero
2) **Beginning C++ Programming** – Richard Grimes (2017, Packt Publishing)

> **Note:** All credits belong to the rightful owners. The retrieval mechanism is not meant for large-scale deployment due to lack of explicit consent from the authors.
> 
> **Additional Reference:** The notebooks take inspiration from [this Medium article](https://medium.com/@thakermadhav/build-your-own-rag-with-mistral-7b-and-langchain-97d0c92fa146) by Madhav Thaker, which may be useful for further insights and adaptations to your specific use case.

