---
title: "Intent-Based Recommendation: Replicating and Extending DUIP"
authors: "Blair Park, Rajiv Garg"
venue: "Working paper"
year: 2026
status: working-paper
theme: "Consumer Behavior & Text Analytics"
order: 3
link: "https://github.com/ihumanoid/DUIP"
---
Traditional recommendation systems are good at pattern-matching on click history but bad at capturing *why* a user is browsing the way they are. This project replicates and extends DUIP (Dynamic User Intent Prediction) — a recommender architecture that pairs a lightweight LSTM session encoder with a frozen large language model to score candidate items by intent, not just co-occurrence.

The design keeps the LLM frozen and trains only a small LSTM, embedding table, and soft-prompt projector that translates session history into pseudo-tokens the LLM can reason over — making it feasible to run on a single consumer GPU rather than requiring full model fine-tuning. This extension evaluates the approach on new datasets and probes where intent-aware scoring outperforms conventional collaborative filtering, and where it doesn't.
