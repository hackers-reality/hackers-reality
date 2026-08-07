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

```text
OBJECTIVE
   │
   ▼
CONTEXT ──► REASON + PLAN ──► DELEGATE ──► EXECUTE ──► TOOLS
                 ▲                │                       │
                 │                └── parallel agents ───┤
                 │                                        ▼
                 └──── SELF-CORRECT ◄──── VERIFY ◄────────┘
                           │                 │
                           └── failed ───────┘
                                             └── passed ──► SHIP / CONTINUE
```

---

## 🤖 Flagship — [FRIDAY](https://github.com/hackers-reality/friday)

> **A Windows-native autonomous AI agent built around observation, memory, tools, delegation and action.**

FRIDAY is my largest agentic-system project. Its current repository documents voice/live audio, screen awareness, desktop and browser automation, persistent memory, goals, communications, model routing, multi-agent delegation, parallel sub-agents, research workflows, scheduling, GitHub integration, self-modification, sidecars, dashboards and a large tool surface.

The interesting question isn't *“can an LLM answer me?”* It's:

**Can a personal AI observe its environment, remember what matters, choose tools, coordinate work, verify itself and actually finish things?**

```text
                              ┌────────────────────┐
                              │    USER / GOAL     │
                              └─────────┬──────────┘
                                        ▼
                              ┌────────────────────┐
                              │    FRIDAY CORE     │
                              └─────────┬──────────┘
          ┌───────────────────┬─────────┼──────────┬───────────────────┐
          ▼                   ▼         ▼          ▼                   ▼
   MEMORY + CONTEXT      REASONING   TOOL ROUTER   AGENTS        AUTHORITY
          │                   │         │          │                   │
          │                   │    ┌────┼────┐  ┌──┼────────┐          │
          │                   │    ▼    ▼    ▼  ▼  ▼        ▼          │
          │                   │ DESKTOP WEB COMMS WORKER RESEARCH PARALLEL
          │                   │    └────┴────┴──┴──┴────────┘          │
          └───────────────────┴──────────────┬─────────────────────────┘
                                             ▼
                                  ┌────────────────────┐
                                  │ VERIFICATION LOOP  │
                                  └─────────┬──────────┘
                                  retry ◄───┤───► action/result
```

The full FRIDAY README itself uses a **repository tree as its architecture view** rather than relying on GitHub's rich-diagram renderer. I followed the same reliability principle here: diagrams that matter are plain README content and survive even when GitHub's Mermaid frontend decides to have a dramatic episode.

**→ [Explore FRIDAY](https://github.com/hackers-reality/friday)**

---

## 🚀 Selected builds

<table>
<tr>
<td width="50%" valign="top">

### 💹 [FinIntel](https://github.com/hackers-reality/FinIntel)
AI-assisted financial intelligence and analysis experiments.

</td>
<td width="50%" valign="top">

### 🎌 [NexAnime](https://github.com/hackers-reality/NexAnime)
Product and full-stack engineering from the application side of my work.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [NexCli](https://github.com/hackers-reality/NexCli)
CLI tooling and developer experimentation — because apparently GUIs weren't enough trouble.

</td>
<td width="50%" valign="top">

### 📚 [JEE Prep](https://github.com/hackers-reality/JEE-prep)
Applying software engineering to learning and preparation.

</td>
</tr>
</table>

### 🏁 Where it started

**[EmoBoost](https://github.com/hackers-reality/EmoBoost-1021)** and **[Innovation Challenge](https://github.com/hackers-reality/innovatiochallenge_3011)** are among my earliest repositories and were built for competitions. They stay visible because they show the beginning of the trajectory, not because I'm pretending an early competition build is the same thing as FRIDAY today.

```text
COMPETITION BUILDS
       │
       ▼
PRODUCT EXPERIMENTS ──► DEVELOPER TOOLS ──► FULL-STACK SYSTEMS
                                                   │
                                                   ▼
                                         AUTONOMOUS AGENTS
                                                   │
                                                   ▼
                                                FRIDAY
```

> This profile is curated. Some repositories on the account are forks, references, experiments or old work; the projects above are intentionally selected rather than treating every repository as authored flagship work.

---

## ⚙️ Languages & tools

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,html,css,react,nextjs,nodejs,git,github,linux,bash,docker,vscode,mysql&perline=8" alt="Technology icons" />

</div>

### Things I keep going too far into

`LLM Agents` · `Context Engineering` · `Prompt Engineering` · `Tool Calling` · `Multi-Agent Systems` · `Automation` · `Research Workflows` · `Full-Stack Architecture` · `APIs` · `Authentication` · `Databases`

---

## 🧩 Agent engineering philosophy

The model is a component, not the whole architecture.

```text
 MODEL ───────┐
 CONTEXT ─────┤
 MEMORY ──────┼──► ORCHESTRATION ──► PLAN ──► EXECUTION ──► VERIFICATION
 TOOLS ───────┤                         │             ▲            │
 AUTHORITY ───┘                         │             │            │
                                        └─► DELEGATE ┘            │
                                              │                    │
                                         PARALLEL AGENTS           │
                                                                   │
                              SELF-CORRECTION ◄──── failed ─────────┘
                                      │
                                      └──────────────► PLAN

                                            passed ──► SHIP / CONTINUE
```

My favorite engineering loop is giving an agent a real objective, enough context to understand the system, permission to inspect its environment, the ability to delegate when useful, and one non-negotiable rule: **verify what you built before claiming you're done.**

The prompt matters. The working context matters. Tool design matters. Delegation matters. Verification matters. A benchmark score by itself doesn't tell you how well the complete system will behave once you hand it a messy repository and tell it to keep going.

---

## 🔬 Portfolio + laboratory

GitHub for me is both. Some repositories are polished projects; others are prototypes, experiments and evidence of an idea arriving at an unreasonable hour.

```text
idea
 │
 ▼
prototype ──► build too much ──► break something
                    ▲                   │
                    │                   ▼
                    └── improve ◄── understand why
                    │
                    └──────────────────────► eventually ship
```

The mess is useful. You can see the progression instead of only the finished screenshot.

---

## 📊 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hackers-reality&theme=tokyo-night&hide_border=true&area=true" alt="hackers-reality contribution activity graph" />

</div>

---

## ⚡ The pattern

```text
BUILD ──► VERIFY ──► SHIP ──► LEARN
  ▲                              │
  └──────────────────────────────┘
```

<div align="center">

### `BUILD → VERIFY → SHIP → LEARN → BUILD AGAIN`

**[FRIDAY](https://github.com/hackers-reality/friday) · [All repositories](https://github.com/hackers-reality?tab=repositories)**

<sub>The interesting engineering begins after the first model response.</sub>

</div>
