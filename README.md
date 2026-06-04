<div align="center">

```
██████╗  █████╗ ██████╗ ██╗███████╗██╗  ██╗ █████╗
██╔══██╗██╔══██╗██╔══██╗██║██╔════╝██║  ██║██╔══██╗
██████╔╝███████║██████╔╝██║███████╗███████║███████║
██╔═══╝ ██╔══██║██╔══██╗██║╚════██║██╔══██║██╔══██║
██║     ██║  ██║██║  ██║██║███████║██║  ██║██║  ██║
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝
```

**18 · NIT Hamirpur · CS undergrad · building things too ambitious for my age**

*I go deep or I don't go at all.*

</div>

---

## who i am

I'm Parisha — I go by **Shylin** online. Third-year CS student at NIT Hamirpur, obsessed with the intersection of mathematics, systems, and intelligence.

I build distributed ML infrastructure from scratch. Not wrappers around APIs — actual transformers, actual message queues, actual autoscalers. I care about how things work at the lowest level.

When I'm not coding, I'm reading philosophy or psychology, doing maths, or listening to music. I think about emergent behavior a lot — in systems, in economies, in minds.

> *"The goal is not to understand AI. The goal is to build the thing that understands."*

---

## what i've built

### [Sentinel](https://github.com/Shylin26/Sentinel) — distributed ML code review platform
> *Every git push. Under 2 seconds.*

Transformer trained **from scratch** on 2M real PR review comments. Not a fine-tune. Not a wrapper. A custom BPE tokenizer, 6-layer encoder, multi-task classification head, TorchScript export. Wired into Kafka → diff extractor → inference worker → GitHub PR comment. Dynamic autoscaler via raw Docker SDK. Prometheus + Grafana observability.

`PyTorch` `TorchScript` `Kafka` `FastAPI` `Docker` `Prometheus` `SentencePiece`

---

### [Sociogenesis](https://github.com/Shylin26/Sociogenesis) — emergent agent economy
> *20 identical agents. One hard problem. Roles emerge on their own.*

Twenty LLM agents dropped into a shared economy with no predefined roles. Coalitions form. Hierarchies emerge. The colony writes its own paper. Runs on a MacBook. Built to study emergence — not simulate it.

`Python` `Multi-agent` `LLM` `Emergent behavior`

---

### [Eidolon](https://github.com/Shylin26/Eidolon) — local code intelligence
> *Your codebase. Your machine. No cloud.*

Local code intelligence layer running entirely on Apple Silicon. Go backend, Kafka event bus, MLX inference, CodeLlama. Everything on-device. Privacy-first, latency-first.

`Go` `Kafka` `MLX` `CodeLlama` `Apple Silicon`

---

## open source

Active contributor to production ML infrastructure:

| PR | Repo | What |
|---|---|---|
| [#4119](https://github.com/vllm-project/vllm-omni/pull/4119) | `vllm-project/vllm-omni` ⭐4.9k | Fix hardcoded `if True` — restored threshold-based SHM routing |
| [#4120](https://github.com/vllm-project/vllm-omni/pull/4120) | `vllm-project/vllm-omni` ⭐4.9k | Remove dead `assets/video.py` — confirmed zero references |
| [#4121](https://github.com/vllm-project/vllm-omni/pull/4121) | `vllm-project/vllm-omni` ⭐4.9k | Fix `engine_args` dict mutation — prevents silent config corruption |
| WIP | `ml-explore/mlx-lm` | Pending review |

---

## tech stack

**ML & AI**
`PyTorch` `TorchScript` `MLX` `SentencePiece` `Transformers` `LLM inference` `multi-agent systems`

**Systems & Infrastructure**
`Apache Kafka` `Docker` `FastAPI` `Prometheus` `Grafana` `gRPC` `Ray`

**Languages**
`Python` `Go` `C` `Bash`

**Hardware**
`Apple Silicon (M4)` `CUDA` `MPS backend`

---

## what i think about

```
mathematics  →  the language everything is written in
philosophy   →  why anything exists at all  
psychology   →  how minds model the world
music        →  the one thing that bypasses language entirely
systems      →  where all four collide
```

I believe robust systems and genuine intelligence are the same problem stated differently. That's what I'm trying to solve.

---

## let's build something

I'm looking for:
- **Research collaborations** — especially multi-agent, inference systems, emergent behavior
- **Open source projects** to contribute to meaningfully
- **People who go deep** — not broad

If you're building something ambitious or want to talk about distributed systems, ML infrastructure, philosophy of mind, or just math — reach out.

*Social links coming soon — setting everything up properly.*

---

<div align="center">

**NIT Hamirpur · India · 2025–2029**

*going into 3rd year · open to internships · building in public*

</div>

<!--
**Shylin26/Shylin26** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
