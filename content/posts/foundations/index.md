---
title: "Part 1: Foundations of LLMs and Healthcare AI"
author: "Hye Sun Yun"
date: "2025-06-25"
summary: "LLM basics and exploring common healthcare tasks and datasets"
description: "LLM basics and exploring common healthcare tasks and datasets"
toc: true
readTime: false
autonumber: true
math: true
tags: ["foundations", "basics"]
showTags: false
hideBackToTop: false
---

# LLMs Meet Healthcare: Understanding the Fundamentals

## Learning Objectives

- Understand what LLMs are and how they work at a high level
- Explore common healthcare applications for LLMs
- Survey key healthcare datasets and their characteristics
- Identify unique challenges in healthcare AI

## LLM Basics

**Large language models (LLMs)** are language models trained with self-supervised machine learning on a vast amount of text, designed for natural language processing tasks, especially language generation. They are deep neural networks that are millions or billions of gigabytes in size and trained on enormous amounts of text data.

LLMs have shown to be very powerful in various natural language tasks including generating summaries, answering questions, or completing text based on a given prompt.

Example Prompts:\
`"Please use the following job description and my resume to write a letter."`\
`"Two American citizens leave the Irish pub sober. Continue the joke, please."`\
`"What is the evidence for inhaled bronchodilators for acute chest syndrome in people with sickle cell disease?"`

The LLM will output some text based on the input. You can think of them as models that can complete text.

**TODO: add autoregressive, n-grams, probabilities, tokenizers**

### What Are Transformers?

Transformers are a type of model that excel at processing sequences of data, such as sentences in a text. This archiecture was introduced by Google researchers in 2017 at NeurIPS conference in their landmark paper named ["Attention Is All You Need."](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)[^1] 

Transformers differ from earlier models like Recurrent Neural Networks (RNNs) or Long Short-Term Memory networks (LSTMs) by processing all elements of the sequence simultaneously, rather than one by one. This parallel processing is enabled by the attention mechanism, which helps the model focus on the most relevant parts of the sequence at each step.

**TODO: a bit more about attention mechanisms?**

Some examples of well-known Transformer-based LLMs are `GPT-4`, `Claude 4 Sonnet`, `Llama`, and `Mistral`. 

### Challenges in NLP for Healthcare

However, these general LLMs mentioned above often lack the specialized knowledge or abilities that are required for health and medical-specific tasks.

NLP tasks for healthcare are different from general NLP tasks for the following reasons:
- Medical jargon
- Requires precision and accuracy
- High risk setting
- Requires clinical/healthcare expert input and feedback

Due to these challenges, researchers and developers have pre-trained or fine-tuned LLMs on biomedical text (clinical notes, medical research articles, etc) to create medical-specific LLMs.

However, there have been several LLMs fine-tuned on biomedical text that were created  `BioBERT`, ClinicalBERT

- What are LLMs? (Transformer architecture simplified)
- How healthcare is different from general NLP tasks
    - Medical jargon
    - Requires precision and accuracy
    - High risk setting
    - Requires clinical/healthcare expert input and feedback

## Healthcare Tasks That LLMs Excel

LLMs can provide value in healthcare by increasing quality but decreasing cost to ensure better patient and care team experience. Specifically, LLMs can reduce healthcare's administrative burden. This allows clinicians time to actually do healthcare rather than administrative work.

Examples:
- Clinical note summarization
- Medical literature review and synthesis
- Patient education material generation
- Drug interaction checking
- Symptom assessment (with major caveats)
- Medical coding assistance (ICD-10, CPT codes)

## Healthcare Datasets

- **MIMIC-III/IV:** ICU patient de-identified data
- **PubMed:** Medical literature abstracts
- **Clinical trial data:** ClinicalTrials.gov
- **Medical imaging datasets:** CheXpert Plus, NIH Chest X-Rays, Cancer Imaging Dataset
- **Synthetic datasets:** They can be used when real patient data is unavailable or to fill in the missing gap

### Excercise!

*An exercise where students explore a sample from each dataset type, noting differences in structure, language, and complexity.*

[^1]: You can find more details on Transformers and this paper via blog posts: [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) and [Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/)
