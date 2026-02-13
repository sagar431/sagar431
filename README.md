# <div align="center">`>_ sagar`</div>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   🧠 Agent Architect  ·  🔧 MLOps Engineer  ·  🔬 First Principles ║
║                                                                  ║
║   Building AI systems that think, see, and ship.                 ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

  <p>
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&width=620&height=80&lines=%3E+Perceiving...+Remembering...+Deciding...+Acting...;No+frameworks.+No+shortcuts.+Just+Python." alt="Typing SVG" />
  </p>

  <a href="https://x.com/sagar_agi007"><img alt="X" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://github.com/sagar431"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://huggingface.co/sagar007"><img alt="HuggingFace" src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"></a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## The Thesis

Most people use AI. I build the systems that make AI *work*.

Every project I ship follows one rule: **understand from first principles, then build from scratch.** No LangChain. No LangGraph. No magic abstractions. Just Python, clear architecture, and hard-won intuition about what actually matters in production.

```
What I've built in 2026:
  ├── 18 AI agent sessions (perception → memory → decision → action)
  ├── A multimodal vision-language model (Gemma-270M + CLIP, trained from scratch)
  ├── ResNet-50 on ImageNet with multi-GPU DDP (one of ~10K people who've done this)
  ├── A screenshot-to-website AI pipeline (6 agents, real-time WebSocket UI)
  └── Production LLMOps infrastructure (FastAPI → Docker → K8s → Prometheus)
```

<br>

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> What I Ship

<table>
<tr>
<td width="50%">

### 🧠 Agentic AI — From Scratch

> *4-layer cognitive architecture: Perceive → Remember → Decide → Act*

I don't use agent frameworks. I build the framework. 18 sessions of progressively complex agent systems, each one teaching a different architectural pattern.

```yaml
Agent Architecture:
  ├── Perception (Gemini Vision + structured extraction)
  ├── Memory (session logs + vector search + summarization)
  ├── Decision (multi-step planning with tool selection)
  └── Action (MCP servers + sandboxed execution)
```

**Key insight:** An agent is just a while loop with good memory. Everything else is engineering.

</td>
<td width="50%">

### 👁️ Multimodal AI — Vision Meets Language

> *Gemma-270M + CLIP = A tiny model that sees and speaks*

Built a complete vision-language model from scratch. Combined a 270M language model with CLIP vision encoder, trained on 157K LLaVA pairs on a single A100.

```
Pipeline:
  Image → CLIP ViT-Large (frozen, 428M)
       → Vision Projector MLP (trainable)
       → Gemma-270M + LoRA (trainable)
       → Text Response

  539M total · 18.6M trainable (3.4%) · 9hrs on A100
```

**[Live Demo →](https://huggingface.co/spaces/sagar007/Multimodal-Gemma)** · **[Code →](https://github.com/sagar431/multimodal-gemma-270m)**

</td>
</tr>
<tr>
<td width="50%">

### 🏋️ Deep Learning — First Principles

> *ResNet-50 on ImageNet from scratch. Multi-GPU DDP. One Cycle Policy.*

Not `torchvision.models.resnet50(pretrained=True)`. The real thing — implementing every layer, training with proper recipes, scaling to 4× V100s with Distributed Data Parallel.

```
Results:
  ├── CIFAR-100: 73%+ top-1 accuracy
  ├── ImageNet-1K: 75%+ top-1 accuracy
  ├── Training: SGD + OneCycleLR + MixUp + CutOut
  └── Scale: Ring all-reduce across 4 GPUs
```

**Philosophy:** If you can't build it from scratch, you don't understand it.

</td>
<td width="50%">

### 🚀 LLMOps — Production AI Infrastructure

> *From model handler to Kubernetes deployment with monitoring*

Complete production pipeline: FastAPI serving → Docker containerization → K8s orchestration → Prometheus monitoring → rate limiting → cost controls.

```
Stack:
  ├── Serving: FastAPI + uvicorn + async handlers
  ├── Containers: Docker multi-stage builds
  ├── Orchestration: Kubernetes + GPU scheduling
  ├── Monitoring: Prometheus + Grafana dashboards
  └── CI/CD: GitHub Actions → HuggingFace Spaces
```

**Principle:** You can't optimize what you can't measure.

</td>
</tr>
</table>

<br>

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="25"> Tech Stack

<div align="center">

| Domain | Technologies |
|--------|-------------|
| **🤖 Agent Architecture** | `Custom Cognitive Loops` `MCP Servers` `Structured Reasoning` `Tool Orchestration` |
| **🧠 ML / Deep Learning** | `PyTorch` `Transformers` `CLIP` `LoRA/PEFT` `Mixed Precision` `DDP` |
| **💬 LLM APIs** | `Gemini` `GPT` `Claude` `Ollama` `vLLM` |
| **🔧 MLOps** | `Docker` `Kubernetes` `DVC` `MLflow` `W&B` `Prometheus` `Grafana` |
| **☁️ Cloud & Infra** | `AWS (EC2/Lambda/EKS)` `HuggingFace Spaces` `Render` |
| **💾 Data & Storage** | `FAISS` `Pinecone` `PostgreSQL` `Redis` `Vector DBs` |
| **🌐 Web** | `FastAPI` `WebSockets` `React` `Gradio` |

</div>

<br>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,docker,kubernetes,aws,fastapi,postgres,redis,git,linux&theme=dark" />
</div>

<br>

## 🔬 Current Deep Dives

<div align="center">

```
┌────────────────────────────────────────────────────────────────────────┐
│                                                                        │
│   📚 Training Models from Scratch                                      │
│   ├── Understanding every gradient, every weight update                │
│   ├── CUDA optimization & GPU computing fundamentals                   │
│   └── Making deep learning "go brrrr" from first principles           │
│                                                                        │
│   🏗️ Building AI Agents                                                │
│   ├── Perception → Memory → Decision → Action loops                   │
│   ├── Tool use & MCP server architecture                              │
│   └── Cognitive monitoring & memory versioning                        │
│                                                                        │
│   ⚙️ Production MLOps → AgentOps                                       │
│   ├── Config-driven architecture (behavior via YAML, not code)        │
│   ├── Unified infra for traditional models + autonomous agents        │
│   └── Same production rigor for reasoning as predictions              │
│                                                                        │
└────────────────────────────────────────────────────────────────────────┘
```

</div>

<br>

## 📝 Writing

I write deep technical blogs — no fluff, just working code and hard-won lessons.

| Blog | Topic | What You'll Learn |
|------|-------|-------------------|
| **[Agentic AI from First Principles](https://sagar431.github.io/portfolio)** | Agent Architecture | 4-layer cognitive stack, tool use, multi-agent systems — all in Python |
| **[LLMOps: Deploy & Scale LLMs](https://sagar431.github.io/portfolio)** | Production AI | FastAPI → Docker → K8s → Prometheus, every line explained |
| **[Training ResNet from Scratch](https://sagar431.github.io/portfolio)** | Deep Learning | Architecture → implementation → One Cycle Policy → multi-GPU DDP |
| **[Building a Multimodal VLM](https://sagar431.github.io/portfolio)** | Multimodal AI | CLIP + Gemma-270M + LoRA, trained on 157K pairs with full MLOps CI/CD |

<br>

## 💡 How I Think

```python
class AgentArchitect:
    """The principles behind everything I build."""

    principles = {
        "first_principles":    "If you can't build it from scratch, you don't understand it",
        "no_magic":            "No LangChain, no LangGraph — just Python and clear thinking",
        "production_or_bust":  "A model in a notebook is a toy. Ship it or it doesn't count",
        "measure_everything":  "Prometheus for predictions AND cognitive load",
        "config_over_code":    "Change behavior via YAML, not rewrites",
        "small_teaches_big":   "A 270M model teaches the same architecture as a 70B one",
    }

    def build(self, idea):
        """The loop: understand → implement → ship → write about it."""
        understanding = self.study_from_first_principles(idea)
        implementation = self.build_from_scratch(understanding)
        production = self.deploy_with_monitoring(implementation)
        return self.write_the_blog(production)  # so others can learn too
```

<br>

## 📈 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=sagar431&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117"/>
  <img height="180em" src="https://github-readme-streak-stats-nine-alpha.vercel.app/?user=sagar431&theme=tokyonight&hide_border=true&background=0D1117"/>
</div>

<br>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=sagar431&theme=tokyonight" width="100%"/>
</div>

<br>

## 🧠 2026: Building AI Agents & MLOps from Scratch

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Snake animation" />

</div>

<br>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3000&pause=500&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=100&lines=%3E+Initializing+Agent+Training+Pipeline...;%3E+Loading+perception+module...+%E2%9C%93;%3E+Connecting+memory+infrastructure...+%E2%9C%93;%3E+Activating+decision+engine...+%E2%9C%93;%3E+Agent+ready.+Awaiting+commands.+%F0%9F%9A%80" alt="Terminal Animation" />
</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

<sub>⚡ Like training a neural network — each epoch brings us closer to autonomous systems 🧠</sub>

</div>

<br>

## 📬 Let's Connect

<div align="center">

*Building the bridge between deep learning fundamentals and production AI systems.*

*If you're training models from scratch, building agents without frameworks, or shipping ML to production — let's talk!*

<br>

<a href="mailto:sagarpallai1997@gmail.com">
  <img src="https://img.shields.io/badge/Email-sagarpallai1997@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://x.com/sagar_agi007">
  <img src="https://img.shields.io/badge/DM_on_X-000000?style=for-the-badge&logo=x&logoColor=white"/>
</a>

<a href="https://huggingface.co/sagar007">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=sagar431&label=Profile%20Views&color=00D9FF&style=flat-square" alt="Profile Views"/>

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,100:7B68EE&height=100&section=footer" width="100%"/>

<div align="center">
  <sub>🔧 Built with passion for AI systems that actually work in production</sub>
</div>
