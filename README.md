<div align="center">

# Hey, I'm Arnav 👋
### `hackers-reality`

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=800&color=00F5FF&center=true&vCenter=true&width=900&lines=I+build+AI+that+does+things%2C+not+just+talks.;Agents+%E2%86%92+Tools+%E2%86%92+Verification+%E2%86%92+Action;Context+engineering+is+part+of+the+system.;Build.+Break.+Inspect.+Improve.+Repeat." alt="Typing introduction" />

<br/>

<img src="https://komarev.com/ghpvc/?username=hackers-reality&style=for-the-badge&color=blueviolet" alt="Profile views" />
<img src="https://img.shields.io/badge/Focus-Agentic%20AI-00C2FF?style=for-the-badge" alt="Agentic AI" />
<img src="https://img.shields.io/badge/Mode-Building-00C853?style=for-the-badge" alt="Building" />

### `context → reason → plan → delegate → execute → verify → self-correct → continue`

</div>

---

## 🧠 I build systems that act

I build **autonomous AI agents, developer tools, automation-heavy systems and full-stack products**.

I'm less interested in another chatbot wrapper and more interested in what happens **after the first model response**: context, memory, tools, permissions, orchestration, parallel workers, verification loops and the engineering required to let an agent keep moving without turning autonomy into chaos.

A strong model helps. But the system around it determines how much of that intelligence survives contact with a real task.

```mermaid
graph LR
    A[Objective] --> B[Context]
    B --> C[Reason + Plan]
    C --> D{Delegate?}
    D -->|Yes| E[Parallel Agents]
    D -->|No| F[Execute]
    E --> F
    F --> G[Use Tools]
    G --> H[Verify]
    H --> I{Correct?}
    I -->|No| J[Self-Correct]
    J --> C
    I -->|Yes| K[Ship + Continue]
```

---

## 🤖 Flagship — [FRIDAY](https://github.com/hackers-reality/friday)

> **A Windows-native autonomous AI agent built around observation, memory, tools, delegation and action.**

FRIDAY is my largest agentic-system project: voice and live audio, screen awareness, desktop/browser automation, persistent memory, goals and productivity enforcement, communications, model routing, multi-agent delegation, parallel sub-agents, research workflows, scheduling, GitHub integration, self-modification, sidecar networking, dashboards and more.

The interesting question isn't *“can an LLM answer me?”* It's:

**Can a personal AI observe its environment, remember what matters, choose tools, coordinate work, verify itself and actually finish things?**

```mermaid
graph TD
    U[User / Goal] --> F[FRIDAY Core]
    F --> M[Memory + Context]
    F --> R[Reasoning + Planning]
    F --> T[Tool Router]
    F --> A[Agent Orchestration]
    T --> D[Desktop]
    T --> W[Browser / Web]
    T --> C[Communications]
    T --> G[GitHub + Dev Tools]
    A --> P1[Worker Agent]
    A --> P2[Research Agent]
    A --> P3[Parallel Sub-agents]
    M --> V[Verification Loop]
    R --> V
    D --> V
    W --> V
    C --> V
    G --> V
    P1 --> V
    P2 --> V
    P3 --> V
    V -->|Needs correction| F
    V -->|Done| O[Action / Result]
```

**→ [Explore FRIDAY](https://github.com/hackers-reality/friday)**

---

## 🚀 Selected builds

| Project | What it represents |
|---|---|
| 💹 **[FinIntel](https://github.com/hackers-reality/FinIntel)** | AI-assisted financial intelligence and analysis experiments. |
| 🎌 **[NexAnime](https://github.com/hackers-reality/NexAnime)** | Product/full-stack engineering on the application side of my work. |
| 🖥️ **[NexCli](https://github.com/hackers-reality/NexCli)** | CLI tooling and developer experimentation — because apparently GUIs weren't enough trouble. |
| 📚 **[JEE Prep](https://github.com/hackers-reality/JEE-prep)** | Applying software engineering to learning and preparation. |

### 🏁 The early builds

**[EmoBoost](https://github.com/hackers-reality/EmoBoost-1021)** and **[Innovation Challenge](https://github.com/hackers-reality/innovatiochallenge_3011)** are among my first repositories and were built for competitions. They aren't here because they're my most advanced work; they're here because they show where the trajectory started.

```mermaid
graph LR
    A[Competition Builds] --> B[Product Experiments]
    B --> C[Developer Tools]
    C --> D[Full-Stack Systems]
    D --> E[Autonomous Agents]
    E --> F[FRIDAY]
```

> This profile is curated. Some repositories on the account are forks, references, experiments or old work; I don't pretend every repo under an account is something I authored. Revolutionary concept, apparently. 😭

---

## ⚙️ Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,html,css,react,nextjs,nodejs,git,github,linux,bash,docker,vscode,mysql&perline=8" alt="Technology icons" />

</div>

### Things I keep going too far into

`LLM Agents` · `Context Engineering` · `Prompt Engineering` · `Tool Calling` · `Multi-Agent Systems` · `Automation` · `Research Workflows` · `Full-Stack Architecture` · `APIs` · `Authentication` · `Databases`

---

## 🧩 How I think about agent engineering

```mermaid
graph TD
    MODEL[Model] --> ORCH[Orchestration]
    CONTEXT[Context] --> ORCH
    MEMORY[Memory] --> ORCH
    TOOLS[Tools] --> ORCH
    RULES[Permissions + Guardrails] --> ORCH

    ORCH --> PLAN[Plan]
    PLAN --> EXEC[Execution]
    PLAN --> DELEGATE[Parallel Delegation]
    DELEGATE --> EXEC
    EXEC --> CHECK[Verification]
    CHECK -->|Failed| REPAIR[Self-Correction]
    REPAIR --> PLAN
    CHECK -->|Passed| DONE[Continue / Ship]
```

The model is a component, not the whole architecture.

My favorite engineering loop is giving an agent a real objective, enough context to understand the system, permission to inspect its environment, the ability to delegate when useful, and one non-negotiable rule: **verify what you built before claiming you're done.**

---

## 🔬 Portfolio + laboratory

GitHub for me is both. Some repositories are polished projects; others are prototypes, experiments and evidence of an idea arriving at an unreasonable hour.

```mermaid
graph LR
    IDEA[Idea] --> PROTO[Prototype]
    PROTO --> BUILD[Build too much]
    BUILD --> BREAK[Break something]
    BREAK --> DEBUG[Understand why]
    DEBUG --> IMPROVE[Improve the system]
    IMPROVE --> BUILD
    BUILD -->|Eventually| SHIP[Ship]
```

The mess is useful. You can see the progression instead of only the finished screenshot.

---

## 📊 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hackers-reality&theme=tokyo-night&hide_border=true&area=true" alt="hackers-reality contribution activity graph" />

</div>

<details>
<summary><b>Why only one external stats graphic?</b></summary>
<br/>

Profile README widgets are convenient until somebody else's endpoint has a bad day and your portfolio suddenly develops broken-image icons. The architecture diagrams above are native GitHub Mermaid instead; the activity graph stays because it communicates something GitHub Markdown cannot generate by itself.

</details>

---

<div align="center">

### `BUILD → VERIFY → SHIP → LEARN → BUILD AGAIN`

**[FRIDAY](https://github.com/hackers-reality/friday) · [All repositories](https://github.com/hackers-reality?tab=repositories)**

<sub>The interesting engineering begins after the first model response.</sub>

</div>
