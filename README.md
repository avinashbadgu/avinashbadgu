# Hi, I'm Avinash Badgu

Software Engineer building Python backends and AI applications, with a focus on retrieval, evaluation, document intelligence, and structured data workflows.

## About Me

I build APIs and applications that connect AI models with data, validation, and review workflows. My projects explore how to preserve source evidence, evaluate retrieval behavior, and keep business rules explicit when integrating AI into an application.

My recent work focuses on document extraction with field-level provenance and confidence scoring, alongside MCP interfaces that preserve that information for AI agents.

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

### Care Coordination Platform

A care-coordination application with typed timelines, medication reminders, deterministic escalations, and document review workflows.

**Technologies:** Python, FastAPI, SQLAlchemy, Pydantic, Next.js, TypeScript, pytest.

**Why it matters:** Demonstrates relational modeling and explicit business rules across a backend and frontend. AI providers are pluggable, with a deterministic local stub as the default.

[View Repository](https://github.com/avinashbadgu/care-coordination-platform)

### Support Deflection Assistant

A RAG support assistant with hybrid retrieval, reranking, abstention, and an evaluation harness over a curated documentation corpus.

**Technologies:** Python, FastAPI, Chroma, BM25, OpenAI, Prefect, pytest.

**Why it matters:** Provides tools to compare retrieval configurations and inspect failure cases, rather than treating answer generation as the only measure of success.

[View Repository](https://github.com/avinashbadgu/support-deflection-assistant)

### LLM Trace Evaluation

An LLM trace collection and background evaluation application with a Python SDK and React dashboard.

**Technologies:** Python, FastAPI, SQLAlchemy, PostgreSQL, Redis, ARQ, RAGAS, React, Docker Compose.

**Why it matters:** Connects API instrumentation, asynchronous evaluation, relational persistence, and a UI for inspecting traces. The worker implements answer relevancy and conditional faithfulness evaluation.

[View Repository](https://github.com/avinashbadgu/llm-trace-eval)

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

## Connect

[LinkedIn](https://www.linkedin.com/in/avinashbadgu/) · [GitHub](https://github.com/avinashbadgu)
