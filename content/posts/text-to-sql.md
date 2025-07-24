---
title: "Finetuning LLM for Text-to-SQL generation"
date: 2025-07-24T01:12:08Z
draft: false
tags: ["ai", "llm", "project"]
---

I just completed a [project](https://github.com/l1-ca0/text-to-sql-finetune) that lets people ask database questions in plain English and get back proper SQL queries using a fine-tuned large language model. 

For the base model, I chose Mistral-7B-v3 and fine-tuned it specifically for SQL generation. Using QLoRA for efficient training, I was able to train the 7-billion parameter model on a single consumer-grade GPU (Nvidia Tesla P100) in around 3 hours. 

The resulting model performs well on common SQL patterns like filtering, joins, and aggregations, effectively handling the majority of real-world database queries. That said, it can be less accurate for complex subqueries or really intricate nested queries due to the limitations of the Mistral-7B model —- a larger model would handle these cases better, but this was a tradeoff between performance and computational requirements.

## The Applications

To make the model accessible, I built three interfaces:

**Web Interface**: A simple web app built with Gradio that allows anyone to try the tool without setup. Users can input their database schema, ask questions in natural language, and instantly see the generated SQL queries. The interface provides example databases and sample questions to help users get started, validates SQL syntax, and displays the query results.

**Command Line Interface**: A CLI designed for terminal lovers. It features session management, command history and syntax highlighting.

**Notebook Interface**: An interactive notebook environment for use on platforms such as Jupyter Notebook, Google Colab and Kaggle Notebook.

---
