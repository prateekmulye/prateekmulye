[![Prateek Mulye: Software engineering. Applied AI.](https://prateekmulye.dev/media/brand-portfolio-cover.png)](https://prateekmulye.dev/)

# Prateek Mulye

**Senior Software Engineer · Backend & Distributed Systems · Applied AI**

I build AI applications, drawing on 11+ years in software engineering. Much of my work has involved keeping data pipelines and event-driven systems reliable. My latest projects apply local models to payment review, building electricity readings and captions.

[Portfolio](https://prateekmulye.dev) · [Engineering index](https://prateekmulye.github.io/) · [LinkedIn](https://www.linkedin.com/in/prateekmulye/)

## Current projects

**[Payment Exception Desk](https://payments.prateekmulye.dev/)** reviews incoming credits against expected payments. MiniLM ranks descriptions after exact amount, currency and date checks. A reviewer chooses the matches and exports decisions with source evidence. The app does not initiate payments. [Source](https://github.com/prateekmulye/payment-exception-desk).

**[Load Review](https://energy.prateekmulye.dev/)** inspects electricity readings against occupied hours. A TensorFlow.js model trains locally and must outperform simpler baselines on later readings before flagging periods for investigation. Reviewers can trace findings to the original intervals. All three public-building trials withheld flags; no savings claim is made. [Source](https://github.com/prateekmulye/load-review).

**[Caption Review](https://captions.prateekmulye.dev/)** compares an English WAV recording with existing captions using Whisper. Listen, accept or edit individual cues, then export the revised track and edit log. No suggestion changes the track without a review decision. [Source](https://github.com/prateekmulye/caption-review).

These are personal projects, hosted as static applications on Cloudflare Pages. Inference runs on the user's device. Inputs and review decisions stay in browser memory, so reviews need to be exported before closing. The checks establish workflow behavior, not operational accuracy or customer adoption.

## Other work

**[Assay](https://github.com/prateekmulye/assay)** builds on my contribution to the SuperDataScience CP044 FinResearch AI community project. The implementation includes parallel analyst workflows, streamed reports, pgvector search with keyword fallback, and an evaluation harness comparing debate and non-debate workflows. Investment accuracy and production adoption remain unverified.

**[ChatFormula1](https://github.com/prateekmulye/ChatFormula1)** is in development. Its v2 combines Python/LangGraph retrieval and query routing with an Elixir/Phoenix streaming gateway. A typed React client handles duplicate and replayed events. The earlier public v1 is a separate implementation.

## Engineering foundation

- **HG Insights (W1):** Owned architecture through phased rollout of a geo-standardization service that normalized 15M+ U.S. and Canadian company records. [NDA-safe case study](https://github.com/prateekmulye/geo-standardization-case-study).
- **Cognizant, for Capital One (W4):** Owned Kafka recovery workflows with dead-letter handling, bounded retries, backoff, and idempotent replay.
- **Agilent:** Senior Software Engineer, Manufacturing. Built internal applications for Gemba reporting and action tracking. Gemba walks are Lean shop-floor observation rounds. Both applications are used by colleagues and reduce manual coordination. Leadership has expressed interest in wider rollout. I also support manufacturing processes and lead internal AI education.

The public projects are personal work. The career records describe my work for employers without publishing their source code or internal data.
