# Hack With Hyderabad 3 — Hindsight hackathon: notable projects

Curated from the 101 non-duplicate submissions I reviewed as **Mentor 10** (sheet rows 1425–1582), 2026-10-01.
Each repo was cloned and checked for real Hindsight API/SDK use (retain / recall / reflect), code size, commit history, README and demo video.

> **Licensing:** only MemoLint is MIT. Everything else has no licence = all rights reserved. Use these for ideas and patterns, not copy-paste — especially into client work.

## Top picks

| Project | Why |
|---|---|
| [pre-mortem](https://github.com/DeathSurfing/pre-mortem) | Most serious build: 47 commits, ~9k lines, 3.4k-word README, live demo at premortem.lexcontra.com. Decision reviewer that **refuses to answer without evidence**. |
| [incident-response-agent](https://github.com/Sanjanasree02/incident-response-agent) | 51 commits, deepest Hindsight integration (retain/recall/reflect across 25 files). |
| [SentryMind](https://github.com/Aumnamaha/SentryMind) | Redacts incident text before the LLM; treats recalled memory as untrusted input. Most security-aware design. |
| [MemoLint](https://github.com/WaifuPuller/MemoLint) | Code reviewer that remembers rejected advice. 29 commits over 55h. **MIT — reusable.** |
| [CompetitorIQ](https://github.com/24pa1a42a8-design/CompetitorIQ) | Largest and most polished (~17k lines, 52 Hindsight files). |

## Ideas relevant to Contralyne

- **PII redaction before the LLM** — [dealmemory](https://github.com/akolluru4211/dealmemory) strips passwords/SSNs/API keys before inference, with tests. Matches ContractKen's "Moderation Layer".
- **Policy vs. practice drift** — [Policy_Drift_Agent](https://github.com/NohithaDachepalli/Policy_Drift_Agent) compares written policy with actual decisions → playbook rule vs. what was really accepted in past contracts.
- **Refuse without evidence** — [pre-mortem](https://github.com/DeathSurfing/pre-mortem): suppress findings that can't cite source text (anti-hallucination for legal).
- **Hold / send decision desk** — [payerline](https://github.com/Hasini-09guttula/payerline): an approve/escalate UI that shows its reasons.

## Good — 70+/80 (34 projects)

### User-Feedback-Synthesizer — Iris · **76/80**

*Turn multi-channel customer feedback into living, persistent product intelligence using Hindsight Agentic Memory and Hugging Face Pretrained Models.*

- **Repo:** https://github.com/siribeesu/User-Feedback-Synthesizer
- **Demo:** https://youtu.be/H6wdISOmmsM
- **Article:** https://drive.google.com/file/d/1jt9m3BgCSoqi0_kHhzSBQArNNa3j4Jcp/view
- **Hindsight use:** deep · ~6,672 lines · 19 commits · licence: none (all rights reserved)

### payerline — QuadX · **76/80**

Cashless pre-authorisation desk for St. Brigid Memorial Hospital.

- **Repo:** https://github.com/Hasini-09guttula/payerline  (teammates' forks: https://github.com/padamatintisrimukhi/payerline)
- **Demo:** https://youtu.be/cKinU3VmM7s
- **Article:** https://dev.to/guttula_hasini/hindsight-made-yesterdays-denial-part-of-todays-review-59nc
- **Hindsight use:** deep · ~4,715 lines · 15 commits · licence: none (all rights reserved)

### dejavu-payments-agent — TECHVENGERS · **76/80**

DejaVu remembers every failed payment your operations desk has ever fixed. It uses that memory to diagnose the next one in seconds and warns you before a payment fails. It is built on Hindsight agent memory, with Groq fo…

- **Repo:** https://github.com/AKSHAYAa10/dejavu-payments-agent  (teammates' forks: https://github.com/roopa-codes/dejavu-payments-agent, https://github.com/SaiSruthiG8074/dejavu-payments-agent, https://github.com/aaronthomas7/dejavu-payments-agent)
- **Demo:** https://drive.google.com/file/d/1rFbX_CFVh0lZ9_gYGM-J0xd2m0Mzn84_/view
- **Article:** https://medium.com/@akshayaroyalpasupuleti/why-our-ai-payment-agent-stopped-making-expensive-mistakes-the-power-of-memory-65994717a0ba
- **Hindsight use:** deep · ~5,242 lines · 8 commits · licence: MIT License

### resolveiq — Code Crafters · **76/80**

ResolveIQ is an AI customer support agent that uses Hindsight by Vectorize to recall relevant support experiences, generate grounded recommendations, and retain outcomes for future cases.

- **Repo:** https://github.com/harshadsr28-wq/resolveiq
- **Demo:** https://lnkd.in/p/dxWyRkeM
- **Article:** https://dev.to/harshad_sr_/the-missing-feedback-loop-behind-our-support-agent-5dh5
- **Hindsight use:** deep · ~1,779 lines · 5 commits · licence: none (all rights reserved)

### incident-response-agent — TDS · **76/80**

An AI agent that remembers every past production incident at ShopFast (a fictional e-commerce platform) and uses that memory to suggest root causes and fixes for new incidents. Built on Hindsight memory and Groq.

- **Repo:** https://github.com/Sanjanasree02/incident-response-agent
- **Demo:** https://youtu.be/3PpXA27gcX0
- **Article:** https://ssree6204.substack.com/p/hindsight-taught-my-incident-agent
- **Hindsight use:** deep · ~7,368 lines · 51 commits · licence: none (all rights reserved)

### pre-mortem — Keplers · **76/80**

Live demo: premortem.lexcontra.com — open it and try one of the

- **Repo:** https://github.com/DeathSurfing/pre-mortem
- **Demo:** https://youtu.be/SMpy9KXTb94
- **Article:** https://adityavikramdev.substack.com/p/i-built-a-decision-reviewer-that
- **Hindsight use:** deep · ~9,132 lines · 47 commits · licence: none (all rights reserved)

### DebugHindsight — CodeForge · **76/80**

An AI-powered debugging agent with persistent memory that learns from previous debugging experiences.

- **Repo:** https://github.com/deepthireddy2488/DebugHindsight
- **Demo:** https://youtu.be/qNNqRoxmROk
- **Article:** https://dev.to/deepthireddy2410/debughindsight-building-an-ai-debugging-agent-with-persistent-memory-25ge
- **Hindsight use:** deep · ~1,831 lines · 5 commits · licence: none (all rights reserved)

### Policy_Drift_Agent — ByteForge Syndicate · **76/80**

Production-ready AI hackathon application powered by Hindsight Cloud Persistent Memory (Vectorize.io) and Groq LLM Reasoning.

- **Repo:** https://github.com/NohithaDachepalli/Policy_Drift_Agent
- **Demo:** https://youtu.be/27yFPdKxcjk
- **Article:** https://medium.com/@ashubegum548/i-tested-zero-memory-against-hindsight-recall-678f95da82c8
- **Hindsight use:** deep · ~4,141 lines · 5 commits · licence: none (all rights reserved)

### BATCHWISE-AI-Powered-Supplier-Sourcing-Agent-with-Hindsight-Persistent-Memory — GEEKSX · **76/80**

Experience-Driven Supplier Sourcing Agent with Hindsight Persistent Memory

- **Repo:** https://github.com/rithvik-30/BATCHWISE-AI-Powered-Supplier-Sourcing-Agent-with-Hindsight-Persistent-Memory
- **Demo:** https://youtu.be/KTRsfn3L6ys
- **Article:** https://github.com/rithvik-30/BATCHWISE-AI-Powered-Supplier-Sourcing-Agent-with-Hindsight-Persistent-Memory/blob/main/BATCHWISE_TECHNICAL_ARTICLE.md
- **Hindsight use:** deep · ~5,038 lines · 10 commits · licence: none (all rights reserved)

### recall-ops-production — VersionControl.IO · **76/80**

Recall-Ops is an AI-powered production incident-response agent that uses Hindsight as a persistent memory layer to remember past production incidents, root causes, successful fixes, and deployment relationships. When a n…

- **Repo:** https://github.com/Charan9441/recall-ops-production
- **Demo:** https://drive.google.com/file/d/1q2emTRXfMXgbk3XCUbFxb_6sPjzxjoMT/view
- **Article:** https://drive.google.com/file/d/11q_ez86nm89sh_8QVyX3oVPkaKKZRH3C/view
- **Hindsight use:** deep · ~2,563 lines · 8 commits · licence: none (all rights reserved)

### SentryMind — Abyss · **76/80**

SentryMind sends redacted incident text to a configured local LLM and retrieves matching incident history from Hindsight. Retrieved notes are untrusted historical context: the agent asks operators to review and verify an…

- **Repo:** https://github.com/Aumnamaha/SentryMind
- **Demo:** https://lnkd.in/p/dn3wQfsY
- **Article:** https://lnkd.in/p/dN-q2dHE
- **Hindsight use:** deep · ~6,709 lines · 12 commits · licence: none (all rights reserved)

### DeployGuard — MONSTER · **74/80**

An AI-powered DevOps pipeline agent that connects to authorized GitHub repositories, monitors

- **Repo:** https://github.com/pranaviyalala-hub/DeployGuard  (teammates' forks: https://github.com/amulyakulkarni08/DeployGuard)
- **Demo:** https://youtu.be/P3loNDWxcvk
- **Article:** https://www.linkedin.com/pulse/incident-memory-hindsight-have-we-seen-before-pranavi-yalala-u69ef
- **Hindsight use:** deep · ~7,606 lines · 3 commits · licence: none (all rights reserved)

### ProMaker — AA ctrl · **74/80**

Your product team's decision memory. Don't repeat what already failed.

- **Repo:** https://github.com/akhileshsiva1212-gif/ProMaker
- **Demo:** https://youtu.be/e1twCUCXJGM
- **Article:** https://medium.com/@akhilesh.pinisetti21/promaker-building-an-ai-product-decision-memory-system-0455e7aa625e
- **Hindsight use:** deep · ~2,314 lines · 6 commits · licence: none (all rights reserved)

### Deal-intelligence-agent — Sage · **74/80**

A sales copilot that briefs a rep from memory, not from a blank chat. It remembers every touch on a deal, and it remembers which objection-handling tactics won or lost on other deals.

- **Repo:** https://github.com/teju2028/Deal-intelligence-agent
- **Demo:** https://drive.google.com/drive/folders/15w7omMqSkzTHogZFNoH4qSNzYLJvDqXm
- **Article:** https://drive.google.com/file/d/1JBQeiqUnb-PhJeqQ5EVTe5Wlyd1ekNde/view
- **Hindsight use:** deep · ~3,821 lines · 7 commits · licence: none (all rights reserved)

### promptGuard — code_blooded · **74/80**

PromptGuard AI is an enterprise-grade AI security gateway that acts as a zero-trust proxy between developers/applications and public cloud LLM services (such as Groq). It detects sensitive PII, passwords, financial cards…

- **Repo:** https://github.com/sakhipuvvadi/promptGuard
- **Demo:** https://drive.google.com/file/d/1fQfPPCwh1Cp7-mSHZA_bdbjWHD_Jc7_d/view
- **Article:** https://medium.com/@naraharineeraja2005/prompt-guard-069fa765db84
- **Hindsight use:** deep · ~3,414 lines · 3 commits · licence: none (all rights reserved)

### CompetitorIQ — NexGen Minds · **74/80**

CompetitorIQ is an AI-assisted competitive intelligence workspace designed to help teams understand what competitors are doing, why those changes matter, and how activity across time connects. Instead of treating every c…

- **Repo:** https://github.com/24pa1a42a8-design/CompetitorIQ
- **Demo:** https://youtu.be/iNtTHbLdLAk
- **Article:** https://dev.to/sorra_vedakshari_334b9677/competitoriq-46fc
- **Hindsight use:** deep · ~16,850 lines · 3 commits · licence: none (all rights reserved)

### EchoMind--Agentic-AI-with-Organizational-Memory — Thridha labs · **74/80**

EchoMind is an agentic AI system with persistent organizational memory that enables AI

- **Repo:** https://github.com/Srinadhch07/EchoMind--Agentic-AI-with-Organizational-Memory
- **Demo:** https://youtu.be/OahxMV7u3y4
- **Article:** https://srinadhch07.medium.com/i-built-a-support-agent-that-learns-with-hindsight-a2b862fe9fec
- **Hindsight use:** deep · ~9,669 lines · 3 commits · licence: none (all rights reserved)

### engbrain-hindsight-cloud — Stack Titans · **74/80**

The differentiator is persistent Hindsight memory: commits, PRs, incidents, deployments, root causes, fixes, and architecture decisions — linked and searchable.

- **Repo:** https://github.com/Varshithareddy2603/engbrain-hindsight-cloud
- **Demo:** https://youtu.be/-60vVQv2rOI
- **Article:** https://medium.com/@varshithareddym26/how-we-stopped-junior-devs-from-undoing-intentional-hacks-using-hindsight-8bbd475e1db5
- **Hindsight use:** deep · ~1,973 lines · 6 commits · licence: none (all rights reserved)

### tier-n — nerders · **73/80**

When a typhoon heads for Kaohsiung, a stateless AI copilot tells you to "monitor the situation and consider alternate suppliers."

- **Repo:** https://github.com/raheem-ui/tier-n  (teammates' forks: https://github.com/mohit20678/tier-n)
- **Demo:** https://youtu.be/MRlkknt82E8
- **Article:** https://dev.to/raheemui/why-my-ai-risk-analyst-needed-to-remember-a-typhoon-from-2024-5d4f
- **Hindsight use:** deep · ~1,244 lines · 15 commits · licence: none (all rights reserved)

### MemoryOps — Techizens · **73/80**

An incident-response agent that gets better at diagnosing outages the more outages it sees.

- **Repo:** https://github.com/ShashankChilukuri/MemoryOps
- **Demo:** https://youtu.be/8UIuBLc8Lc0
- **Article:** https://memoryops.hashnode.dev/hindsight-taught-my-on-call-agent-to-stop-misdiagnosing-the-same-bug
- **Hindsight use:** deep · ~646 lines · 7 commits · licence: none (all rights reserved)

### memoryassit-ai — Alphacoders · **73/80**

Enterprise technical support and DevOps incident management is broken in one specific way: customers are forced to repeat themselves every single time.

- **Repo:** https://github.com/VemireddyBhavana/memoryassit-ai
- **Demo:** https://drive.google.com/file/d/1_0LlR1oNtr2bufVnT_7Bc-N0abFq9lsK/view
- **Article:** https://dev.to/bhavana_vemireddy_1f1c88e/how-i-built-an-enterprise-support-agent-that-never-forgets-an-incident-using-hindsight-ee8
- **Hindsight use:** deep · ~950 lines · 11 commits · licence: none (all rights reserved)

### PulseLoop — Velora · **72/80**

PulseLoop is a memory-driven customer feedback intelligence platform that transforms customer feedback from isolated records into meaningful product intelligence.

- **Repo:** https://github.com/krithikaabbagoni111-dev/PulseLoop
- **Demo:** https://youtu.be/iq67Dv8aqZ4
- **Article:** https://www.linkedin.com/pulse/how-i-turned-customer-feedback-product-intelligence-krithika-abbagoni-c63qf
- **Hindsight use:** deep · ~6,258 lines · 5 commits · licence: none (all rights reserved)

### Recall-desk — Sprintx · **72/80**

When a customer contacts support again about the same problem, each new agent usually starts from zero and the customer has to explain everything again. RecallDesk fixes this with an AI support agent that has long-term m…

- **Repo:** https://github.com/GouthamAdepu/Recall-desk
- **Demo:** https://youtu.be/4Brd0lgy5xY
- **Article:** https://medium.com/@kalasthriharshini/why-customer-support-needs-memory-003f5881f6d6
- **Hindsight use:** deep · ~3,394 lines · 1 commits · licence: none (all rights reserved)

### Microsoft_project — Achivers · **72/80**

OpsMind is an AI-powered Incident Response Agent that uses persistent memory to remember previous production incidents, their root causes, resolutions, successful runbooks, resolution times, and post-mortems.

- **Repo:** https://github.com/nikitha0716/Microsoft_project
- **Demo:** https://youtube.com/shorts/-cb5NWyWyxk
- **Article:** https://medium.com/@nikithabangari07/opsmind-building-a-memory-powered-ai-incident-response-agent-with-hindsight-3f94883a0833
- **Hindsight use:** deep · ~1,509 lines · 1 commits · licence: none (all rights reserved)

### microsoft-hack-3.0 — CoffeeAndCode · **72/80**

RecallOps is an AI-powered incident intelligence platform built for Site Reliability Engineers (SREs) and DevOps teams. Unlike stateless AI assistants that repeatedly offer generic troubleshooting checklists, RecallOps i…

- **Repo:** https://github.com/ashrithaitham001/microsoft-hack-3.0
- **Demo:** https://youtu.be/j8Lj1jJ8K3E
- **Article:** https://medium.com/@akkasanirathnavarsha/ai-intelligence-agent-33760f90cb36
- **Hindsight use:** deep · ~5,521 lines · 1 commits · licence: none (all rights reserved)

### IncidentIQ — The Five · **72/80**

subgraph LiveCluster["Simulated Live Environment (Fintech Prod)"]

- **Repo:** https://github.com/likitha-medaboina/IncidentIQ
- **Demo:** https://drive.google.com/file/d/1uJsj99jlIzvm2igjTZzJZQbxEtD0k1Oc/view
- **Article:** https://medium.com/@medaboinalikitha643/we-gave-a-devops-agent-institutional-memory-heres-what-changed-11c129f6fb28
- **Hindsight use:** deep · ~5,550 lines · 1 commits · licence: none (all rights reserved)

### Incident-response-ai-agent — Code Hunter's (7496bc45) · **72/80**

An incident-response console that compares a stateless Groq answer with a Hindsight-grounded answer. Memory starts empty, and only lessons an engineer explicitly approves are retained.

- **Repo:** https://github.com/rakesh-0918/Incident-response-ai-agent
- **Demo:** https://youtu.be/4R05ouVkAYE
- **Article:** https://www.reddit.com/r/LLMDevs/s/BLGZrL29Hy
- **Hindsight use:** deep · ~1,674 lines · 1 commits · licence: none (all rights reserved)

### HireRecall-AI — Hyderabyte · **72/80**

In modern technical hiring, multiple interviewers evaluate a candidate across screening, system design, coding, and behavioral rounds. However:

- **Repo:** https://github.com/sopparisaisri6332/HireRecall-AI
- **Demo:** https://youtu.be/2msJLde1LAI
- **Article:** https://medium.com/@sopparisaisri/hirerecall-ai-building-a-persistent-memory-agent-for-multi-round-interviews-b444da433c46
- **Hindsight use:** deep · ~7,964 lines · 1 commits · licence: none (all rights reserved)

### Code-Review-Agent — ETF · **72/80**

An AI code reviewer that learns a team's coding standards, recurring mistakes, and review preferences over time. Instead of behaving like the same generic reviewer for every codebase, it uses Hindsight memory to recall t…

- **Repo:** https://github.com/Sailajayadav/Code-Review-Agent
- **Demo:** https://youtu.be/beMj1F47vj4
- **Article:** https://medium.com/@veerlasailajayadav/how-agent-memory-stopped-my-reviewer-from-repeating-itself-9018b29e3d7d
- **Hindsight use:** deep · ~1,601 lines · 1 commits · licence: none (all rights reserved)

### DealMind — Zyra · **72/80**

DealMind is a negotiation intelligence platform that helps sales teams make winning decisions by combining Hindsight long-term organizational memory, evidence-grounded reasoning, deterministic business rules, and LLM syn…

- **Repo:** https://github.com/Nikhilll-dev-code/DealMind
- **Demo:** https://youtu.be/3aJ-Ur-Byqg
- **Article:** https://dev.to/nikhil_sathelli_266b94d61/we-built-dealmind-to-remember-what-actually-works-in-negotiations-2o7g
- **Hindsight use:** deep · ~4,900 lines · 2 commits · licence: none (all rights reserved)

### soc-triage-agent — Coding Ninjas · **72/80**

An AI-assisted SOC alert triage agent that learns from analyst feedback using persistent Hindsight memory.

- **Repo:** https://github.com/Nithin2801/soc-triage-agent
- **Demo:** https://youtu.be/itjOiBl5A-A
- **Article:** https://www.linkedin.com/pulse/soc-alert-triage-agent-hindsight-memory-turning-past-analyst-devika-p-vh82c
- **Hindsight use:** deep · ~4,341 lines · 7 commits · licence: none (all rights reserved)

### dealmind-ai-sales-agent — Team Nexus · **71/80**

DealMind helps a salesperson recover the requirements, objections and preferences

- **Repo:** https://github.com/Vaishnavi-Naga-Sai-Ravula/dealmind-ai-sales-agent
- **Demo:** https://www.youtube.com/watch
- **Article:** https://github.com/Vaishnavi-Naga-Sai-Ravula/dealmind-ai-sales-agent/blob/main/article.md
- **Hindsight use:** deep · ~1,063 lines · 3 commits · licence: none (all rights reserved)

### codementor-ai — Commit 4 chaos · **71/80**

CodeMentor AI is an AI-powered Java code review application that analyzes Java source code, identifies potential issues, explains them, and provides improvement suggestions.

- **Repo:** https://github.com/nazminsk67-hash/codementor-ai
- **Demo:** https://youtu.be/9M_q3gJaoVM
- **Article:** https://medium.com/@nazmin.sk67/building-codementor-ai-a-memory-powered-java-code-review-assistant-16592da7a1b0
- **Hindsight use:** deep · ~599 lines · 3 commits · licence: none (all rights reserved)

### dark-pattern-audit-agent — ByteForge · **70/80**

An AI-powered tool that audits websites for dark UX patterns using Hindsight (browser automation) and Groq (LLM analysis).

- **Repo:** https://github.com/sadamushasri22-maker/dark-pattern-audit-agent
- **Demo:** https://youtu.be/-em6rqQI6jM
- **Article:** https://dev.to/sadam_ushasri_c0b8dc3866b/when-a-fixed-dark-pattern-came-back-hindsight-remembered-40kp
- **Hindsight use:** deep · ~2,672 lines · 2 commits · licence: none (all rights reserved)

## Okay — 55–69/80 (30 projects)

### VIDHURA — EKAGRA · **69/80**

DevOps teams repeatedly investigate incidents with information scattered across previous incidents, postmortems, and troubleshooting records. Important experience is easy to lose between on-call rotations.

- **Repo:** https://github.com/yadavallicharishma3-art/VIDHURA
- **Demo:** https://youtu.be/JGQ5Cx3kddY
- **Article:** https://dev.to/a_m_b9b7101251fd2835f1cba/vidura-building-an-incident-response-agent-that-learns-from-every-post-mortem-3eb5
- **Hindsight use:** deep · ~589 lines · 1 commits · licence: none (all rights reserved)

### vendor-memory-agent — Ignite Minds · **69/80**

A negotiation-memory agent for procurement reps, built on Hindsight (Vectorize) for *Hack With Hyderabad 3.0*.

- **Repo:** https://github.com/Asma957/vendor-memory-agent
- **Demo:** https://youtu.be/FCwDft3s-PE
- **Article:** https://medium.com/@242p5a3203/why-your-procurement-ai-needs-to-forget-building-a-vendor-memory-agent-with-hindsight-the-problem-19719c8bb4d7
- **Hindsight use:** deep · ~808 lines · 5 commits · licence: none (all rights reserved)

### Lore-AI — Transformers · **69/80**

Lore AI is a content strategy agent that uses Hindsight to build a persistent memory of every post a creator has made — what they posted, what worked, what didn't, and how they talk to their audience. Instead of generati…

- **Repo:** https://github.com/pradhyuthmohan19/Lore-AI
- **Demo:** https://youtu.be/LJF0QtOvJhc
- **Article:** https://medium.com/@pradhyuthmohan/how-i-built-an-agent-that-learns-from-a-single-b38811104462
- **Hindsight use:** deep · ~1,289 lines · 4 commits · licence: none (all rights reserved)

### RecallDesk — TEAM HYDRA · **69/80**

RecallDesk is an AI-powered customer support agent that uses persistent memory to provide personalized support across multiple conversations.

- **Repo:** https://github.com/edunation07-cloud/RecallDesk
- **Demo:** https://youtu.be/o0AzXd3-xsk
- **Article:** https://medium.com/@edunation07/recalldesk-building-an-ai-customer-support-assistant-with-persistent-memory-3b9979d80043
- **Hindsight use:** deep · ~1,162 lines · 3 commits · licence: none (all rights reserved)

### meeting-prep-agent — Orangutan · **69/80**

An AI-powered meeting preparation assistant that generates personalized briefing documents for upcoming meetings. It uses Hindsight for long-term memory and Gemini for intelligent brief generation.

- **Repo:** https://github.com/shivatejakatikenapally/meeting-prep-agent
- **Demo:** https://youtu.be/PDoFnJRXBeQ
- **Article:** https://dev.to/katikenapally_shivateja/how-i-gave-my-meeting-agent-memory-with-hindsight-29ja
- **Hindsight use:** deep · ~833 lines · 4 commits · licence: none (all rights reserved)

### hackWithHyderabad — Akatsuki · **68/80**

An autonomous, decoupled SRE Incident Copilot that bridges real-time outage triage with institutional post-mortem memory, multi-project error tracking, and zero-pollution agentic IDE context generation.

- **Repo:** https://github.com/Gowthamsai-k/hackWithHyderabad
- **Article:** https://www.reddit.com/r/LLMDevs/comments/1wtfpii/onko_learn_from_the_past/
- **Hindsight use:** deep · ~2,860 lines · 23 commits · licence: none (all rights reserved)

### ADM — Sankalp · **68/80**

ADM (Adaptive Decision Memory) helps project and operations teams make vendor-selection decisions using organizational experience stored as persistent memory.

- **Repo:** https://github.com/dharanalakota/ADM
- **Demo:** https://youtu.be/VZ_McXHKPx0
- **Article:** https://parnikak.blogspot.com/2026/09/what-i-learned-turning-decision-memory.html
- **Hindsight use:** deep · ~8,116 lines · 1 commits · licence: none (all rights reserved)

### Recall-X — Neural Nexus · **67/80**

- A DECISION-SUPPORT system that remembers operational cause-and-effect across shifts.

- **Repo:** https://github.com/Pushpa-ravuri/Recall-X
- **Demo:** https://drive.google.com/file/d/1M75e5AtzFKveqx7B_tj-GOKE9yDCOiLX/view
- **Article:** https://dev.to/pushparavuri/i-let-hindsight-find-the-incidents-my-code-decides-which-ones-matter-1abj
- **Hindsight use:** solid · ~1,832 lines · 1 commits · licence: MIT License Copyrigh

### dealpilot — SuperNova · **67/80**

DealPilot is a memory-powered sales intelligence agent. It stores every sales interaction in Hindsight and recalls the right memories to brief you before your next meeting.

- **Repo:** https://github.com/gubbashruthika/dealpilot
- **Demo:** https://drive.google.com/file/d/1gelGcEL0mAWdKmYTiNH3rTEICazzot9q/view
- **Article:** https://docs.google.com/document/d/1lLqq-T0U7pUSMNAX6iUktKVI0IBddCu3/edit
- **Hindsight use:** deep · ~1,008 lines · 1 commits · licence: none (all rights reserved)

### memoryops-ai-incident-response — Yugma · **67/80**

MemoryOps is an AI incident-response platform that investigates production incidents using current operational evidence and persistent organizational memory through Hindsight.

- **Repo:** https://github.com/sriamsatwik2005/memoryops-ai-incident-response
- **Demo:** https://drive.google.com/file/d/1AMF2Ad3dJgNCgphO82nxtrvzhCZGYK9g/view
- **Article:** https://dev.to/sriram_satwik/i-gave-an-incident-agent-a-memory-with-hindsight-428g
- **Hindsight use:** deep · ~730 lines · 1 commits · licence: none (all rights reserved)

### LOGIMIND — Team AcadNexus · **66/80**

Turn operational data into decisions — and decisions into institutional memory with HINDSIGHT.

- **Repo:** https://github.com/24A31A42I5/LOGIMIND
- **Demo:** https://drive.google.com/file/d/1GXO5EXHeZGPMTKnXpiMMVsXCT9w2qzUS/view
- **Article:** https://medium.com/@kingsplash989/i-built-a-distributor-agent-that-remembers-what-went-wrong-849d766b1981
- **Hindsight use:** solid · ~2,580 lines · 3 commits · licence: none (all rights reserved)

### dealmemory — EDCO · **66/80**

Enterprise B2B SaaS sales representatives waste 40–60 minutes before every customer meeting re-reading fragmented CRM notes, call transcripts, email threads, and Slack messages. Crucial deal context is routinely forgotte…

- **Repo:** https://github.com/akolluru4211/dealmemory
- **Demo:** https://lnkd.in/p/dCtfvxbg
- **Article:** https://medium.com/@kolluruadarsh06/memory-is-not-a-bigger-prompt-building-a-deal-intelligence-agent-with-hindsight-b717cfe18eba
- **Hindsight use:** deep · ~9,387 lines · 4 commits · licence: none (all rights reserved)

### MemoLint — Waifu Pullers · **66/80**

Every AI code reviewer today has amnesia. It flags the same rejected nitpick on every PR, never learns that your team uses guard clauses, and has no idea that the pattern in this diff caused last month's outage. Memolint…

- **Repo:** https://github.com/WaifuPuller/MemoLint
- **Demo:** https://youtu.be/jWx0-Nl4BRk
- **Article:** https://dev.to/waifu_puller/hindsight-made-my-code-reviewer-stop-repeating-rejected-advice-5hmh
- **Hindsight use:** partial · ~3,366 lines · 29 commits · licence: MIT License

### CarbonTwin-OS — Kronos · **64/80**

CarbonTwin OS is an industrial AI and Digital Twin operating platform engineered for modern manufacturing plants and industrial facilities. It unifies high-frequency IoT telemetry streaming, physics-informed digital twin…

- **Repo:** https://github.com/tuhin-codes/CarbonTwin-OS
- **Demo:** https://drive.google.com/drive/folders/1d0iZUF0Zp3S-H6Ss_beBjwvZIWJZ75qq
- **Article:** https://fixtrace.hashnode.dev/fixtrace-building-an-ai-maintenance-agent-that-remembers-failures-using-hindsight
- **Hindsight use:** deep · ~67,092 lines · 1 commits · licence: none (all rights reserved)

### CodeMindAI — Tech titans · **64/80**

CodeMind reviews code with Groq and your team's enabled rules and Agent Memory. When Groq is not configured, the app stays usable with its local pattern checks.

- **Repo:** https://github.com/chinnadomasrinivas/CodeMindAI
- **Demo:** https://drive.google.com/file/d/1yCIbyZrJD3ApsiyGXHKYNaR7gqUm3k1I/view
- **Article:** https://drive.google.com/file/d/1zuFsYui5E9EGoy30nfEmx3vG5iZfnNma/view
- **Hindsight use:** deep · ~1,668 lines · 11 commits · licence: none (all rights reserved)

### Recall-AI-Customer-Support-Agent — SeriousBugKillers · **63/80**

An AI customer support agent that remembers previous interactions

- **Repo:** https://github.com/abdulmuqsith1/Recall-AI-Customer-Support-Agent
- **Demo:** https://youtu.be/QFgl4ZsFuco
- **Article:** https://drive.google.com/file/d/1lZzm6H9OMH1FFV0bJTi-b2D2y8y49ThW/view
- **Hindsight use:** solid · ~1,485 lines · 4 commits · licence: none (all rights reserved)

### userfeedback-hackathon — Runtime Rebels · **62/80**

- **Repo:** https://github.com/vignesh8009/userfeedback-hackathon
- **Demo:** https://drive.google.com/file/d/1uBrI3AAFw88dILhtDgYUKlCrw_xafxW9/view
- **Article:** https://www.linkedin.com/pulse/giving-customer-feedback-memory-building-intelligence-sumukh-thalla-kq7vf
- **Hindsight use:** deep · ~2,968 lines · 1 commits · licence: none (all rights reserved)

### VYRON — Chaar Log · **62/80**

- **Repo:** https://github.com/souriashritha11/VYRON
- **Demo:** https://drive.google.com/file/d/1PWmhEWaNeJhm4Ap1FMjYMI08xf31AkBA/view
- **Article:** https://www.reddit.com/r/aiagents/s/6frX1C7VJH
- **Hindsight use:** deep · ~3,502 lines · 5 commits · licence: none (all rights reserved)

### support-agent-live-memory — UPEKSHITAM · **62/80**

A customer support agent that remembers every customer's history. It uses Hindsight for long-term memory and Groq for fast LLM replies, with a browser dashboard that shows what the agent remembers in real time.

- **Repo:** https://github.com/kotasanthosh750/support-agent-live-memory
- **Demo:** https://www.youtube.com/watch
- **Article:** https://www.linkedin.com/feed/update/urn:li:activity:7510742970053074944/
- **Hindsight use:** deep · ~497 lines · 1 commits · licence: none (all rights reserved)

### AuditMind — CodeNova · **61/80**

AuditMind is an AI-powered compliance and audit assistant that uses persistent memory to remember previous audit findings, remediation actions, and control history.

- **Repo:** https://github.com/akshayavanga/AuditMind
- **Demo:** https://drive.google.com/file/d/1D3g7QTo6gyaNgeXDSS5f3BAPg0vqvOp-/view
- **Article:** https://drive.google.com/file/d/1OZXOpIxxQU9BtcxZyrLz6Cnzuy4PMYoY/view
- **Hindsight use:** deep · ~452 lines · 4 commits · licence: none (all rights reserved)

### Mnemo — Pentagoon · **60/80**

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

- **Repo:** https://github.com/syedasadiafatima182/Mnemo
- **Demo:** https://youtu.be/QmEF1mRErEw
- **Article:** https://syedasadiafatima.substack.com/p/beyond-retrieval-how-we-engineered
- **Hindsight use:** solid · ~871 lines · 1 commits · licence: none (all rights reserved)

### pr-memory-reviewer — TechNova · **60/80**

- Hindsight GitHub: https://github.com/vectorize-io/hindsight

- **Repo:** https://github.com/Lahari61111/pr-memory-reviewer
- **Demo:** https://youtu.be/dMeV4M0QLtA
- **Article:** https://dev.to/jyothisri_laveti_3ba6a948/my-hindsight-code-reviewer-kept-enforcing-a-dead-rule-i0j
- **Hindsight use:** partial · ~323 lines · 8 commits · licence: none (all rights reserved)

### RecallOps-Hindsight-Agent — BUG HUNTERS · **59/80**

RecallOps is an AI incident-response assistant that remembers previous production incidents, recalls relevant experience, and uses those lessons to make future troubleshooting more targeted.

- **Repo:** https://github.com/sairam823/RecallOps-Hindsight-Agent
- **Demo:** https://drive.google.com/file/d/1-OZY8AyoMhM1Lmktf-zk3M9a4t2JvZea/view
- **Article:** https://www.linkedin.com/pulse/recallops-building-ai-incident-response-agent-learns-from-shriram-0xjic
- **Hindsight use:** deep · ~433 lines · 1 commits · licence: MIT License

### nexus — Code warriors team · **59/80**

Every incident becomes experience. Every experience improves the next decision.

- **Repo:** https://github.com/Abhinayasrija/nexus
- **Demo:** https://drive.google.com/drive/u/2/home
- **Article:** https://drive.google.com/drive/u/2/my-drive
- **Hindsight use:** deep · ~1,186 lines · 3 commits · licence: none (all rights reserved)

### RecallOps-AI-Incident-Response — Hackers · **59/80**

- **Repo:** https://github.com/Gayathriui/RecallOps-AI-Incident-Response
- **Demo:** https://drive.google.com/file/d/1v-9w9ee5kFEt8vwSvp_s_8pB5Xf6Kgba/view
- **Article:** https://medium.com/@23251a1220akshaya/recallops-giving-ai-persistent-memory-for-incident-response-d870ef023fae
- **Hindsight use:** deep · ~576 lines · 1 commits · licence: none (all rights reserved)

### 1BWqWpKoFKe3r1kUbMX1P4CWBb7GTJgiy — Chakravyuha · **59/80**

A runnable implementation of the incident-response workflow shown in the supplied demo video.

- **Repo:** https://drive.google.com/drive/folders/1BWqWpKoFKe3r1kUbMX1P4CWBb7GTJgiy
- **Demo:** https://youtu.be/r-UEoVsIuWA
- **Article:** https://dev.to/boini_chandana_f3b4d0bbde/ai-incident-response-agentpowered-by-hindsight-11h3
- **Hindsight use:** deep · ~252 lines · 0 commits · licence: none (all rights reserved)

### AI_sre — MISSION M · **57/80**

RunbookMind is an intelligent AI Site Reliability Engineering (SRE) platform designed to automatically analyze high-severity incident alerts, search log snippets & deployment histories, generate root cause hypotheses, an…

- **Repo:** https://github.com/M0h1tkumar/AI_sre
- **Demo:** https://youtu.be/02nsGigd_5g
- **Article:** https://dev.to/mohit_kumar_e3775f1988373/hindsight-taught-my-sre-agent-to-stop-repeating-failed-fixes-1jde
- **Hindsight use:** solid · ~1,150 lines · 1 commits · licence: none (all rights reserved)

### feedback-intelligence-agent — TechNova · **57/80**

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

- **Repo:** https://github.com/likhithamadupu-netizen/feedback-intelligence-agent
- **Demo:** https://drive.google.com/file/d/1xYzO_65YMKFkeqjyNcw30U-tIMMEYJAe/view
- **Article:** https://ieeexplore.ieee.org/document/11078280
- **Hindsight use:** partial · ~3,846 lines · 2 commits · licence: none (all rights reserved)

### MarkSight — Bharat Nextgen · **57/80**

MarkSight is an autonomous AI marketing agent powered by long-term Hindsight Memory. Unlike traditional generative AI tools that produce disconnected one-off answers and immediately forget past outcomes, MarkSight contin…

- **Repo:** https://github.com/nixauraa/MarkSight
- **Demo:** https://youtu.be/RURMwEtqfbc
- **Article:** https://dev.to/nikitha_5543f5631ada30b52/how-i-built-a-marketing-memory-loop-with-hindsight-4mgl
- **Hindsight use:** light · ~1,596 lines · 1 commits · licence: none (all rights reserved)

### Competitive-Intelligence-Agent — INNOV8 · **56/80**

An autonomous, executive-grade Competitive Intelligence (CI) system built with Streamlit, Groq, and the Hindsight SDK.

- **Repo:** https://github.com/Sai-Venkat-Maharajula-2006/Competitive-Intelligence-Agent
- **Demo:** https://youtu.be/ylrzBvU2A6s
- **Article:** https://www.linkedin.com/pulse/architecting-autonomous-competitive-intelligence-engine-m-sai-venkat-yyl4f
- **Hindsight use:** partial · ~429 lines · 4 commits · licence: none (all rights reserved)

---
Scoring rubric (/80): Hindsight integration 30 · complete & working (code + demo) 20 · problem/usefulness 10 · documentation 10 · code quality 10.