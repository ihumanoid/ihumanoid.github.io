---
title: "RAG Chunking for Long- and Short-Form Text: Optimizing Retrieval Cost and Quality"
authors: "Siyao Yu, Rajiv Garg"
venue: "Working paper"
year: 2026
status: working-paper
theme: "LLM Systems & Applications"
order: 2
---
Chunking strategy is one of the most consequential — and least principled — design choices in a retrieval-augmented generation (RAG) pipeline. Chunk too small and you lose context; chunk too large and you burn tokens (and money) retrieving irrelevant text. This project studies how the optimal chunking strategy differs between long-form documents and short-form text, and builds a cost-aware framework for choosing chunk size and overlap.

The goal is a practical decision rule: given a document type and a retrieval quality target, what chunking configuration minimizes cost per query without sacrificing the answers RAG is supposed to get right.
