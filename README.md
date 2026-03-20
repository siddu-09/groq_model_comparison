# Groq Model Comparison

## Lab Overview

This project evaluates multiple Groq models and selects the one that gives a correct response with the lowest token usage.

### Hints

- Use the same prompt for every model to keep the comparison fair
- Compare both correctness and total token usage
- Use deterministic prompts for reliable evaluation

### What Each Component Does

| Component       | Description                                                    |
| --------------- | -------------------------------------------------------------- |
| Objective       | Defines the optimization goal: correctness + minimum tokens    |
| Background      | Explains token cost, quality trade-offs, and model variability |
| Evaluation flow | Standardizes how each model is tested and compared             |

### Project Structure

- **Objective:** Defines the optimization goal: correctness and minimum token usage.
- **Background:** Explains token cost, quality trade-offs, and model variability.
- **Evaluation Flow:** Standardizes the process for testing and comparing each model.

---

This repository is designed to help you systematically compare Groq models for both accuracy and efficiency.
