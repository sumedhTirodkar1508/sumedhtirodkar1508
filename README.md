<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/bento-dark.svg" />
  <img src="./assets/bento-light.svg" alt="Sumedh Tirodkar: Full Stack Software Engineer | Software Development Engineer" width="100%" />
</picture>

## ✦ About

I build full-stack applications—architecting React and Next.js frontends, designing PostgreSQL schemas with row-level security, and integrating OAuth flows that protect over **1 million** records. At the University of Maryland I reduced page load latency by **35%** and query execution time by **65%** through schema redesign and indexing. Before that, I engineered backend services at Reliance Jio that automated tax compliance for **20,000+** users, cutting submission time by **70 minutes** per person.

## ✦ Selected work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| **onespec** | Compiles one JSON Schema into TypeScript types, client and server validators, and PostgreSQL check constraints | Property-based tests prove all three layers agree | TypeScript, JSON Schema, Ajv, PostgreSQL, Vitest, fast-check |
| **sessionprops** | Expresses session security as invariants and checks them with stateful property-based testing | Generates and shrinks adversarial login, elevate, rotate, and logout sequences | TypeScript, Express, Redis, Vitest, fast-check |
| **schemadrift** | GraphQL breaking-change gate that downgrades severity using real field-usage telemetry | GitHub Action posts annotated PR comments naming clients that still call removed fields | TypeScript, GraphQL.js, Node.js CLI, Vitest, GitHub Actions |
| **gatekeep** | BeyondCorp-style identity-aware reverse proxy with OIDC and PKCE | Device posture assertions, CEL policies, encrypted sessions, and hash-chained audit log | Go, OpenID Connect, PKCE, JWKS, AES-256-GCM, EdDSA ES256, CEL |
| **Project Pluto** | Real-time data streaming application capturing live market data from browser sessions | Delivers streaming updates to Next.js frontend with reliable browser automation and failure recovery | TypeScript, Node.js, Playwright, ConnectRPC, Protobuf, Next.js |
| **NeuroPanel** | Chrome extension and backend platform for multilingual audio capture and transcription | Achieved over **95%** transcription reliability, reducing manual note-taking | React, Vite, TypeScript, Next.js, PostgreSQL, Prisma, JWT, Gemini AI, NextAuth |

<details>
<summary>onespec, in depth</summary>

</details>

<details>
<summary>sessionprops, in depth</summary>

</details>

## ✦ AI / ML work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| **[driftguard](https://github.com/sumedhTirodkar1508/driftguard)** | End-to-end ML lifecycle that trains, registers in MLflow, serves with FastAPI, detects drift and retrains itself | Caught concept drift (PSI **0.223**) that feature monitoring missed; retraining cut held-out MAE by **44.6%** | Python, scikit-learn, MLflow, FastAPI, SciPy, Docker |
| **[AI-SOC](https://github.com/sumedhTirodkar1508/ai_soc)** | AI-augmented security operations center with local LLM triage, RAG over MITRE ATT&CK and ML flow classification | **193** offline tests passing; p95 inference **378 ms**; role-based analyst review and dry-run responses | Python, FastAPI, Ollama, ChromaDB, XGBoost, PostgreSQL, Docker |
| **[Email Phishing Detector](https://github.com/sumedhTirodkar1508/email-phishing-detection)** | Analyzes .eml/.msg headers, body and attachments, checks VirusTotal and asks an AI model for a verdict | Concurrent asyncio analysis, SPF/DKIM/DMARC parsing, typosquat detection, OCR, 0–10 phishing score | Python, asyncio, aiohttp, SQLite, Tesseract OCR, LLM API |
| **[Fraud Detection](https://github.com/sumedhTirodkar1508/fraud-detection-in-python)** | Compares five classifiers on **594,643** synthetic BankSim transactions with a 1.2% fraud class | Naive Bayes **0.9993** recall; decision tree **0.9027** precision | Python, pandas, scikit-learn, Jupyter |
| **[NLP Text Analysis](https://github.com/sumedhTirodkar1508/text-analysis-using-nlp-streamlit)** | Streamlit app for text or PDF/DOCX/TXT uploads: tokens, POS, lemmas, entities, sentiment, word cloud | Two analysis modes with CSV export of the token table | Python, spaCy, TextBlob, Streamlit, pandas |

## ✦ Experience

| Period | Role | Company | Highlights |
|--------|------|---------|------------|
| *Aug 2024 – Present* | Research Assistant - Software Developer | University of Maryland, USA | Reduced page load latency by **35%** and query time by **65%** through schema redesign, indexing, and API optimization; secured **1M+** records with PostgreSQL RLS; cut deployment time from **30 minutes** to **4 minutes** with GitHub Actions. |
| *Aug 2023 – Dec 2024* | Teaching Assistant - Graduate Programming | University of Maryland, USA | Conducted labs and debugging sessions for **150+** students; automated evaluation of **200+** weekly submissions with PyTest, JUnit, and Docker; earned **4.9/5** instructor rating. |
| *Aug 2019 – Jul 2023* | Software Development Engineer | Reliance Jio Platforms Limited | Engineered backend services for **20,000+** users, reducing tax submission time by **70 minutes** per user; coordinated API gateway onboarding across **5+** teams; reduced MTTR by **30%** through log analysis and monitoring. |

## ✦ Credentials

### Education
- **Master of Science**, Information Technology – *University of Maryland, College Park* (*Aug 2023 – Dec 2024*)
- **Bachelor of Engineering**, Electronics and Telecommunication – *University of Mumbai* (*Jul 2015 – Jun 2019*)

## ✦ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,py,js,ts,go,html,bash,react,nextjs,spring,nodejs,express,django,fastapi,postgres,mysql&theme=dark&perline=8" alt="java, py, js, ts, go, html, bash, react, nextjs, spring, nodejs, express, django, fastapi, postgres, mysql" />
</p>

<p align="center"><a href="mailto:sumedhtirodkar15@gmail.com"><b>Email</b></a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/sumedh-tirodkar/"><b>LinkedIn</b></a> &nbsp;·&nbsp; <a href="https://github.com/sumedhTirodkar1508"><b>GitHub</b></a></p>

## ✦ Projects

- [driftguard](https://github.com/sumedhTirodkar1508/driftguard) — Self-monitoring ML lifecycle: MLflow registry, FastAPI serving, PSI/KS drift detection and automatic retraining, evaluated on held-out data.
- [ai_soc](https://github.com/sumedhTirodkar1508/ai_soc) — AI-augmented SOC with local LLM triage, RAG over MITRE ATT&CK, ML flow classification, analyst review and Sigma rule export.
- [email-phishing-detection](https://github.com/sumedhTirodkar1508/email-phishing-detection) — Phishing analysis for .eml/.msg files with header, body and attachment checks, VirusTotal lookups, OCR and an AI verdict.
- [fraud-detection-in-python](https://github.com/sumedhTirodkar1508/fraud-detection-in-python) — Five scikit-learn classifiers compared for transaction fraud on 594,643 synthetic BankSim payments.
- [text-analysis-using-nlp-streamlit](https://github.com/sumedhTirodkar1508/text-analysis-using-nlp-streamlit) — Streamlit NLP app for tokens, POS, entities, sentiment and word clouds from text or PDF/DOCX/TXT files.
- [onespec](https://github.com/sumedhTirodkar1508/onespec) — One JSON Schema compiles into TypeScript types, client and server validators and PostgreSQL check constraints, with property-based tests proving all three…
- [sessionprops](https://github.com/sumedhTirodkar1508/sessionprops) — Session security expressed as invariants and checked with stateful property-based testing that generates and shrinks adversarial login, elevate, rotate and…
- [schemadrift](https://github.com/sumedhTirodkar1508/schemadrift) — A GraphQL breaking-change gate that downgrades severity using real field-usage telemetry, naming the client that still calls a removed field, with a GitHub…
- [originbound](https://github.com/sumedhTirodkar1508/originbound) — A sealed lab where one relay attack succeeds against TOTP and fails against WebAuthn, with the clientDataJSON origin field shown as the cause.
- [tokenforge](https://github.com/sumedhTirodkar1508/tokenforge) — One design-token source of truth, forged into Tailwind, CSS variables (light/dark/high-contrast), and typed TS — with a WCAG contrast gate that fails CI before…
- [gatekeep](https://github.com/sumedhTirodkar1508/gatekeep) — A BeyondCorp-style identity-aware reverse proxy in Go with OIDC and PKCE, device posture assertions, CEL policies, encrypted sessions and a hash-chained audit…
- [contextlens](https://github.com/sumedhTirodkar1508/contextlens) — Engineers waste significant time re-deriving why code is written a certain way — the tribal knowledge lives in PR comments and commit messages disconnected…
- [stridediff](https://github.com/sumedhTirodkar1508/stridediff) — Architecture-as-code tool that computes a STRIDE threat delta on every pull request and fails CI when a new trust-boundary crossing has no recorded mitigation.
- [dmarcwatch](https://github.com/sumedhTirodkar1508/dmarcwatch) — Email deliverability monitoring that parses DMARC aggregate XML reports to separate mail that never arrived from mail that arrived and was ignored, and flags…
- [adrlint](https://github.com/sumedhTirodkar1508/adrlint) — A decision-record linter that builds a graph of architecture decisions and flags unresolved contradictions, expired reviews and orphaned supersedes chains.
