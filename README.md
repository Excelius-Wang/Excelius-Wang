<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0:282a36,100:bd93f9&section=header" alt="banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Pacifico&size=55&color=bd93f9&center=true&vCenter=true&width=600&height=90&lines=Excelius" alt="Excelius" />
</p>

<p align="center">
  LLM post-training · alignment · evaluation · agents 🤖 — MSc @ BJTU
</p>

<p align="center">
  <a href="https://www.excelius.xyz">Website</a> •
  <a href="mailto:excelius@qq.com">Email</a>
</p>

---

## About Me

- 🎓 MSc in Software Engineering @ **Beijing Jiaotong University**; BEng @ Nantong University.
- 🔬 I work on **LLM post-training, alignment, and evaluation**, and build **LLM agents** and developer tools.
- 🛠️ I contribute fixes to open-source training, evaluation, and agent frameworks, with a focus on numerical stability, metric correctness, and reliable runtime behavior.
- 📝 Co-authored a research paper.
- ✍️ I write notes & blog posts at [excelius.xyz](https://www.excelius.xyz).

## Experience

- **ByteDance** — Multimodal LLM Algorithm Intern · *present*
- **Baidu** — LLM Post-training Algorithm Intern
- **Tsinghua University, Institute of Vehicle Power & Intelligent Energy** — LLM Application & Full-stack Intern

## Open Source Contributions

**45 merged PRs across external open-source repositories**, covering code fixes, tests, and documentation. Counts below include merged PRs only, as of **September 13, 2026**.

- **OpenRLHF — 7 merged PRs**: Improved PPO numerical stability, reward computation, checkpoint recovery, evaluation batch handling, and multi-turn rollout truncation. Selected PRs: [k3 KL gradients #1335](https://github.com/OpenRLHF/OpenRLHF/pull/1335) · [FP32 reward shaping #1334](https://github.com/OpenRLHF/OpenRLHF/pull/1334) · [checkpoint recovery #1333](https://github.com/OpenRLHF/OpenRLHF/pull/1333) · [rollout truncation #1327](https://github.com/OpenRLHF/OpenRLHF/pull/1327).
- **ms-swift — 6 merged PRs**: Fixed NLG metric aggregation, inference error propagation, prompt token accounting, SSE handling, and training integration compatibility. Selected PRs: [empty prediction scoring #9962](https://github.com/modelscope/ms-swift/pull/9962) · [worker errors #10093](https://github.com/modelscope/ms-swift/pull/10093) · [prompt usage #10094](https://github.com/modelscope/ms-swift/pull/10094) · [Megatron integration #10025](https://github.com/modelscope/ms-swift/pull/10025).
- **EvalScope — 6 merged PRs**: Corrected ASR word error rates, streaming latency measurements, multimodal image inputs, and Terminal-Bench reward validation; also updated evaluation configuration and documentation. Selected PRs: [ASR scoring #1722](https://github.com/modelscope/evalscope/pull/1722) · [TTFT / ITL #1645](https://github.com/modelscope/evalscope/pull/1645) · [image inputs #1618](https://github.com/modelscope/evalscope/pull/1618) · [trial rewards #1610](https://github.com/modelscope/evalscope/pull/1610).
- **OpenAI Agents Python — 3 merged PRs**: Fixed session deletion under cancellation, model-provider cleanup, and type annotations for variadic tool arguments. PRs: [session cleanup #4790](https://github.com/openai/openai-agents-python/pull/4790) · [provider lifecycle #4785](https://github.com/openai/openai-agents-python/pull/4785) · [tool arguments #4655](https://github.com/openai/openai-agents-python/pull/4655).

Other merged contributions include **Atomic Agents (4)**, **LiveKit Agents (2)**, **MCP Servers (1)**, **OpenAI Agents JS (1)**, and **Axolotl (1)**. Examples: [MCP resource templates](https://github.com/Eigenwise/atomic-agents/pull/280) · [turn cancellation](https://github.com/livekit/agents/pull/6913) · [UTF-8 file reads](https://github.com/modelcontextprotocol/servers/pull/4667) · [hosted MCP outputs](https://github.com/openai/openai-agents-js/pull/1747) · [activation checkpointing compatibility](https://github.com/axolotl-ai-cloud/axolotl/pull/3942).

## Tech Stack

- **Languages**: Python, C++, TypeScript / JavaScript, Rust
- **LLM / Post-training**: PyTorch, Hugging Face Transformers, LLaMA-Factory, ms-swift, vLLM
- **Alignment / Evaluation**: SFT, LoRA, DPO, PPO, GRPO, reward modeling, LLM-as-a-Judge, EvalScope
- **Agents**: LangChain, LangGraph, tool calling, ReAct, plan-and-execute workflows
- **Applications / Infra**: React, Vue, FastAPI, Tauri, multi-node multi-GPU training, Git, Docker

## Featured Projects

- [**Repolane**](https://github.com/Excelius-Wang/harbor) — A GitHub desktop workspace for browsing code, reviewing pull requests, and managing repository work, built with React, TypeScript, Rust, and Tauri. Repository: `harbor`; actively developing, with no packaged public release yet.
- [**Self-DeepResearch**](https://github.com/Excelius-Wang/Self-DeepResearch) — An iterative research agent built with LangGraph and Tavily: plan → search → review → report, with a Vue frontend and FastAPI streaming backend.
- [**marginalia**](https://github.com/Excelius-Wang/marginalia) — A paper-reading skill for Claude Code / Codex that reconstructs a paper's reasoning, examines its assumptions, and publishes structured notes with figures and formulas to a Feishu knowledge base.
- [**dive-into-transformer-pytorch**](https://github.com/Excelius-Wang/dive-into-transformer-pytorch) — A Transformer language model implemented in PyTorch and trained on *Dream of the Red Chamber*, with DDP multi-GPU training, checkpoint saving, and training-curve visualization.
- [**BERT_BiLSTM_CRF**](https://github.com/Excelius-Wang/BERT_BiLSTM_CRF) — Chinese named-entity recognition with BERT + BiLSTM + CRF, developed for BJTU NLP coursework.

---

## 📊 Dashboard

<p align="center">
  <a href="https://ghfind.com/u/excelius-wang?ref=badge">
    <img src="https://ghfind.com/api/card/mini/excelius-wang?lang=zh" alt="ghfind GitHub 评分卡" width="440" />
  </a>
</p>

<!--
  仪表盘统一使用 dracula 主题（深紫底+浅字），深浅模式表现一致，故不再做 <picture> 双版本。
  实例选择：stats 用加速实例；streak 用 demolab 官方；summary 用官方；trophy 用社区负载均衡端点。
  若某张卡破图，可互换域名：
    github-readme-stats-fast.vercel.app      <-> github-readme-stats.vercel.app
    streak-stats.demolab.com                 <-> github-readme-streak-stats.vercel.app
    github-profile-summary-cards.vercel.app  <-> github-profile-summary-cards-mirror.vercel.app
    github-trophies.devomb.com               <-> 其他志愿者端点(见 ryo-ma/github-profile-trophy README)
  换主题：把各 URL 的 theme=dracula 改成目标主题名即可。
-->

<table width="100%" align="center">
  <tr>
    <td colspan="3" align="center"><a href="https://github.com/anuraghazra/github-readme-stats">
      <img src="https://github-readme-stats-fast.vercel.app/api?username=Excelius-Wang&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&number_format=long&theme=dracula" height="100%" />
    </a></td>
    <td colspan="3" align="center"><a href="https://github.com/denvercoder1/github-readme-streak-stats">
      <img src="https://streak-stats.demolab.com/?user=Excelius-Wang&mode=weekly&hide_border=true&theme=dracula" height="100%" />
    </a></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Excelius-Wang&theme=dracula" height="100%" />
    </a></td>
    <td colspan="2" align="center"><a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Excelius-Wang&theme=dracula" height="100%" />
    </a></td>
    <td colspan="2" align="center"><a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Excelius-Wang&utcOffset=8&theme=dracula" height="100%" />
    </a></td>
  </tr>
  <tr>
    <td colspan="6" align="center"><a href="https://github.com/ryo-ma/github-profile-trophy">
      <img src="https://github-trophies.devomb.com/?username=Excelius-Wang&column=7&row=1&margin-w=8&no-frame=true&theme=dracula" width="100%" />
    </a></td>
  </tr>
</table>
