# Multi-Agent Pricing and Deal Recommendation System  
**(Google Agent Development Kit – ADK v1.19.0)**

## Overview
This project implements a **multi-agent intelligent shopping and deal-recommendation pipeline** using the **Google Agent Development Kit (ADK) v1.19.0**.  
The system analyzes a user’s product query and generates an optimal purchasing recommendation by coordinating multiple **specialized, tool-assisted agents**.

The pipeline demonstrates:
- Parallel agent execution
- Structured knowledge synthesis
- Sequential decision orchestration
- End-to-end execution within a Kaggle Notebook environment

---

## Motivation & Objective
Online shoppers face increasing difficulty in identifying the most cost-effective purchasing options due to:
- Fragmented marketplaces
- Multiple condition categories (new, used, refurbished)
- Scattered discount and coupon sources

The objective of this project is to **automate decision-making** by building a **scalable multi-agent framework** that:

- Retrieves current product prices
- Identifies used and refurbished marketplace offers
- Fetches active discount and coupon codes
- Analyzes all options holistically
- Produces a clear, data-grounded recommendation

This work explores how **LLM-based multi-agent systems** can improve real-world consumer decision workflows.

---

## System Architecture
The system follows a **modular, agent-based design**:

### Core Agents
- **Retail Specialist** → Fetches new product prices

- **Marketplace Specialist** → Fetches used/refurb options

- **Coupon Specialist** → Retrieves relevant discounts

### Orchestration
An **orchestrator agent** coordinates:
- Parallel execution of retrieval agents
- Structured aggregation of intermediate outputs
- Final decision synthesis based on price, condition, and discounts

---

## Key Technical Features
- Multi-agent coordination using **Google ADK**
- Tool-augmented agents for external information retrieval
- Parallel execution for latency reduction
- Structured intermediate representations for interpretability
- Fully reproducible Kaggle-based workflow

---
## Tech Stack
- Python
- Google Agent Development Kit (ADK v1.19.0)
- Large Language Models (LLMs) [Google's Large language Models]
- Kaggle Notebook Environment

## Kaggle Notebook
👉 https://www.kaggle.com/code/bhargavikanojia/deal-hunter-ai-agent

## Author
Bhargavi Kanojia
Artificial Intelligence & Data Science Undergrad'27


## Installation & Setup
Install Google ADK inside the notebook environment:

```bash
pip install --upgrade google-adk


