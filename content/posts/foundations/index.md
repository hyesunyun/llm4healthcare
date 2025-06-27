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
---

# LLMs Meet Healthcare: Understanding the Fundamentals

## Learning Objectives

- Understand what LLMs are and how they work at a high level
- Explore common healthcare applications for LLMs
- Survey key healthcare datasets and their characteristics
- Identify unique challenges in healthcare AI

## LLM Basics for Healthcare

- What are LLMs? (Transformer architecture simplified)
- Key capabilities: text generation, question answering, summarization
- Popular models: GPT-4, Claude, Llama, BioBERT, ClinicalBERT
- How healthcare is different from general NLP tasks
    - Medical jargon
    - Requires precision and accuracy
    - High risk setting
    - Requires clinical/healthcare expert input and feedback

## Healthcare Tasks Where LLMs Excel

LLMs can provide value in healthcare by increasing quality but decreasing cost to ensure better patient and care team experience. Specifically, LLMs can reduce healthcare's administrative burden. This allows clinicians time to actually do healthcare rather than administrative work.

Examples:
- Clinical note summarization
- Medical literature review and synthesis
- Patient education material generation
- Drug interaction checking
- Symptom assessment (with major caveats)
- Medical coding assistance (ICD-10, CPT codes)

## Healthcare Datasets Deep Dive

- **MIMIC-III/IV:** ICU patient de-identified data
- **PubMed:** Medical literature abstracts
- **Clinical trial data:** ClinicalTrials.gov
- **Medical imaging datasets:** CheXpert Plus, NIH Chest X-Rays, Cancer Imaging Dataset
- **Synthetic datasets:** They can be used when real patient data is unavailable or to fill in the missing gap

### Interactive Element

*An exercise where students explore a sample from each dataset type, noting differences in structure, language, and complexity.*
