# AI Safety & Security Evaluation Harness

A lightweight evaluation harness for testing LLM responses against prompt injection, data leakage, unsafe compliance, and safety-risk scenarios.

## Overview

This project explores how language models respond to security-sensitive prompts, including prompt injection, data leakage, unsafe compliance, and overconfident answers.

As AI systems become part of critical infrastructure, safety is not only a research problem; it is also an engineering and security problem. This project reflects my interest in evaluating whether AI systems remain reliable, harmless, and honest under adversarial or ambiguous conditions.

## Why this matters

My background is in cloud security, identity governance, infrastructure automation, and operational risk reduction. In production cloud environments, small configuration mistakes can create serious downstream consequences. I am interested in applying that same security and systems-thinking mindset to AI safety.

This project is a small self-directed experiment focused on one question:

> How can we evaluate whether an AI system behaves safely when users ask ambiguous, adversarial, or high-risk questions?

## What this project does

- Defines a small set of security and safety test prompts
- Categorizes risks such as prompt injection, data leakage, unsafe compliance, and hallucination
- Scores model responses using a simple risk rubric
- Produces a short written analysis of observed behavior

## Research areas connected to this project

- AI Security
- Adversarial Robustness
- AI Control
- Scalable Oversight
- Evaluation Design
- Responsible AI Deployment

## Project structure

```text
ai-safety-security-evals/
├── README.md
├── requirements.txt
├── evals/
│   └── prompts.json
├── src/
│   └── evaluate.py
└── results/
    └── sample_results.md
