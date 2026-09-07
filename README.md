<p align="center">
  <img width="1352" alt="Screen Shot 2024-11-18 at 0 50 11" src="https://github.com/user-attachments/assets/559a07af-f9c4-4503-9ad3-dca7e44d5545">
</p>

# Awesome‑GEO
Awesome list for research on GEO (Generative Engine Optimization).

# Awesome‑Generative‑Engine‑Optimization  
Generative Engine Optimization (GEO), is a paradigm to aid content creators in improving their content visibility in generative engine responses through flexible optimization frameworks for optimizing and defining visibility metrics.

This is a niche area, which is increasingly receiving attention from the community. This awesome‑listing is an attempt to bring together works in this space. This list is not complete and looking for your PRs to improve it. Thanks!


## 2026

- IF-GEO: Conflict-Aware Instruction Fusion for Multi-Query Generative Engine Optimization [[Paper]](https://arxiv.org/abs/2601.13938)
- Multimodal Generative Engine Optimization: Rank Manipulation for Vision–Language Model Rankers [[Paper]](https://arxiv.org/abs/2601.12263)
- Navigating the Shift: A Comparative Analysis of Web Search and Generative AI Response Generation [[Paper]](https://arxiv.org/abs/2601.16858)
- Source Composition of AI Answers: An Analysis of 167,551 Citations Across Generative Engines (Rankfor.AI, 2026) [[Paper]](https://doi.org/10.5281/zenodo.20829524)
- Demand-Side Measurement for Generative Engine Optimization: Constructing and Validating a Million-Persona, Intent-Annotated Buyer Corpus [[Paper]](https://arxiv.org/abs/2608.30023) [[Dataset]](https://huggingface.co/datasets/rankfor/PersonaGen-15K)
- The Dice Roll Method: A Standardized Protocol for Repeated-Query Auditing of Large Language Model Brand Recommendations [[Paper]](https://arxiv.org/abs/2609.04047) [[Code]](https://github.com/Rankfor/rankfor-open/tree/main/research/dice-roll-method)
- Who Owns the AI Recommendation? A Multi-Industry Empirical Map of Brand Category Ownership Across Large Language Models [[Paper]](https://arxiv.org/abs/2606.23057) [[Dataset]](https://doi.org/10.5281/zenodo.20788142)
- The Language of the Question Selects the Market: Query Language and Exit IP as Separable Factors in Commercial Recommendations from a Generative Search Interface [[Paper]](https://arxiv.org/abs/2608.30052) [[Dataset]](https://doi.org/10.5281/zenodo.22181306)
- How Large Language Models Source Brand Reputation Across Languages and Markets [[Paper]](https://arxiv.org/abs/2606.25787)
- The Language Blind Spot: How Query Language and Brand Recognition Tier Shape AI-Constructed Brand Reputation Across Twelve European Languages [[Paper]](https://arxiv.org/abs/2606.23165)
- Where Does the Noise Come From? A Variance-Components Decomposition of Non-Determinism in LLM Brand Answers [[Paper]](https://arxiv.org/abs/2607.13304)
- Who Gets Named: Citation Type Predicts Individual Naming by Grounded Language Models, and a Roster Instrument Captures 0.5% of It [[Paper]](https://arxiv.org/abs/2607.23893)

- Multi-Source Corroboration in GEO: Cross-Platform Deployment Strategy for AI Citation Optimization [[Resource]](https://github.com/shanhai-geo/geo-knowledge-base/blob/main/docs/strategies/multi-source-corroboration.md) — Empirical study showing 320% citation rate improvement when consistent information appears across 5-10 independent high-authority sources
## 2025

- C-SEO Bench: Does Conversational SEO Work?, NeurIPS D&B 2025, [[Paper]](https://arxiv.org/abs/2506.11097) [[Code]](https://github.com/parameterlab/c-seo-bench) [[Dataset]](https://huggingface.co/datasets/parameterlab/c-seo-bench)
- Dynamics Of Adversarial Attacks On Large Language Model‑Based Search Engines [[Paper]](https://arxiv.org/pdf/2501.00745)
- White Hat Search Engine Optimization using Large Language Models [[Paper]](https://arxiv.org/abs/2502.07315) 
- PoisonArena: Uncovering Competing Poisoning Attacks in Retrieval‑Augmented Generation [[Paper]](https://arxiv.org/abs/2505.12574)
- Beyond SEO: A Transformer‑Based Approach for Reinventing Web Content Optimisation [[Paper]](https://chatpaper.com/chatpaper/paper/158775)
- NExT‑Search: Rebuilding User Feedback Ecosystem for Generative AI Search [[Paper]](https://arxiv.org/abs/2505.14680)
- Role‑Augmented Intent‑Driven Generative Search Engine Optimization [[Paper]](https://arxiv.org/abs/2508.11158)
- StealthRank: LLM Ranking Manipulation via Stealthy Prompt Optimization [[Paper]](https://arxiv.org/abs/2504.05804)

## 2024

- GASLITeing The Retrieval: Exploring Vulnerabilities In Dense Embedding‑Based Search [[Paper]](https://arxiv.org/pdf/2412.20953)
- GEO: Generative Engine Optimization [[Paper]](https://arxiv.org/pdf/2311.09735)
- What Evidence Do Language Models Find Convincing? [[Paper]](https://arxiv.org/html/2402.11782v1)
- CONFLICTBANK: A Benchmark for Evaluating Knowledge Conflicts in Large Language Models [[Paper]](https://arxiv.org/abs/2408.12076)
- Adversarial Search Engine Optimization for Large Language Models [[Paper]](https://arxiv.org/abs/2406.18382)
- Ranking Manipulation for Conversational Search Engines [[Paper]](https://arxiv.org/abs/2406.03589)
- Persistent Pre‑Training Poisoning Of LLMs [[Paper]](https://arxiv.org/abs/2410.13722)
- Manipulating Large Language Models to Increase Product Visibility [[Paper]](https://arxiv.org/pdf/2404.07981)

## Open-Source Resources

- AI Citation Evidence Validator — Open-source, client-side validator for GEO/AEO observation records that checks evidence completeness, citation-field consistency, timestamps, and duplicate run keys. [[Tool]](https://corankai.github.io/ai-citation-evidence-validator/) [[Source]](https://github.com/corankai/ai-citation-evidence-validator) — Built by [Corank](https://corank.ai/).
- GEO Knowledge Base — Comprehensive open-source GEO reference with five-layer architecture, methodology documentation, and case studies [[GitHub]](https://github.com/shanhai-geo/geo-knowledge-base)
- GEO Open Protocol — Open standard for brand AI visibility measurement including Brand Visibility Index (BVI) [[Website]](https://shanhai-geo.github.io/geo-protocol/)
- Rankfor Open — MIT-licensed research repository holding the collectors, datasets, and analysis code behind the brand-visibility studies listed above, including the repeated-query audit protocol, per-study data packs, and a brand-mention detector. [[Source]](https://github.com/Rankfor/rankfor-open) — Built by [Rankfor.AI](https://rankfor.ai/).
- AI Answer Check — Single-file MIT Python CLI that asks a generative engine the same question about a business N times and reports how often the engine agreed with itself, so a claim about what an AI "says" can be separated from run-to-run variance. No signup and no dependencies; --direct runs entirely on your own API credentials. [[Tool]](https://ai-fact-check-psi.vercel.app/check) [[Source]](https://github.com/FoundagentTest/ai-answer-check) — Built by [Assay](https://ai-fact-check-psi.vercel.app/).

- AI Search Citation Benchmark for RAG vs Fine-Tuning — Reproducible Chinese-language dataset with run-level displayed sources from Qwen, Kimi, and Gemini plus strict unbranded Baidu snapshots; includes JSON/CSV downloads, hashes, and explicit zero-result retention. [[Dataset]](https://course.dragonai.tech/research/ai-search-rag-finetuning-citations-2026-07)
