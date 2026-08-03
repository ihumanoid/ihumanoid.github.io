---
title: "Domain Anchorage in GPT-4: A Computational Linguistic Analysis of Lexicographic Profiling and Its Implications for Unintended Information Dissemination"
authors: "Lekha Challappa, Jenevieve Zhang, Rajiv Garg"
venue: "Proceedings of the 58th Hawaii International Conference on System Sciences (HICSS)"
year: 2025
status: published
theme: "Fairness & Trustworthy AI"
order: 2
link: "https://hdl.handle.net/10125/109692"
extra_link: "https://www.rajivgarg.org/research"
extra_link_label: "Extended journal version — Data & Policy, vol. 7, e73 (2025)"
---
This project examines how GPT-4's attention and embedding layers respond after a conversation is "primed" toward a particular domain — asking whether the model's internal representations become anchored to that domain in ways that carry over to later, lexicographically unrelated queries with the same underlying intent.

Using computational linguistics methods to trace vector transformations and attention distributions across declarative primes and follow-up questions, the analysis finds that domain-specific terms can receive disproportionately high gradient weight, creating a kind of semantic echo chamber. The authors argue this raises real privacy and ethical concerns: a model exhibiting domain anchorage could inadvertently carry contextual information across what should be independent user interactions.

### Abstract
This study analyzes how GPT-4 processes semantic attention following domain priming, examining response similarity to lexicographically independent queries that share the same intent. Grounded in established computational linguistics frameworks, the analysis of vector transformations and attention distributions shows that domain-specific words can receive elevated gradient updates, introducing bias and forming semantic echo chambers. The authors highlight resulting privacy and ethical concerns, since the model may inadvertently carry information across users due to this domain-anchorage effect.
