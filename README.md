Você pode usar algo assim no **README.md** do GitHub:

# FocusTimer AI Specialist - NotebookLM Challenge

This project was developed as part of an AI Assistant challenge using Google NotebookLM.

## Overview

FocusTimer is a fictional productivity platform based on the Pomodoro Technique. The objective of this project is to create a specialized AI assistant capable of answering user questions exclusively from the product documentation, ensuring accuracy, transparency, and reliability.

The repository contains two PDF documents:

* **FocusTimer Product Documentation** – Defines the product features, business rules, plans, limitations, and usage guidelines.
* **FocusTimer AI Assistant Prompt** – Defines the assistant's behavior, personality, response strategy, and prompt engineering techniques.

## Assistant Characteristics

The assistant was designed to act as:

* **Product Specialist** – Expert on the FocusTimer platform.
* **Communicator** – Provides clear explanations and practical examples.
* **Integrity-Driven** – Answers only based on documented information.
* **Transparent** – Explicitly acknowledges when information is not available in the documentation.

## Prompt Engineering Techniques

The assistant incorporates multiple prompt engineering techniques:

* **Zero-Shot Prompting**
* **Few-Shot Prompting**
* **Chain of Thought (Internal Reasoning)**

These techniques help improve consistency, accuracy, and reduce hallucinations.

## Expected Behavior

When a question can be answered using the documentation, the assistant provides a clear and objective explanation.

When the requested information is outside the documented scope, the assistant responds with:

> "A informação solicitada não está presente na documentação oficial do FocusTimer. Para esclarecimentos adicionais, entre em contato com a equipe de desenvolvimento pelo e-mail [exemplo@exemplo.com](mailto:exemplo@exemplo.com)."

## Repository Structure

```text
/
├── FocusTimer_Product_Documentation.pdf
└── FocusTimer_Assistant_Prompt.pdf
```

## Goal

Demonstrate how a reliable AI assistant can be built using NotebookLM by combining:

* Well-structured product documentation
* Clear behavioral instructions
* Prompt engineering best practices
* Controlled knowledge boundaries

This project focuses on creating a trustworthy assistant that prioritizes factual accuracy over speculation.
