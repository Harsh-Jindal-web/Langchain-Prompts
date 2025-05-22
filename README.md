# LangChain-Prompts

This repository offers an interactive and practical guide to using **Prompts in LangChain**, a crucial aspect of building intelligent conversational and generative AI systems. It includes code modules, prompt utilities, a UI interface, and summarized notes for deeper understanding.

## 🧠 Overview

Prompts in LangChain define **how information is sent** to language models. Crafting the right prompt is essential for maximizing model accuracy, relevance, and creativity.

This project explores:

1. **Prompt Templates** – Creating reusable prompt structures with placeholders.
2. **Chat Prompt Templates** – Structuring role-based message sequences for chat models.
3. **Dynamic Prompt Generation** – Building custom prompts programmatically.
4. **Temperature and Sampling** – Controlling randomness and output diversity.

For a structured summary, check out [**Notes Prompts in LangChain.pdf**](./Notes%20Prompts%20in%20LangChain.pdf).

Video walkthrough available here:  
- [📺 Prompts in LangChain (YouTube)](https://www.youtube.com/watch?v=3TGqlQxpuU0&list=PLKnIA16_RmvaTbihpo4MtzVm4XOQa0ER0&index=6)

## 📂 Repository Structure

- `chatbot.py` – Main script for running a chatbot with LangChain prompts.
- `prompt_template.py` – Create and render basic prompt templates.
- `chat_prompt_template.py` – Work with LangChain's chat-specific prompt structure.
- `messages.py` – Constructs user/system/assistant messages.
- `message_placeholder.py` – Supports dynamic insertion of messages.
- `temperature.py` – Adjusts temperature settings to control model creativity.
- `prompt_generator.py` – Utility to generate prompts from config files or input.
- `prompt_ui.py` – Provides a UI for interacting with prompt components.
- `template.json` – Stores pre-defined templates for structured prompting.
- `chat_history.txt` – Maintains the conversation history for continuity.
- `Notes Prompts in LangChain.pdf` – Summarized notes for reference.

## 📄 Resources

- **LangChain Documentation – Prompt Templates**  
  [https://python.langchain.com/docs/how_to/#prompt-templates](https://python.langchain.com/docs/how_to/#prompt-templates)
  
---

Feel free to explore, contribute, or open issues to improve or expand this guide.

---
