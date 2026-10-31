# Hi, I'm Andrii Boiko.

I'm a **Lead AI Engineer** based in Berlin. I work on production AI architecture, agents, retrieval, and evaluation.

[Case studies & personal projects](https://boiko.ai/work/) · [LinkedIn](https://www.linkedin.com/in/andriyboyko/) · [Hugging Face](https://huggingface.co/aboiko) · [Email](mailto:andrewvboyko@gmail.com)

## Selected projects

| Project | What it does |
| --- | --- |
| [pgwarden](https://github.com/B0yko/pgwarden) | An MCP gateway for Postgres with per-person database permissions, PII masking, human-approved writes, and auditable queries. |
| [taskdistill](https://github.com/B0yko/taskdistill) | Distils recurring LLM tasks into small local models with LoRA and MLX, held-out evaluation, and selective escalation to the original API. |
| [agent-claimcheck](https://github.com/B0yko/agent-claimcheck) | Checks agent success claims against tool receipts and state evidence. Includes calibrated decisions, a review queue, and a [labelled synthetic benchmark on Hugging Face](https://huggingface.co/datasets/aboiko/claimcheck-bench). |
| [Tern](https://github.com/B0yko/tern) | Local multimodal search for video and podcast archives on Apple Silicon, combining speech, on-screen text, and visual retrieval. |
| [local-enough](https://github.com/B0yko/local-enough) | Measures local and cloud models on business tasks: quality, latency, cost, and routing decisions against explicit quality thresholds. |
| [booking-truth](https://github.com/B0yko/booking-truth) | Tests AI booking agents on the calendar state they leave behind, with fault injection, pass^k, and false-success rates. Ships a guarded Cal.com, Google Calendar, and HubSpot booking agent. |

These are personal projects. Each repository documents its implementation, evaluation, and current limitations. Tern is source-visible under an all-rights-reserved licence; the other projects above use Apache-2.0.

## Production work

My [case studies](https://boiko.ai/work/) explain the architecture and engineering decisions behind that work.

## Tools I work with

Python · TypeScript · FastAPI · LangGraph · LangChain · PostgreSQL / pgvector · MCP · Docker

## Selected open-source contributions

- **[vLLM Semantic Router](https://github.com/vllm-project/semantic-router/pull/5373#issuecomment-6424806576)** · Technical review  
  Flagged duplicate score IDs that could silently change routing-evaluation results. The PR author [acknowledged the finding and added validation and regression tests](https://github.com/vllm-project/semantic-router/pull/5373#issuecomment-6518821351).

- **[Inspect Scout](https://github.com/meridianlabs-ai/inspect_scout/pull/751)** · Code contribution · Draft PR  
  Proposed incremental checkpointing to preserve completed loader results after interruption, with regression coverage for recovery and retries.
