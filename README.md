# Ahmed Agent Messaging Evidence

**Prompt + curated external evidence pack** for Ahmed Bashir (DevRev CTO) weekly X messaging on **agent operators / autonomy**.

This repo is research scaffolding: it helps keep messaging **evidence-backed** while staying on **one core narrative** framed many ways — not fifty unrelated topics.

## What’s in here

| File | Purpose |
| --- | --- |
| [`PROMPT.md`](./PROMPT.md) | Self-contained weekly research prompt — paste into an LLM to refresh evidence |
| [`EVIDENCE.md`](./EVIDENCE.md) | Starting curated corpus (papers, lab blogs, standards, OSS docs) mapped to 5 angles |
| [`sources.json`](./sources.json) | Machine-readable list of the same corpus |
| [`README.md`](./README.md) | This file |

## Core messaging strategy

Repeat **one** core message (~100 framings), not invent 50 pillars:

> Build **operators** that move work **managed → conversational → autonomous**, with **precision, efficiency, and safety** — without conflating **search / context / memory** — using **open models with safety** (reversibility, evidence, alignment) and climbing **L1→L4** autonomy deliberately (vehicle-style levels).

### Five angles

1. Precision, efficiency, safety  
2. Not conflating search with context or memory  
3. Managed work → conversational work → autonomous work  
4. Building operators; L1 to L4 autonomy levels  
5. Embracing open models + safety  

## How to use `PROMPT.md`

1. Open [`PROMPT.md`](./PROMPT.md).
2. Paste the full prompt into your LLM of choice (or a scheduled research agent).
3. Ask it to follow the output schema and produce a dated refresh.
4. Merge strong new sources into `EVIDENCE.md` / `sources.json`; drop weak or duplicated ones.
5. Prefer primary sources; **never** use X/Twitter scraping or the X API as primary evidence.

`EVIDENCE.md` is a **starting corpus**, not a permanent canon — re-run the prompt weekly as labs and standards move.

## Attribution

Curated for **Nimit Savant / DevRev X growth research**.  

**Not** official DevRev marketing. Do not invent DevRev product claims from this pack.

## Suggested public repo name

`ahmed-agent-messaging-evidence`

## License

Prompt text and curation structure: **CC-BY-4.0** (attribution requested) **or MIT** — pick one when publishing.

Underlying papers/standards remain under their own licenses; link out rather than redistributing PDFs when in doubt.

## Quality bar (maintainers)

- Every URL should be fetchable or confirmed via search with full URL.
- No fabricated papers or fake DOIs.
- No X/Twitter links as primary evidence.
- Flag **Established** vs **Speculative** in refresh notes.
