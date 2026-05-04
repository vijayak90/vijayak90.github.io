# Vijayalakshmi (Vijaya) Karthikeyan
**AI Product Builder | Agentic AI Architect | Enterprise Solution Strategist**

📍 Bangalore | vijayak90@gmail.com |[Portfolio](https://vijayak90.github.io) | [LinkedIn](https://linkedin.com/in/vijayalakshmikarthikeyan)

## What I Build
- I design and build agentic AI systems using AI-native tooling — translating enterprise product thinking directly into working solutions. 
- 12+ years of enterprise experience across Alteryx, Merck-MSD, Informatica, and Oracle informs every architectural decision I make.

## Connexa — Architecture Deep Dive

--> An intelligent multi-agentic AI chatbot built to enterprise production standards.

### Agent Topology

| Agent | Responsibility | LLM Used | Why |
|---|---|---|---|
| Churn Prediction | Analyses customer signals, flags at-risk accounts | Claude API | Better reasoning on nuanced behavioural patterns |
| Fraud Detection | Scans interaction patterns for anomalies | OpenAI GPT-4o | Stronger classification on structured pattern data |
| Retention Personalisation | Generates tailored intervention messages | Claude API | Superior instruction-following for tone control |
| Quality Evaluation | Scores every agent output against rubric | OpenAI GPT-4o | Consistent structured JSON output |
| Conversational AI | Handles live customer queries end-to-end | Claude API | More natural, context-aware conversation |

### Key Architecture Decisions

**RAG Pipeline:** LangChain for customization + Supabase for vector storage  
*Why Supabase over Pinecone:* Lower latency for our query volume, simpler operational overhead, and combined relational + vector capability in one database reduced infrastructure complexity.

**Workflow Automation:** n8n Cloud (109 nodes)  
*Why n8n:* Native webhook support, visual debugging, and direct API integration without code overhead — ideal for agentic workflow orchestration.

**Security Architecture (5 layers):**
1. Input sentinel — 30+ adversarial pattern detection before any LLM call
2. Prompt hardening — system prompt injection resistance
3. Output sanitisation — PII scrubbing before any response leaves the system
4. Inter-agent validation — each agent's output is validated before passing downstream
5. Automated red-team testing — adversarial test suite run on every deployment

Compliance: OWASP LLM Top 10 | MITRE ATLAS | DPDPA | Responsible AI

### What Was A/B Tested Before Committing
- OpenAI vs Claude per agent use case — different models per agent based on output quality
- Pinecone vs Supabase — Supabase selected based on latency benchmarks and cost
- RAG chunk sizes — tested 256, 512, 1024 token chunks for retrieval relevance
- Prompt configurations — 5 variants per agent tested before production configuration

## Research Projects

**ISB Cybersecurity for Leaders (2025)** — AI & Cybersecurity Strategy for BackHome Solutions - An RTI-based Startup Solution
Research on GenAI, IoT, and blockchain security implications for enterprise.  
Output: Zero-trust architecture framework + AI-era cybersecurity team playbook

**SMU Product Management (2025)** — Tech-Enabled Food Court Experience  
Led the full design thinking cycle.  
Output: PRD + product roadmap + 5 prioritised value propositions.  

## Technical Stack

**Agentic AI:** LangChain; n8n; OpenAI API; Claude API; AutoGen; RAG Pipelines  
**Vector DBs:** Supabase; Pinecone
**AI Dev Tools:** Cursor;  Lovable; Replit; GitHub Copilot  
**Cloud:** Azure; AWS; GCP; Snowflake; BigQuery  
**Data & Integration:** Python; SQL; REST APIs; Salesforce; ServiceNow; 50+ Enterprise Connectors
**Security:** OWASP LLM Top 10; MITRE ATLAS; Prompt Injection Defense; DPDPA
**Product:** Aha Roadmaps; Asana; JIRA; Confluence; Miro; Figma AI; Agile

## Career Summary

| Period | Role | Company |
|---|---|---|
| Apr 2024 – Present | AI Product Builder & Researcher | Self-directed |
| Apr 2022 – Mar 2024 | Principal Support Engineer — APAC | Alteryx, Singapore |
| Jan 2021 – Mar 2022 | Senior Customer Support Engineer | Alteryx, Singapore |
| Nov 2019 – Jan 2021 | Customer Support Engineer | Alteryx, Singapore |
| Sep 2017 – Oct 2019 | Independent ML Practitioner | Self-directed |
| Apr 2016 – Sep 2017 | MDM Analyst — Data Architect | Merck-MSD, Singapore |
| Jun 2012 – Jan 2016 | Technical Support Engineer | Informatica, Bengaluru |

---

## Recognition

★ MVP Award — Alteryx (first support engineer recipient, previously sales-exclusive)  
★ Alteryx Xcellence Award  
★ Merck Excellence Award  
★ Innovation Day Global Runner-Up — 75 teams, Redwood City, CA (Informatica)  
★ Mercury Team Player Award — Vienna

---

*Open to work · Bangalore · Available immediately*  
*Full portfolio and project details: [vijayak90.github.io](https://vijayak90.github.io)*
