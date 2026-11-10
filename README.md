# Varshitha C — AI Engineer & Applied AI Engineer

🌐 **[Visit the live portfolio](https://varshithaportfolio-ai-engineer.vercel.app/)**

AI Engineer focused on NLP, Generative AI, retrieval-augmented generation (RAG), LLM evaluation, and reliable tool-using agent workflows. This portfolio brings together my professional experience, technical skills, selected projects, education, and IEEE publication.

## Featured projects

### [Pika PACE — Autonomous Generative Video Studio](https://agenticai-lime-five.vercel.app/)
**Live demo · Interactive prototype · Agent-first creative workflow · Model MCP**

Public Vercel demo of an agent-first creative studio concept. The interface includes natural-language scene prompts, storyboard and timeline controls, camera-motion controls, an MCP configuration panel, and illustrative gateway/cost UI. [Project notes](projects/pika-pace/README.md).

### [Grounded Knowledge Assistant with Hybrid Retrieval](https://github.com/VarshithaChappidi/Grounded-Knowledge-Assistant-with-Hybrid-Retrieval)
A local document-QA MVP combining lexical and TF-IDF retrieval, reciprocal-rank fusion, source-linked evidence, and evidence-based abstention. Includes FastAPI endpoints, a small local benchmark, tests, Docker, and a PostgreSQL/pgvector extension schema. The current implementation does not yet include persistent pgvector integration, cross-encoder reranking, or LLM answer synthesis.

### [Tool-Using Agent Reliability and Evaluation Harness](https://github.com/VarshithaChappidi/Tool-Using-Agent-Reliability-and-Evaluation-Harness)
A LangGraph support-workflow demo using synthetic tickets and mock APIs. It exercises bounded retries, structured tool outcomes, ambiguous-request handling, prompt-injection-like inputs, and human approval requirements before proposed state-changing actions.

### [Conversation Intelligence Classification Benchmark](https://github.com/VarshithaChappidi/conversation-intelligence-classification-benchmark)
A conversational NLP benchmark project focused on intent classification, model comparison, per-class metrics, and error analysis.

### [Financial RAG Evaluation and Grounded Answering Agent](https://github.com/VarshithaChappidi/financial-rag-eval)
A retrieval-evaluation and grounded-answering project over SEC 10-K filings for five banks, using BM25 and dense retrieval, reciprocal-rank fusion, cross-encoder reranking, source citations, numeric verification, refusal behavior, and automated tests.

### [Text-to-SQL Fine-Tuning with QLoRA](https://github.com/VarshithaChappidi/text2sql-qlora) · [Fine-tuned model on Hugging Face](https://huggingface.co/Varshitha2603/qwen2.5-coder-3b-text2sql-qlora)
Fine-tuned Qwen2.5-Coder-3B-Instruct using 4-bit QLoRA on 5,000 examples; normalized SQL exact match improved from **57.0% to 77.3%** on 300 held-out questions.

## Professional experience

### Frontier Agents Engineer (Applied AI) — Scale, USA
*January 2025 – Present*

- Improved RAG retrieval **Recall@5 from 74% to 82%** across 300 labeled queries through chunking improvements, hybrid retrieval, and reranking.
- Built reusable LLM evaluation pipelines for groundedness, instruction adherence, and tool-use correctness using automated checks and human-reviewed scoring rubrics.
- Implemented LangGraph workflows with validated tool calls, bounded retries, and human-review checkpoints; improved task completion from **76% to 84%** across 150 evaluation scenarios.
- Reduced evaluation benchmark runtime from **45 to 36 minutes** through bounded concurrency and batched preprocessing.
- Deployed containerized inference and evaluation services with FastAPI, Docker, and AWS, integrating MLflow tracking, automated tests, and monitoring for failures, latency, and token usage.
- Collaborated with product managers, data annotation specialists, and backend engineers on acceptance criteria, model failure analysis, evaluation quality, and release trade-offs.

### AI Engineer — Observe.AI, India
*June 2021 – July 2023*

- Built NLP pipelines for intent classification, sentiment analysis, and conversation tagging from speech transcripts.
- Fine-tuned BERT-based intent classifiers with PyTorch and Hugging Face, improving **macro F1 from 0.79 to 0.85** on 1,500 held-out utterances.
- Implemented call-quality checks for greetings, required disclosures, and script adherence, reducing median review time from **6 to 5 minutes per call** in a controlled 100-call review.
- Packaged NLP models as FastAPI services with Docker, input validation, prediction logging, and versioned artifacts.

## Technical focus

- **Programming & data:** Python, SQL, Pandas, NumPy, preprocessing, dataset validation
- **ML & NLP:** PyTorch, Hugging Face Transformers, scikit-learn, BERT, fine-tuning, intent classification, sentiment analysis
- **Generative AI:** RAG, LangChain, LangGraph, Claude API, prompt/context engineering, tool calling, structured outputs, Pydantic, human-in-the-loop workflows
- **Retrieval & evaluation:** Embeddings, hybrid search, BM25, cross-encoder reranking, PostgreSQL/pgvector, Recall@K, Macro F1, groundedness, human evaluation, regression testing
- **Backend & MLOps:** FastAPI, REST APIs, Docker, AWS, MLflow, GitHub Actions, CI/CD, model versioning, logging, latency and cost monitoring
- **Engineering:** Pytest, unit/integration tests, Git, code reviews, documentation, requirements analysis, cross-functional collaboration

## Publication

**Interactive Projection Technology Using Hand Gesture Recognition with Attention Mechanism and ResNet**

Co-authored a peer-reviewed IEEE ICAAIC 2023 paper on an attention- and ResNet-based hand-gesture recognition system for touchless presentation navigation.

[Read on IEEE Xplore](https://ieeexplore.ieee.org/document/10141150/) · [DOI: 10.1109/ICAAIC56838.2023.10141150](https://doi.org/10.1109/ICAAIC56838.2023.10141150)

## Education

- **M.S., Computer and Information Science** — University of North Texas, USA | August 2023 – May 2025
- **B.S., Computer Science** — K L University, India | June 2019 – May 2023

## Links

- **Live portfolio:** https://varshithaportfolio-ai-engineer.vercel.app/
- **Pika PACE live demo:** https://agenticai-lime-five.vercel.app/
- **GitHub profile:** https://github.com/VarshithaChappidi
- **LinkedIn:** https://www.linkedin.com/in/chappidi-varshitha/

---

*Focused on building useful, well-evaluated AI systems that connect model capabilities with reliable real-world applications.*
