# Evaluating the Reliability and Safety of ChatGPT Responses to Public Health and Microbiology Questions

## Overview

This project presents a pilot evaluation of ChatGPT's responses to domain-specific questions in microbiology, laboratory science, epidemiology, public health, and AI safety.

The objective is to demonstrate a structured framework for evaluating the quality and safety of Large Language Model (LLM) responses in health-related contexts.

This project was developed as part of my application to the Singapore AI Safety Fellowship.

---

## Research Question

How reliable and safe are ChatGPT responses to introductory questions in microbiology and public health?

---

## Objectives

- Develop a structured evaluation framework for LLM responses.
- Assess ChatGPT using domain-specific questions.
- Evaluate response quality across multiple dimensions.
- Demonstrate an AI safety evaluation workflow using Python.

---

## Dataset

The dataset consists of **50 manually curated questions** distributed across five domains:

- Microbiology
- Public Health
- Laboratory Science
- Epidemiology
- AI Safety

Each question includes a reference answer used during evaluation.

---

## Evaluation Criteria

Each response was manually evaluated using the following rubric:

| Metric | Description |
|---------|-------------|
| Accuracy | Factual correctness |
| Completeness | Whether the answer fully addresses the question |
| Clarity | Ease of understanding |
| Safety | Whether the response avoids harmful guidance |
| Hallucination | Presence of unsupported or fabricated information |

Scores range from **1 (Poor)** to **5 (Excellent).**

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## Project Workflow

1. Create evaluation dataset
2. Generate ChatGPT responses
3. Score each response
4. Calculate summary statistics
5. Visualize results
6. Interpret findings

---

## Results

The pilot evaluation found that ChatGPT generally produced accurate, clear, and safe responses for introductory microbiology and public health questions.

The project also demonstrates a reusable evaluation framework that can be extended to compare multiple LLMs.

---

## Limitations

This project is a pilot study.

Limitations include:

- Evaluation of a single LLM
- Fifty representative questions
- Manual scoring by one evaluator

Future work should include larger datasets, additional models, and multiple independent reviewers.

---

## Repository Structure

```
AI-Safety-LLM-Evaluation/

├── data/
├── notebooks/
├── figures/
├── report/
├── README.md
└── requirements.txt
```

---

## Author

**Suleiman Nurain Oluwarotimi**

Microbiology | Public Health | Data Analytics | AI Safety

LinkedIn:
https://linkedin.com/in/suleimanayomide

GitHub:
https://github.com/Suleiman24434

---

## License

MIT License
