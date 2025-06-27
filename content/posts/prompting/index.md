---
title: "Part 3: Medical Question Answering with AI Agent | Prompting LLM"
author: "Hye Sun Yun"
date: "2025-06-25"
summary: "Techniques to refine and test prompts for improved performance on medical question answering"
description: "Techniques to refine and test prompts for improved performance on medical question answering"
toc: true
readTime: false
autonumber: true
math: true
tags: ["prompting", "code"]
showTags: false
---

# Your First Healthcare AI Assistant: Hands-On Prompting

## Learning Objectives

- Practice prompt engineering for healthcare applications
- Build a functional healthcare Q&A system
- Understand the importance of prompt validation and testing
- Learn to implement safety guardrails

## Prompt Engineering for Healthcare

- The anatomy of a good prompt
- Techniques: few-shot learning, chain-of-thought, role-playing
- Healthcare-specific considerations: requesting sources, acknowledging uncertainty
- Examples of effective prompts for different tasks

## Building the Healthcare Q&A Assistant

- Using HuggingFace LLM with system and user prompts
- Test assistant with various types of questions and refine prompts based on results
- Extend the assistant to handle a specific medical domain of choice (e.g., diabetes management, mental health basics) 
- Base code will be provided in Jupyter notebook or Google Colab

### Key Features to Implement
- Input validation (filtering inappropriate medical questions)
- Disclaimer generation ("This is not medical advice...")

### Testing and Validation

- Creating test cases for medical Q&A
- Measuring usefulness vs. safety trade-offs
- User testing with non-medical students
- Iterative improvement based on feedback

### Safety Guardrails

- Implementing content filters
- Recognizing when to refuse to answer
- Proper medical disclaimers
- Escalation protocols
