<div align="center">

# 👨‍💻 Nico Wittemann

### AI Developer · Multi-Agent Systems · AI Automation · Python Engineering

I build AI-supported systems that turn messy inputs into structured workflows.

<p>
  <img src="https://img.shields.io/badge/AI%20Developer-111111?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multi--Agent%20Systems-5B2EFF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI%20Automation-7A3FE4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python%20Engineering-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nico%20Wittemann-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nico-wittemann)
![Focus](https://img.shields.io/badge/Focus-Agentic%20AI%20%26%20Automation-5B2EFF?style=flat)
![Location](https://img.shields.io/badge/Based%20in-Germany-222222?style=flat)

</div>

---

## 🧠 What I Build

I work on **AI-supported software systems**, **multi-agent workflows**, **LLM-based automation**, and backend systems that connect AI with real business processes.

My focus is not just “chat with a model”.  
I care about systems that can:

- classify messy input
- extract relevant information
- prepare structured outputs
- connect APIs and tools
- support internal workflows
- reduce repetitive manual work
- keep humans in control where decisions matter

Before moving into software, I worked in **industrial automation** as a PLC programmer. That background still shapes how I build today: structured, process-oriented, reliable, and focused on systems that work in the real world — not just in demos.

> Most of my current AI automation and multi-agent work is part of professional or private projects and is not fully open source.  
> My public repositories show selected foundations in backend development, API design, automation logic, structured data processing, and AI integration.

---

## 🧭 AI System Architecture Mindset

```mermaid
flowchart LR
    subgraph INPUT["📥 Input Layer"]
        A1["Emails"]
        A2["Documents"]
        A3["Forms"]
        A4["Unstructured Text"]
    end

    subgraph UNDERSTANDING["🧠 AI Understanding Layer"]
        B1["Classification"]
        B2["Information Extraction"]
        B3["Context Matching"]
        B4["Validation"]
    end

    subgraph STRUCTURE["📊 Structured Output Layer"]
        C1["JSON Output"]
        C2["Detected Fields"]
        C3["Missing Information"]
        C4["Risk / Priority Signals"]
    end

    subgraph WORKFLOW["⚙️ Workflow Layer"]
        D1["Routing Logic"]
        D2["API Actions"]
        D3["Draft Preparation"]
        D4["Next Step Suggestion"]
    end

    subgraph CONTROL["👤 Human Control Layer"]
        E1["Review"]
        E2["Decision"]
        E3["Send / Approve"]
    end

    subgraph OBSERVE["📡 Observability Layer"]
        F1["Tracing"]
        F2["Debugging"]
        F3["Quality Checks"]
        F4["Feedback Loops"]
    end

    INPUT --> UNDERSTANDING
    UNDERSTANDING --> STRUCTURE
    STRUCTURE --> WORKFLOW
    WORKFLOW --> CONTROL
    WORKFLOW --> OBSERVE
    OBSERVE --> UNDERSTANDING

    classDef input fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#ffffff;
    classDef ai fill:#1e1b4b,stroke:#a78bfa,stroke-width:2px,color:#ffffff;
    classDef output fill:#052e2b,stroke:#34d399,stroke-width:2px,color:#ffffff;
    classDef workflow fill:#1c1917,stroke:#f59e0b,stroke-width:2px,color:#ffffff;
    classDef human fill:#3f1d2b,stroke:#fb7185,stroke-width:3px,color:#ffffff;
    classDef observe fill:#111827,stroke:#60a5fa,stroke-width:2px,color:#ffffff;

    class A1,A2,A3,A4 input;
    class B1,B2,B3,B4 ai;
    class C1,C2,C3,C4 output;
    class D1,D2,D3,D4 workflow;
    class E1,E2,E3 human;
    class F1,F2,F3,F4 observe;
```

<div align="center">

**From messy input to structured action — with AI preparing the workflow and humans staying in control.**

</div>

---

## 🚀 Current Focus

<table>
  <tr>
    <td><b>🤖 Multi-Agent Systems</b></td>
    <td>Agent-based workflows, task decomposition, tool usage, structured outputs, and workflow orchestration</td>
  </tr>
  <tr>
    <td><b>⚙️ AI Automation</b></td>
    <td>Email workflows, internal process automation, classification, routing, and response preparation logic</td>
  </tr>
  <tr>
    <td><b>🧠 LLM Workflows</b></td>
    <td>Prompt structures, output validation, RAG-style context usage, and JSON-first responses</td>
  </tr>
  <tr>
    <td><b>🔌 API Integrations</b></td>
    <td>Backend services, authentication, external APIs, and workflow automation</td>
  </tr>
  <tr>
    <td><b>🔐 Privacy-Conscious AI</b></td>
    <td>Local AI models, cloud-vs-local tradeoffs, data protection aware implementation</td>
  </tr>
  <tr>
    <td><b>📊 Observability</b></td>
    <td>Tracing, debugging, monitoring, and quality checks for AI-supported workflows</td>
  </tr>
  <tr>
    <td><b>🧰 Agentic Development</b></td>
    <td>Claude Code, Codex, MCP integrations, AI-assisted engineering, and structured development workflows</td>
  </tr>
</table>

---

## 🛠️ Tech Stack

### Core Engineering

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20APIs-009688?style=flat"/>
</p>

### AI, Agents & Automation

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat"/>
  <img src="https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-Model%20Context%20Protocol-5B2EFF?style=flat"/>
  <img src="https://img.shields.io/badge/AI%20Agents-111111?style=flat"/>
  <img src="https://img.shields.io/badge/Multi--Agent%20Systems-5B2EFF?style=flat"/>
  <img src="https://img.shields.io/badge/LLM%20Workflows-000000?style=flat"/>
  <img src="https://img.shields.io/badge/AI%20Automation-7A3FE4?style=flat"/>
  <img src="https://img.shields.io/badge/Local%20AI%20Models-2E8B57?style=flat"/>
</p>

### Backend, Auth, Observability & Tools

<p>
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat"/>
  <img src="https://img.shields.io/badge/Logfire-FF6B35?style=flat"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/API%20Design-222222?style=flat"/>
  <img src="https://img.shields.io/badge/Workflow%20Automation-5B2EFF?style=flat"/>
</p>

---

## 🔒 Private & Professional AI Work

A large part of my current AI and automation work is not public source code.

This includes professional and private work around AI-supported systems that connect language models with real business workflows, APIs, internal tools, authentication flows, observability, and human review steps.

Current areas I work on:

- 🤖 Multi-agent systems for complex internal workflows
- ⚙️ AI-supported automation for service, operations, and customer communication
- 📩 Email-based classification, routing, and response preparation
- 🧠 LLM workflows with structured outputs, validation logic, and tool usage
- 🔌 API integrations, authentication flows, and backend automation
- 🔐 Privacy-conscious AI implementation with cloud and local model setups
- 📊 Observability and debugging for AI-supported workflows
- 🧰 Agentic development workflows using Claude Code, Codex, MCP, and custom tool patterns

The code for these systems is not public because it is connected to professional work, private business logic, product development, or internal workflows.

This profile shows the technical direction without exposing private repositories, customer data, internal company systems, or production logic.

---

## 🧪 Independent AI Automation Project

### AI Complaint Intake Copilot  
Private codebase · Demo / product prototype

I am building a private AI automation project focused on complaint intake workflows for B2B companies.

The system is designed to turn incoming complaint emails and related information into structured case outputs:

- case summary
- detected customer and product information
- missing information checklist
- prepared customer reply draft
- internal next step for the service team
- human review before any final response is sent

The goal is not to replace human decision-making.  
The goal is to reduce manual preparation work, structure messy incoming communication, and help teams respond faster with better context.

Technical direction:

- Python / FastAPI backend
- React-based demo interface
- LLM-based extraction and classification
- structured JSON outputs
- email workflow automation
- draft preparation logic
- privacy-conscious human-in-the-loop design

The repository is private because it contains product logic, implementation details, and business-specific workflow design.

---

## 🧩 Public Foundation Project

### 🖥️ Django PC Webshop Backend  
Backend API for configuring custom PCs with structured product data, authentication, order logic, payment handling, and AI-supported recommendations.

This is an older public project, but it shows several foundations that still matter in my current work: backend architecture, API design, data modeling, external integrations, payment flows, and AI integration.

**Key parts:**

- Django REST API with JWT authentication, product catalog, order management, and PostgreSQL
- GPT-4o integration for PC build suggestions based on budget and intended use
- CSV-based data import and filtering logic for structured component data
- Stripe payment flow and webhook handling
- Swagger API documentation and deployment-oriented configuration

**Tech Stack:**  
Python · Django REST Framework · PostgreSQL · JWT · Stripe · GPT-4o · Render

🔗 [GitHub Repository](https://github.com/nico-wittemann/django_pc_webshop_api)

---

## 🧬 AI Workflow Blueprint

```mermaid
sequenceDiagram
    autonumber
    participant U as User / Incoming Request
    participant API as Backend API
    participant ORCH as Workflow Orchestrator
    participant LLM as LLM / Agent Layer
    participant CTX as Context / Tools
    participant OBS as Observability
    participant H as Human Review

    U->>API: Submit messy input
    API->>ORCH: Normalize request
    ORCH->>LLM: Classify + extract information
    LLM->>CTX: Use context, tools, or rules
    CTX-->>LLM: Return relevant signals
    LLM-->>ORCH: Structured JSON output
    ORCH->>OBS: Trace result + quality signals
    ORCH->>H: Prepare draft / next step
    H-->>U: Review, decide, send
```

---

## 🧠 How I Think About AI Systems

<table>
  <tr>
    <td><b>Bad AI implementation</b></td>
    <td>Chatbot on top of a broken process</td>
  </tr>
  <tr>
    <td><b>Good AI implementation</b></td>
    <td>Structured system that understands input, prepares action, and supports human decisions</td>
  </tr>
  <tr>
    <td><b>My preferred direction</b></td>
    <td>AI as workflow infrastructure: extraction, classification, routing, drafting, validation, observability</td>
  </tr>
</table>

Useful AI is not just a chatbot.

Useful AI connects to real workflows.  
It understands messy input, extracts what matters, prepares the next step, and keeps the human in control where judgment matters.

That is the direction I focus on when building software:

<div align="center">

**clear system design · practical automation · reliable implementation · real process value**

</div>

---

## 📊 Public GitHub Snapshot

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nico-wittemann&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nico-wittemann&layout=compact&theme=tokyonight&hide_border=true" />

</div>

---

## 🤝 Connect

I’m interested in practical AI, automation, multi-agent systems, backend engineering, and software that creates real workflow value.

<p>
  <a href="https://www.linkedin.com/in/nico-wittemann">
    <img src="https://img.shields.io/badge/LinkedIn-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>
