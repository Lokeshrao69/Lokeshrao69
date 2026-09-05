<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║                    LOKESH RAO — PROFILE                     ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

# `LOKESH RAO`

### Quantitative Developer · Systems Engineer · Builder

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+low-latency+trading+systems;Engineering+market+microstructure+infrastructure;Exploring+reinforcement+learning+for+execution;C%2B%2B20+%C3%97+Python+%C3%97+CUDA+%C3%97+Linux" alt="Typing animation" />

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Lokeshrao69-181717?style=for-the-badge\&logo=github)](https://github.com/Lokeshrao69)
[![Nexus-LOB](https://img.shields.io/badge/Project-Nexus--LOB-0A0A0A?style=for-the-badge\&logo=github)](https://github.com/Lokeshrao69/Nexus_LOB)

</div>

---

## `> whoami`

```text
┌──────────────────────────────────────────────────────────────────┐
│                                                                  │
│  Lokesh Rao                                                      │
│                                                                  │
│  Quantitative Developer / Systems Engineer                       │
│                                                                  │
│  I like building things where software engineering meets        │
│  quantitative finance, market microstructure, and machine        │
│  learning.                                                       │
│                                                                  │
│  Current focus:                                                  │
│                                                                  │
│    → Low-latency C++ systems                                     │
│    → Limit order books & matching engines                         │
│    → Algorithmic execution                                       │
│    → Market-data replay & microstructure                         │
│    → Reinforcement learning                                      │
│    → GPU / CUDA computing                                        │
│    → Quantitative risk systems                                   │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

---

## `> current_project`

<div align="center">

# [NEXUS-LOB](https://github.com/Lokeshrao69/Nexus_LOB)

### Low-Latency Limit Order Book & Quantitative Execution Platform

</div>

```text
                        MARKET DATA
                            │
                            ▼
                    ┌───────────────┐
                    │  ITCH 5.0     │
                    │    REPLAY     │
                    └───────┬───────┘
                            │
                            ▼
              ┌───────────────────────────┐
              │       LIMIT ORDER BOOK    │
              │                           │
              │       C++20 ENGINE        │
              │                           │
              │  Price-Time Priority      │
              │  Market / Limit / IOC     │
              │  FOK / GTC / Cancel       │
              │  Partial Fills            │
              │  Multi-Level Sweeps       │
              └─────────────┬─────────────┘
                            │
                    pybind11 / SHM
                            │
                            ▼
              ┌───────────────────────────┐
              │       PYTHON QUANT        │
              │                           │
              │  L2 Replay                │
              │  Gymnasium Environment    │
              │  TWAP / VWAP / POV        │
              │  Execution Analytics      │
              └─────────────┬─────────────┘
                            │
                            ▼
                 ┌────────────────────┐
                 │   RL EXECUTION     │
                 │                    │
                 │   PPO / GRPO       │
                 └────────────────────┘
```

**Nexus-LOB** is my attempt to build the infrastructure underneath an execution-research stack rather than treating trading as just a machine-learning problem.

### Stack

`C++20` · `Python` · `CMake` · `pybind11` · `NumPy` · `Gymnasium` · `Linux` · `Shared Memory` · `ITCH 5.0`

### Implemented

* Price-time-priority matching engine
* Integer-tick price representation
* Limit / Market / IOC / FOK / GTC orders
* Partial fills and multi-level sweeps
* Cancellation and modification
* Fixed-capacity order pool
* Fixed-size L2 state contract
* C++ ↔ Python bridge
* ITCH 5.0 parser
* Deterministic market replay
* Gymnasium execution environment
* TWAP / VWAP / POV / Passive baselines
* Shared-memory SPSC transport
* C++ engine vs Python reference-model parity testing

### Research Direction

```text
        Conventional Execution
                 │
        ┌────────┼────────┐
        ▼        ▼        ▼
       TWAP     VWAP     POV
        │        │        │
        └────────┼────────┘
                 ▼
          Learned Execution
                 │
             PPO / GRPO
                 │
                 ▼
       Lower Implementation
            Shortfall
```

→ **[Explore Nexus-LOB](https://github.com/Lokeshrao69/Nexus_LOB)**

---

## `> tech_stack`

### Systems

<p align="center">

<img src="https://skillicons.dev/icons?i=cpp,cmake,linux,git,github" />

</p>

### Quant / ML

<p align="center">

<img src="https://skillicons.dev/icons?i=python,numpy,pytorch" />

</p>

### Currently Exploring

```text
C++20
├── memory-conscious data structures
├── low-latency execution paths
├── lock-free / shared-memory systems
└── deterministic simulation

Quant Finance
├── market microstructure
├── limit order books
├── algorithmic execution
├── implementation shortfall
└── execution optimization

Machine Learning
├── reinforcement learning
├── PPO
├── GRPO
└── policy-based execution

GPU
├── CUDA
├── Monte-Carlo simulation
├── VaR
└── CVaR
```

---

## `> engineering_principles`

```text
┌────────────────────────────────────────────────────────────┐
│                                                            │
│  01  Correctness before optimization                       │
│                                                            │
│  02  Benchmark the system, don't guess                    │
│                                                            │
│  03  Keep hot paths deterministic                          │
│                                                            │
│  04  Prefer explicit memory ownership                      │
│                                                            │
│  05  Use reference implementations as correctness oracles  │
│                                                            │
│  06  Treat interfaces / ABI boundaries as contracts        │
│                                                            │
│  07  Build infrastructure that makes experiments          │
│      reproducible                                          │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

---

## `> github_stats`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Lokeshrao69&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true" />

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lokeshrao69&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

---

## `> contribution_activity`

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Lokeshrao69&theme=github-dark-blue&hide_border=true" />

</div>

<br>

<div align="center">

### contribution graph

<img src="https://raw.githubusercontent.com/Lokeshrao69/Lokeshrao69/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation" />

</div>

---

## `> featured_work`

### [Nexus-LOB](https://github.com/Lokeshrao69/Nexus_LOB)

**Low-latency limit-order-book and execution research platform.**

```text
C++20
│
├── Matching Engine
├── Order Pool
├── Book State
├── Shared Memory
└── Benchmarks
       │
       ▼
Python
│
├── ITCH Replay
├── L2 State
├── Execution Environment
├── Baselines
└── RL Research
```

---

### More projects

I'm building out the rest of this section as the project portfolio grows.

The goal is to keep the repositories focused on **systems, quantitative finance, machine learning, and interesting engineering problems** rather than collecting tutorial projects.

---

## `> currently_learning`

```text
[██████████████████░░]  C++ Systems / Performance

[████████████████░░░░]  Quantitative Finance

[███████████████░░░░░]  Market Microstructure

[████████████░░░░░░░░]  Reinforcement Learning

[██████████░░░░░░░░░░]  CUDA / GPU Computing
```

---

## `> research_ideas`

Things I want to explore:

```text
01  Can RL learn when to cross the spread vs provide liquidity?

02  How much execution quality comes from queue-position awareness?

03  How does market impact change with participation rate?

04  Can learned execution policies outperform TWAP / VWAP / POV
    under realistic order-book dynamics?

05  How much can GPU parallelism accelerate portfolio risk simulation?

06  What happens when execution optimization and risk optimization
    are treated as one problem?
```

---

## `> terminal`

```bash
$ uname -a

Linux quant-node 6.x x86_64

$ cat /etc/interests

systems
quant-finance
market-microstructure
reinforcement-learning
gpu-computing
algorithmic-trading

$ ./current_project

Nexus-LOB

$ ./stack

C++20
Python
CMake
NumPy
pybind11
Gymnasium
CUDA

$ systemctl status brain

● brain.service - learning
   Loaded: loaded
   Active: active (always)

$ echo $STATUS

BUILDING.
```

---

## `> contribution_graph`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Lokeshrao69&theme=github-compact&hide_border=true&area=true" alt="Contribution activity graph" />

</div>

---

## `> contact`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Lokeshrao69-181717?style=for-the-badge\&logo=github)](https://github.com/Lokeshrao69)

</div>

---

<div align="center">

```text
"Build systems. Measure them. Break them. Understand them."
```

### `EOF`

</div>
