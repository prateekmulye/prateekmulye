# Hi, I'm Prateek

I'm a backend engineer. Most of my 11+ years has been on systems where losing or double-handling a message means real money goes the wrong way: payments, banking, and a data platform running 30M+ rows in Postgres. I tend to care most about the boring parts, like catching a bad input and retrying it instead of letting it quietly break something at 2am.

I also build agentic AI systems, and I build them the way I build backend systems: retries, idempotency, structured state, evals. ChatFormula1 (LangGraph + Pinecone RAG, live at [chatformula1.com](https://chatformula1.com)) and Assay (FinResearch AI — multi-agent equity research on LangGraph/FastAPI/pgvector, live on Hugging Face Spaces) are both deployed with CI, tests, and rate limiting. Both are below.

Right now I'm a Software Engineer at Agilent on the manufacturing side, where part of the job is helping the team actually use AI day to day. Before that: HG Insights, Capital One (through Cognizant), and AurionPro.

[prateekmulye.dev](https://prateekmulye.dev) · [LinkedIn](https://www.linkedin.com/in/prateekmulye/) · [Email](mailto:prateekmulye@gmail.com)

## Featured work

**[ChatFormula1](https://chatformula1.com)** — a single-agent agentic RAG assistant for Formula 1 *(live)*
One agent routes between a vector store and live web search, then answers over what it retrieves. Built with production hygiene: auth, rate-limiting, tests, structured logging, caching, graceful degradation, CI/CD, and Pydantic-typed state.
`LangGraph` · `Pinecone` · `Tavily` · `FastAPI` · `Pydantic`

**[Assay (FinResearch AI)](https://github.com/prateekmulye/assay)** — a multi-agent equity-research system *([live on Hugging Face Spaces](https://huggingface.co/spaces/prateekmulye/FinResearchAI))*
A LangGraph manager fans out to specialized research agents in parallel, then an analyst and a reporter write a verdict over what was retrieved. Every step emits structured JSON so the agents stay grounded instead of guessing. Grew out of my submission to the SuperDataScience CP044 community project.
`multi-agent` · `LangGraph` · `FastAPI` · `pgvector` · `RAG` · `Python`

**[slipstream-f1-strategist](https://github.com/prateekmulye/slipstream-f1-strategist)** — an event-driven race-strategy service
A reactive API publishes a request to Kafka, a consumer runs a deterministic simulation, and the result is written back exactly once. The NDA-free analogue of my Capital One reliability work: bounded retry with backoff and idempotent processing, so a bad message is retried sensibly and never processed twice.
`Java 21` · `Spring WebFlux` · `Kafka` · `PostgreSQL` · `OpenTelemetry` · `Testcontainers`

## What I work on

| | |
| :-- | :-- |
| **Distributed systems** | Apache Kafka, PostgreSQL at 30M+ rows, idempotent recovery, DLQ + bounded retry, service contracts |
| **Backend** | Java (Spring Boot), Elixir (Phoenix), Python, GraphQL and REST |
| **Applied AI** | LangGraph, RAG, Pinecone, Pydantic-typed state, multi-agent orchestration |
| **Platform** | Docker, Kubernetes, Terraform, OpenTelemetry, Datadog, AWS |

---

<div align="center">

More at **[prateekmulye.dev](https://prateekmulye.dev)**.

</div>
