# Task 4: General Health Query Chatbot

## Objective
Build a health chatbot using prompt engineering with an LLM.

## Dataset
No training dataset used — prompt engineering based approach.

## Tools Used
- LLaMA 3.3 70B via Groq API (free)
- Two-layer safety filter system

## Models Applied
LLaMA 3.3-70b-versatile via Groq API

## Key Results & Findings
- System prompt fully controls LLM tone and behavior
- Two-layer safety: rule-based filter + LLM system prompt
- Multi-turn conversation memory implemented successfully
- Same LLM gives completely different responses with different prompts
- Temperature 0.7 gave balanced natural responses