---
title: "Part 2: Ethics, Limitations, and Data Handling"
author: "Hye Sun Yun"
date: "2025-06-25"
summary: "Patient privacy requirements, bias/fairness issues, and AI limitations in healthcare"
description: "Patient privacy requirements, bias/fairness issues, and AI limitations in healthcare"
toc: true
readTime: false
autonumber: true
math: true
tags: ["ethics", "limitations", "privacy", "data", "code", "bias", "fairness"]
showTags: false
hideBackToTop: false
---

# The Double-Edged Sword: Ethics, Limitations, and Data Handling

## Learning Objectives

- Understand HIPAA and patient privacy requirements
- Recognize bias and fairness issues in healthcare AI
- Learn data de-identification techniques
- Develop critical thinking about AI limitations in healthcare

## Data Privacy

- HIPAA basics for AI developers
- De-identification techniques
    - safe harbor method
    - expert determination
- Synthetic data generation as an alternative

### Interactive Element

*Implement a simple data de-identification script for a sample clinical dataset. This will involve giving students some basic code and data and some instructions to follow.*

## Bias and Fairness

- Historical bias in medical research (lack of diversity in clinical trials)
    - "Of all forms of inequality, injustice in healthcare is the most shocking and inhumane" - Martin Luther King Jr.
- How bias gets encoded in datasets and models
- Need to ensure that all stakeholders benefit from LLMs
- Case study: ["Dissecting racial bias in an algorithm used to manage the health of populations"](https://www.science.org/doi/10.1126/science.aax2342) by Obermeyer et al., 2019
- Mitigation strategies: diverse datasets, fairness metrics, regular auditing

## Limitations and Failure Modes

- Hallucination in medical contexts (extremely dangerous)
- Overconfidence in AI predictions
- The "black box" problem in healthcare decisions
- Difficulty of translating AI to healthcare
    - [80% of AI projects in healthcare fail.](https://www.healthdatamanagement.com/articles/ai-in-healthcare-breaking-the-hype-cycle-and-avoiding-the-80-failure-trap)
    - "The impressive barriers to translation of AI to healthcare practice may result in no change to the practice of medicine in 5 years." - Eric Horowitz
- When NOT to use AI: life-critical decisions, rare conditions

### Interactive Element

*Students analyze a case study of an AI healthcare failure and identify what went wrong and how it could have been prevented.*

## Responsible Data Handling

- Data storage and encryption
- Access controls
- IRB approval
- International regulations (GDPR)
