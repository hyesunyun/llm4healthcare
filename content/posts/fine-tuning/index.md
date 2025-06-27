---
title: "Part 4: Building an AI Medical Information Extractor Agent | Fine-tuning LLM"
author: "Hye Sun Yun"
date: "2025-06-25"
summary: "Process of adapting LLMs for medical information extraction tasks"
description: "Process of adapting LLMs for medical information extraction tasks"
toc: true
readTime: false
autonumber: true
math: true
tags: ["fine-tuning", "code"]
showTags: false
hideBackToTop: false
---

# Advanced Techniques: Fine-Tuning for Medical Data Extraction

## Learning Objectives
- Understand when and why to fine-tune vs. prompt engineering
- Implement fine-tuning for medical named entity recognition
- Work with medical literature datasets
- Evaluate model performance on healthcare tasks

## Fine-Tuning vs. Prompting - When to Use Each?

- Computational requirements and costs
- Data requirements (how much annotated data do you need?)
- Performance considerations
- Maintenance and updates

## Medical Named Entity Recognition Project

**Dataset Introduction:**
- Using a subset of PubMed abstracts
- Annotation schemes: drug names, diseases, treatments, dosages
- Data preprocessing for medical text

### Interactive Element

**Python Code:**
- Base code and step-by-step instructions will be given to students
- Students fine-tune a model on a specific medical extraction task and compare performance with baseline models.

## Advanced Data Extraction Tasks

Briefly share other types of data extraction tasks that are commmonly done in healthcare applications:
- Relationship extraction (drug-disease interactions)
- Extracting clinical trial outcomes
- Identifying contradictory information across papers
- Temporal information extraction (treatment timelines)

## Key Considerations for Evaluation and Deployment

- Evaluation metrics/framework
- Error analysis in healthcare contexts
- Deployment considerations (speed, accuracy, scalability)
- Continuous learning and model updates
- User Trust
