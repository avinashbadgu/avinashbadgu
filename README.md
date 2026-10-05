# Hi, I'm Avinash Badgu

**Software Engineer | Python Backends & AI Applications**

I build APIs and AI applications around document extraction, retrieval, evaluation, and structured data workflows.

[LinkedIn](https://www.linkedin.com/in/avinashbadgu/) · [GitHub](https://github.com/avinashbadgu) · Pune, India

## About Me

My projects connect model outputs to source evidence, validation rules, and human review. I work primarily with Python and FastAPI, with relational databases, background workers, and React or Next.js interfaces.

I'm interested in the engineering decisions behind AI features: when to retry, when to abstain, what to validate, and how to inspect failures.

## What I Build

- **AI applications:** document extraction, retrieval-augmented generation, hybrid search, reranking, and MCP integrations.
- **Python backends:** FastAPI services, relational data models, background workers, and deterministic workflow rules.
- **Evaluation and data workflows:** retrieval benchmarks, extraction validation, incremental ingestion, and trace collection.

## Featured Projects

### Document Intelligence Agent

A document-extraction pipeline with structural validation, field-level confidence scoring, source provenance, and a human review queue.

**Technologies:** Python, LangGraph, FastAPI, PyMuPDF, SQLAlchemy, Docker.

**Why it matters:** Makes extraction errors inspectable through validation and source evidence. The committed evaluation uses an offline extractor with seeded errors; it is not a live-model accuracy benchmark.

[View Repository](https://github.com/avinashbadgu/doc-intel-agent) · [Companion MCP Server](https://github.com/avinashbadgu/doc-intel-mcp-server)

[Pipeline implementation](https://github.com/avinashbadgu/doc-intel-agent/blob/main/app/graph/pipeline.py) · [Evaluation results](https://github.com/avinashbadgu/doc-intel-agent/blob/main/evals/results/ablation.md)

### Care Coordination Platform

A care-coordination application with typed timelines, medication reminders, deterministic escalations, and document review workflows.

**Technologies:** Python, FastAPI, SQLAlchemy, Pydantic, Next.js, TypeScript, pytest.

**Why it matters:** Demonstrates relational modeling and explicit business rules across a backend and frontend. AI providers are pluggable, with a deterministic local stub as the default.

[View Repository](https://github.com/avinashbadgu/care-coordination-platform)

[Workflow engine](https://github.com/avinashbadgu/care-coordination-platform/blob/main/app/workflows/engine.py) · [Tests](https://github.com/avinashbadgu/care-coordination-platform/tree/main/tests)

### Support Deflection Assistant

A RAG support assistant with hybrid retrieval, reranking, abstention, and an evaluation harness over a curated documentation corpus.

**Technologies:** Python, FastAPI, Chroma, BM25, OpenAI, Prefect, pytest.

**Why it matters:** Provides tools to compare retrieval configurations and inspect failure cases, rather than treating answer generation as the only measure of success.

[View Repository](https://github.com/avinashbadgu/support-deflection-assistant)

[Retrieval implementation](https://github.com/avinashbadgu/support-deflection-assistant/blob/main/src/support_assistant/retrieve.py) · [Evaluation reports](https://github.com/avinashbadgu/support-deflection-assistant/tree/main/data/eval_reports)

*The documented comparison covers five direct-retrieval questions and two configurations; broader abstention and faithfulness validation remains open.*

### LLM Trace Evaluation

An LLM trace collection and background evaluation application with a Python SDK and React dashboard.

**Technologies:** Python, FastAPI, SQLAlchemy, PostgreSQL, Redis, ARQ, RAGAS, React, Docker Compose.

**Why it matters:** Connects API instrumentation, asynchronous evaluation, relational persistence, and a UI for inspecting traces. The worker implements answer relevancy and conditional faithfulness evaluation.

[View Repository](https://github.com/avinashbadgu/llm-trace-eval)

[Evaluation worker](https://github.com/avinashbadgu/llm-trace-eval/blob/main/backend/app/eval_worker.py) · [Backend and SDK tests](https://github.com/avinashbadgu/llm-trace-eval/tree/main/backend/tests)

### Indian Equity Research Desk

A research application combining market-data providers, structured company analysis, and optional LLM commentary.

**Technologies:** Python, FastAPI, Next.js, React, EODHD, yfinance.

**Why it matters:** Demonstrates external provider integration and an end-to-end data application, with documented limits around delayed quotes and modeled fallback content.

[View Repository](https://github.com/avinashbadgu/indian-equity-research-desk)

## Tech Stack

| Area | Technologies |
| --- | --- |
| Languages | Python, SQL, JavaScript, TypeScript |
| Backend | FastAPI, Pydantic, SQLAlchemy, Alembic |
| AI and retrieval | LangGraph, RAG, Chroma, BM25, RAGAS, MCP |
| Data and workers | PostgreSQL, SQLite, Redis, ARQ, Prefect |
| Frontend | React, Next.js, Tailwind CSS |
| Development | Docker, Docker Compose, pytest, Git |

## Current Focus

- Preserving field-level confidence and source provenance from PDF extraction through MCP tool responses.
- Evaluating extraction validation and review thresholds with reproducible offline fixtures.
- Comparing retrieval, reranking, and abstention behavior in documentation-based RAG applications.

