# Multi-Agent Stock Research System

This project demonstrates how to design and orchestrate a **multi-agent AI system** for end-to-end decision-making.

Instead of relying on a single prompt, the system decomposes the problem into **clearly defined roles** coordinated by a manager agent.

## Architecture

- **Manager Agent** – plans, delegates, and evaluates
- **Trending Company Finder Agent** – scans live news
- **Financial Research Agent** – analyzes fundamentals and risks
- **Stock Picker Agent** – compares candidates and selects the best option
- **Notification Tool** – delivers the decision in real time

The focus is on **coordination, determinism, and system design**, not model cleverness.

## Why this matters

As LLM-based systems scale, the hardest problems are no longer:
- prompt quality
- model size

They are:
- delegation
- state & context flow
- reproducible decision pipelines

This repository is a reference implementation of those ideas.

## Disclaimer

This project is for **educational and architectural demonstration purposes only**  
It does **not** provide financial advice.
