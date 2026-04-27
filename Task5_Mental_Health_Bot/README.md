# Task 5: Mental Health Support Chatbot (Fine-Tuned)

## Objective
Fine-tune a small LLM to produce empathetic mental health responses.

## Dataset
- **Name:** EmpatheticDialogues (Estwld/empathetic_dialogues_llm)
- **Source:** Hugging Face Hub
- **Size:** 5,000 training samples used (24,850 total)

## Models Applied
- **Base Model:** DistilGPT2 (82M parameters)
- **Fine-tuning:** Hugging Face Trainer API
- **Interface:** Streamlit web app

## Key Results & Findings
- Training loss decreased consistently over 3 epochs
- Fine-tuned model produces warmer more empathetic responses
- Base vs fine-tuned comparison proved domain adaptation works
- Streamlit interface deployed successfully via Cloudflare tunnel
- Even small models show clear improvement after domain fine-tuning