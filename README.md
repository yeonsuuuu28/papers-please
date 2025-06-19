# PAPERSPLEASE: A Benchmark for Evaluating Motivational Values of Large Language Models Based on ERG Theory

Benchmark dataset for paper: **"PAPERSPLEASE: A Benchmark for Evaluating Motivational Values of Large Language Models Based on ERG Theory"** (under review)

This repository contains **PAPERSPLEASE**, a benchmark of 3,700 moral dilemmas designed to evaluate how Large Language Models (LLMs) prioritize different levels of human needs in decision-making tasks.

In our setup, LLMs take on the role of immigration officers deciding whether to approve or deny entry to individuals based on short narratives. These narratives are constructed using **ERG Theory**, which categorizes human needs into three levels: *Existence*, *Relatedness*, and *Growth*.

## Repository Structure

- `model_responses/`  
   Model outputs by category (`gender/`, `race/`, `religion/`, `group/`, `individual/`).  
   Each subfolder contains `.csv` files with decisions from different LLMs (e.g., GPT, Claude, Gemini).
- `scenarios/`  
   - `scenarios.csv`: General entry scenarios.  
   - `social_identity_scenarios.csv`: Scenarios with added identity cues.

## Description

Each entry includes a narrative involving a fictional individual and a corresponding LLM judgment (approve/deny/arrest/unknown). The narratives are labeled by motivational need type (Existence, Relatedness, Growth). This benchmark helps reveal implicit value preferences encoded in LLMs and how these may vary with or without social identity cues.

## Paper

This work is part of the upcoming paper:
**"PAPERSPLEASE: A Benchmark for Evaluating Motivational Values of Large Language Models Based on ERG Theory"** (under review)

Citation details will be added upon publication.

## License

Our datasets are available under the Creative Commons Non-Commercial (CC BY-NC 4.0).
