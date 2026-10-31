<div align="center">

<img src="banner.svg" width="100%" alt="Top Open Weight Coding Models"/>

# Top Open Weight Coding Models

<p><i>Open-weight coding and agent models (Qwen Coder, DeepSeek, GLM, Kimi, Devstral, StarCoder) plus the tools to run them locally: llama.cpp, Ollama, vLLM, MLX, ranked by GitHub stars</i></p>

![Ranked by GitHub stars](https://img.shields.io/badge/ranked%20by-GitHub%20stars-orange?style=for-the-badge) ![GitHub stars](https://img.shields.io/badge/%E2%AD%90%20stars-repo-black?style=for-the-badge) ![License](https://img.shields.io/badge/license-CC0-0a7bbb?style=for-the-badge)

![entries](https://img.shields.io/badge/entries-63-blueviolet?style=for-the-badge) ![total stars](https://img.shields.io/badge/total%20stars-1.2M-gold?style=for-the-badge) ![updated](https://img.shields.io/badge/updated-2026--10--30-brightgreen?style=for-the-badge)

**English** · [简体中文](README.zh-CN.md)

</div>

---

> **Why now:** Three open-weight releases landed in one week: Reflection's [Beam](https://reflection.ai/blog/beam-is-available) (501B MoE, 23B active, Apache 2.0, weights out Oct 16), [DeepSeek V4.1-Flash-1017](https://api-docs.deepseek.com/news/news261017/) (Oct 17) and Liquid AI's [LFM2.5-24B-A2B](https://www.liquid.ai/blog/lfm2-5-24b-a2b) (Oct 14, 2B active, built for on-device agents). None of the three has a GitHub repo of its own, so they are named here instead of ranked below. Beam was reported with day-0 support in vLLM and SGLang (ranked below), and the first section lists GitHub projects that run LFM2.5. The list ranks the GitHub projects you use to run models like them on your own machine.

---

## Contents

- [🏆 Top Picks](#top-picks)
- [Local Inference Engines](#sec-1) · 20
- [Open-Weight Coding & Agent Models](#sec-2) · 20
- [Local Coding Agents & IDE Plugins](#sec-3) · 20
- [Run LFM2.5 on Your Machine](#sec-4) · 3
- [📖 About this list](#about)

<a id="top-picks"></a>

## 🏆 Top Picks

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ollama/ollama**](https://github.com/ollama/ollama) | 185.3k | Go | 2026-10-30 | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. |
| 2 | [**ggml-org/llama.cpp**](https://github.com/ggml-org/llama.cpp) | 132.8k | C++ | 2026-10-30 | LLM inference in C/C++ |
| 3 | [**deepseek-ai/DeepSeek-V3**](https://github.com/deepseek-ai/DeepSeek-V3) | 104.7k | Python | 2025-08-28 | — |
| 4 | [**vllm-project/vllm**](https://github.com/vllm-project/vllm) | 95.9k | Python | 2026-10-30 | A high-throughput and memory-efficient inference and serving engine for LLMs |
| 5 | [**deepseek-ai/DeepSeek-R1**](https://github.com/deepseek-ai/DeepSeek-R1) | 92.0k | — | 2025-06-27 | — |

<a id="sec-1"></a>

## Local Inference Engines

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ollama/ollama**](https://github.com/ollama/ollama) | 185.3k | Go | 2026-10-30 | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. |
| 2 | [**ggml-org/llama.cpp**](https://github.com/ggml-org/llama.cpp) | 132.8k | C++ | 2026-10-30 | LLM inference in C/C++ |
| 3 | [**vllm-project/vllm**](https://github.com/vllm-project/vllm) | 95.9k | Python | 2026-10-30 | A high-throughput and memory-efficient inference and serving engine for LLMs |
| 4 | [**nomic-ai/gpt4all**](https://github.com/nomic-ai/gpt4all) | 77.3k | C++ | 2025-05-27 | GPT4All: Run Local LLMs on Any Device. Open-source and available for commercial use. |
| 5 | [**exo-explore/exo**](https://github.com/exo-explore/exo) | 48.1k | Python | 2026-10-30 | Run frontier AI locally. |
| 6 | [**AlexsJones/llmfit**](https://github.com/AlexsJones/llmfit) | 38.5k | Rust | 2026-10-30 | Hundreds of models & providers. One command to find what runs on your hardware. |
| 7 | [**sgl-project/sglang**](https://github.com/sgl-project/sglang) | 38.4k | Python | 2026-10-30 | SGLang is a high-performance serving framework for large language models and multimodal models. |
| 8 | [**ml-explore/mlx**](https://github.com/ml-explore/mlx) | 29.0k | C++ | 2026-10-30 | MLX: An array framework for Apple silicon |
| 9 | [**mozilla-ai/llamafile**](https://github.com/mozilla-ai/llamafile) | 26.5k | C++ | 2026-10-12 | Distribute and run LLMs with a single file. |
| 10 | [**jundot/omlx**](https://github.com/jundot/omlx) | 23.2k | Python | 2026-10-30 | LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu b… |

<details>
<summary>Show 10 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**Lightning-AI/litgpt**](https://github.com/Lightning-AI/litgpt) | 13.7k | Python | 2026-10-28 | 20+ high-performance LLMs with recipes to pretrain, finetune and deploy at scale. |
| 12 | [**bentoml/OpenLLM**](https://github.com/bentoml/OpenLLM) | 12.6k | Python | 2026-10-26 | Run any open-source LLMs, such as DeepSeek and Llama, as OpenAI compatible API endpoint in the cloud. |
| 13 | [**openvinotoolkit/openvino**](https://github.com/openvinotoolkit/openvino) | 11.1k | C++ | 2026-10-30 | OpenVINO™ is an open source toolkit for optimizing and deploying AI inference |
| 14 | [**RunanywhereAI/runanywhere-sdks**](https://github.com/RunanywhereAI/runanywhere-sdks) | 10.3k | C++ | 2026-10-29 | Production ready toolkit to run AI locally |
| 15 | [**Tiiny-AI/PowerInfer**](https://github.com/Tiiny-AI/PowerInfer) | 9.9k | C++ | 2026-05-11 | High-speed Large Language Model Serving for Local Deployment |
| 16 | [**xorbitsai/inference**](https://github.com/xorbitsai/inference) | 9.6k | Python | 2026-10-30 | Swap GPT for any LLM by changing a single line of code. Xinference lets you run open-source, speech, and mult… |
| 17 | [**FareedKhan-dev/kimi-k3-in-c**](https://github.com/FareedKhan-dev/kimi-k3-in-c) | 9.2k | C | 2026-10-02 | A 2.78-trillion-parameter Kimi K3 running inference on a single CPU in 8.24 GB of RAM. Portable C99: no BLAS,… |
| 18 | [**InternLM/lmdeploy**](https://github.com/InternLM/lmdeploy) | 8.1k | Python | 2026-10-30 | LMDeploy is a toolkit for compressing, deploying, and serving LLMs. |
| 19 | [**ml-explore/mlx-lm**](https://github.com/ml-explore/mlx-lm) | 7.5k | Python | 2026-10-29 | Run LLMs with MLX |
| 20 | [**bojieli/ai-infra-book**](https://github.com/bojieli/ai-infra-book) | 7.2k | Python | 2026-10-01 | Chinese-language project; see the repo for details |

</details>

<a id="sec-2"></a>

## Open-Weight Coding & Agent Models

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**deepseek-ai/DeepSeek-V3**](https://github.com/deepseek-ai/DeepSeek-V3) | 104.7k | Python | 2025-08-28 | — |
| 2 | [**deepseek-ai/DeepSeek-R1**](https://github.com/deepseek-ai/DeepSeek-R1) | 92.0k | — | 2025-06-27 | — |
| 3 | [**QwenLM/qwen-code**](https://github.com/QwenLM/qwen-code) | 28.8k | TypeScript | 2026-10-30 | An open-source AI coding agent that lives in your terminal. |
| 4 | [**QwenLM/Qwen3**](https://github.com/QwenLM/Qwen3) | 27.7k | Python | 2026-01-09 | Qwen3 is the large language model series developed by Qwen team, Alibaba Cloud. |
| 5 | [**deepseek-ai/DeepSeek-Coder**](https://github.com/deepseek-ai/DeepSeek-Coder) | 24.3k | Python | 2025-11-11 | DeepSeek Coder: Let the Code Write Itself |
| 6 | [**QwenLM/Qwen**](https://github.com/QwenLM/Qwen) | 22.0k | Python | 2026-03-05 | Chinese-language project; see the repo for details |
| 7 | [**QwenLM/Qwen3-Coder**](https://github.com/QwenLM/Qwen3-Coder) | 16.8k | Python | 2026-03-24 | Qwen3-Coder is the code version of Qwen3, the large language model series developed by Qwen team. |
| 8 | [**MoonshotAI/Kimi-K2**](https://github.com/MoonshotAI/Kimi-K2) | 11.1k | — | 2026-01-21 | Kimi K2 is the large language model series developed by Moonshot AI team |
| 9 | [**zai-org/GLM-5**](https://github.com/zai-org/GLM-5) | 7.4k | — | 2026-10-15 | GLM-5: From Vibe Coding to Agentic Engineering |
| 10 | [**deepseek-ai/DeepSeek-LLM**](https://github.com/deepseek-ai/DeepSeek-LLM) | 7.3k | Makefile | 2024-02-04 | DeepSeek LLM: Let there be answers |

<details>
<summary>Show 10 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**deepseek-ai/DeepSeek-Coder-V2**](https://github.com/deepseek-ai/DeepSeek-Coder-V2) | 7.0k | — | 2025-11-11 | DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence |
| 12 | [**deepseek-ai/DeepSeek-V2**](https://github.com/deepseek-ai/DeepSeek-V2) | 5.1k | — | 2024-09-25 | DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model |
| 13 | [**gptme/gptme**](https://github.com/gptme/gptme) | 4.5k | Python | 2026-10-30 | Your agent in your terminal, equipped with local tools: writes code, uses the terminal, browses the web. Make… |
| 14 | [**zai-org/GLM-4.5**](https://github.com/zai-org/GLM-4.5) | 4.4k | Python | 2026-02-01 | GLM-4.5: Agentic, Reasoning, and Coding (ARC) Foundation Models |
| 15 | [**QwenLM/Qwen3.8**](https://github.com/QwenLM/Qwen3.8) | 4.3k | — | 2026-08-17 | Qwen3.8 is the large language model series developed by Qwen team, Alibaba Group. |
| 16 | [**twinnydotdev/twinny**](https://github.com/twinnydotdev/twinny) | 3.7k | TypeScript | 2026-10-16 | Open-source AI coding assistant for VS Code. Coding agent, code completion, chat, edits and reviews with loca… |
| 17 | [**bigcode-project/starcoder2**](https://github.com/bigcode-project/starcoder2) | 2.1k | Python | 2024-03-21 | Home of StarCoder2! |
| 18 | [**huggingface/llm-ls**](https://github.com/huggingface/llm-ls) | 883 | Rust | 2026-09-23 | LSP server leveraging LLMs for code completion (and more?) |
| 19 | [**bin123apple/AutoCoder**](https://github.com/bin123apple/AutoCoder) | 847 | Python | 2024-07-06 | We introduced a new model designed for the Code generation task. Its test accuracy on the HumanEval base data… |
| 20 | [**Fast-Editor/Lynkr**](https://github.com/Fast-Editor/Lynkr) | 640 | JavaScript | 2026-10-28 | Streamline your workflow with Lynkr, a CLI tool that acts as an HTTP proxy for efficient code interactions us… |

</details>

<a id="sec-3"></a>

## Local Coding Agents & IDE Plugins

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**continuedev/continue**](https://github.com/continuedev/continue) | 36.4k | TypeScript | 2026-10-30 | open-source coding agent |
| 2 | [**TabbyML/tabby**](https://github.com/TabbyML/tabby) | 33.9k | Rust | 2026-06-30 | Self-hosted AI coding assistant |
| 3 | [**itayinbarr/little-coder**](https://github.com/itayinbarr/little-coder) | 2.7k | TypeScript | 2026-09-18 | A harness optimized to smaller LLMs |
| 4 | [**ggml-org/llama.vscode**](https://github.com/ggml-org/llama.vscode) | 1.5k | TypeScript | 2026-10-28 | VS Code extension for LLM-assisted code/text completion |
| 5 | [**xNul/code-llama-for-vscode**](https://github.com/xNul/code-llama-for-vscode) | 568 | Python | 2024-07-31 | Use Code Llama with Visual Studio Code and the Continue extension. A local LLM alternative to GitHub Copilot. |
| 6 | [**mlhher/late-cli**](https://github.com/mlhher/late-cli) | 452 | Go | 2026-10-19 | High-performance AI agent for long-horizon tasks and local models. Built on empirical research. 200k+ tokens… |
| 7 | [**danishashko/geo-aeo-tracker**](https://github.com/danishashko/geo-aeo-tracker) | 311 | TypeScript | 2026-10-19 | Open-source AI visibility tracker. Track how ChatGPT, Perplexity, Gemini, Copilot and Google AI Mode mention… |
| 8 | [**plaxtoris/codehamr**](https://github.com/plaxtoris/codehamr) | 222 | Go | 2026-09-25 | A minimal, local-first coding agent for the terminal. |
| 9 | [**autohandai/code-cli**](https://github.com/autohandai/code-cli) | 211 | TypeScript | 2026-10-29 | Open-source terminal coding agent. Use 15+ model providers, local models or your own key. Plan mode before ed… |
| 10 | [**AlysisAi/AlysisCode**](https://github.com/AlysisAi/AlysisCode) | 186 | Python | 2026-10-29 | Open-source, multi-model agent for coding, research, and everyday workflows. Independently built engine with… |

<details>
<summary>Show 10 more</summary>

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**mjasnikovs/pi-task**](https://github.com/mjasnikovs/pi-task) | 145 | TypeScript | 2026-10-24 | Deterministic spec-orchestration for local LLMs in the pi coding agent — drives prompts through refine→resear… |
| 12 | [**nathansutton/chad**](https://github.com/nathansutton/chad) | 143 | Python | 2026-10-26 | chad: a coding agent for your macbook pro |
| 13 | [**L-Forster/open-jet**](https://github.com/L-Forster/open-jet) | 129 | Python | 2026-10-29 | An offline coding agent for local models. One command sets up the best model your GPU can run, and on 24 GB+… |
| 14 | [**templetongroup/radiant**](https://github.com/templetongroup/radiant) | 117 | JavaScript | 2026-10-29 | A local coding harness for Mac. Chat with coding agents across cloud and local models, watch every tool call… |
| 15 | [**slaveOftime/open-relay**](https://github.com/slaveOftime/open-relay) | 109 | Rust | 2026-10-30 | oly runs coding agents and long-running commands in persistent, supervised terminal sessions. The daemon owns… |
| 16 | [**sergezuber/FABULA-LLM-5**](https://github.com/sergezuber/FABULA-LLM-5) | 82 | TypeScript | 2026-09-22 | A local-first coding agent that doesn't take "done" on faith: the engine keeps the run going until the projec… |
| 17 | [**Ninnix/q36**](https://github.com/Ninnix/q36) | 76 | C | 2026-10-27 | Qwen3.8-27B and Qwen3.6-35B-A3B local inference engine for Vulkan and Metal |
| 18 | [**raullenchai/rapid-mlx-dsh-provider**](https://github.com/raullenchai/rapid-mlx-dsh-provider) | 70 | JavaScript | 2026-08-19 | Native Rapid-MLX provider for DeepSeek Harness (dsh) — dsh reads model facts from the server instead of your… |
| 19 | [**RealDealCPA-VR/Iron-Jarvis**](https://github.com/RealDealCPA-VR/Iron-Jarvis) | 65 | Python | 2026-10-30 | A local-first AI control plane for orchestrating agents, models, tools, and machines from one desktop app. |
| 20 | [**MuhammadUsmanGM/code-stick**](https://github.com/MuhammadUsmanGM/code-stick) | 63 | TypeScript | 2026-05-21 | Plug in a USB. Get an offline AI coding agent on any laptop - Windows, macOS, Linux. opencode + Ollama, pre-b… |

</details>

<a id="sec-4"></a>

## Run LFM2.5 on Your Machine

| # | Project | ⭐ Stars | Language | Updated | Description |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**Liquid4All/LeapSDK-Examples**](https://github.com/Liquid4All/LeapSDK-Examples) | 77 | Kotlin | 2026-10-08 | Example apps for LeapSDK |
| 2 | [**maximecb/bebelm**](https://github.com/maximecb/bebelm) | 69 | Rust | 2026-06-16 | CPU-only, pure-Rust implementation of LiquidAI's LFM2.5-8B-A1B LLM |
| 3 | [**gyunggyung/Tiny-MoA**](https://github.com/gyunggyung/Tiny-MoA) | 39 | Python | 2026-02-07 | Running Mixture of Agents on CPU: LFM2.5 Brain (1.2B) + Falcon-R Reasoner (600M) + Tool Caller (90M). CPU-onl… |

<a id="about"></a>

## 📖 About this list

This list is collected from GitHub, deduplicated, link-checked and ranked by stars (recency breaks ties). It is regenerated automatically on a schedule, so numbers stay fresh.

---

<div align="center">

<sub>Auto-generated · refreshed on a schedule · ranked by GitHub stars · 2026-10-30</sub>

</div>
