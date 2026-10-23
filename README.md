# Jorge Arenas

**AI Trust Engineer | AI Evaluation & Reliability | Building AI Applications**

I work on the part of AI that has to hold up after the demo. My professional work includes agent-response QA, regression testing, decision-path checks, and operational reporting. In my own projects, I build Python applications that make model behavior easier to test, inspect, and improve.

I'm working toward AI Systems Engineering through practical projects: structured inputs and outputs, clear boundaries around model behavior, saved evidence, and tests for the things that can go wrong. I use AI tools in development, review the results, and stay responsible for the product and its behavior.

## Featured Projects

### [EvalForge](https://github.com/Roidneg/EvalForge) · AI evaluation workbench

I built a local workbench for checking supplied model responses, inspecting case-level evidence, and comparing evaluation runs. FastAPI, Pydantic, SQLite, and Streamlit support a reproducible workflow. Its synthetic sample moves from **7/12** passing cases to **11/12**, while the comparison still exposes **one regression**. The checks are deterministic and have stated limits; they do not stand in for a human judgment of correctness.

### [StoryDoor](https://github.com/Roidneg/StoryDoor) · interactive fiction with inspectable AI narration

Two playable mysteries use a Python story engine for choices and consequences, with an LLM handling narration. When narration breaks a targeted rule, the app can show an engine-written fallback and retain the original response for review. I added saved journeys, evaluation records, human review, offline regression fixtures, and automated tests. The project grew from a creative idea into a study of what happens when fluent model output conflicts with story state.

### [Star Trek Writer’s Room](https://github.com/Roidneg/Star-Trek-Writer-s-Room-Project) · staged AI generation with human review

I built a Streamlit demo that turns a creative brief into provisional character guidance and a screenplay scene. Python, Pydantic, and Cloudflare Workers AI support a two-stage workflow with downloadable generation records, at most two model calls per draft, and no automatic retries. The default offline suite passes **87 tests**. Live testing also exposed a useful distinction: structurally valid output can still contain unsupported claims and continuity errors. Drafts are explicitly labeled unverified and require human review; the broader research and validation workflows remain experimental.

[Explore the live demo](https://star-trek-writer-s-room-project-jorge.streamlit.app/) — the sample is open to everyone; live generation requires an access code.

### [RAG Hallucination Analysis](https://github.com/Roidneg/RAG-Hallucination-Analysis) · Power BI

I analyzed **6,000 labeled samples** in a two-page Power BI report comparing hallucination labels with and without retrieval. The second page examines the **463 outputs** still labeled as hallucinations with RAG. I document uneven domain sample sizes and the limits of drawing conclusions from this dataset.

### [Discord Job Intelligence](https://github.com/Roidneg/JobDiscordBot) · scheduled data pipeline

I built a Python pipeline that collects public job postings, normalizes and filters remote roles, scores matches with explicit rules, and sends a Discord digest. GitHub Actions runs the workflow on a schedule; saved state helps prevent repeat posts. The current ranking is rule based, providing a baseline for a future AI ranking experiment.

### [ProfileLens](https://github.com/Roidneg/ProfileLens_reddit_Visibility_auditor) · evidence and uncertainty

I built a Streamlit tool for comparing public Reddit profile listings with archived records. It reports evidence states and bounded checks without treating every missing item as proof that a post was deleted or concealed.

## What I Work With

Python · FastAPI · Pydantic · Streamlit · SQLite · pytest · GitHub Actions · SQL · Power BI · AI evaluation · agent QA

## How I Build

I like turning a vague idea into a working system, then asking what it misses. That means keeping failure cases, checking the data flow, and explaining what the tests do and do not prove. I collaborate with AI coding tools on these projects, while setting direction, reviewing behavior, and using observed failures to guide changes.

## Connect

- [LinkedIn](https://www.linkedin.com/in/jarena86/)
- [All repositories](https://github.com/Roidneg?tab=repositories)
