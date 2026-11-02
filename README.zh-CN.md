<div align="center">

<img src="banner.svg" width="100%" alt="开源权重编程模型与本地运行大全"/>

# 开源权重编程模型与本地运行大全

<p><i>开源权重的编程与 Agent 模型（Qwen Coder、DeepSeek、GLM、Kimi、Devstral、StarCoder），以及本地运行工具 llama.cpp、Ollama、vLLM、MLX，按 GitHub Stars 排名</i></p>

![Ranked by GitHub stars](https://img.shields.io/badge/ranked%20by-GitHub%20stars-orange?style=for-the-badge) ![GitHub stars](https://img.shields.io/badge/%E2%AD%90%20stars-repo-black?style=for-the-badge) ![License](https://img.shields.io/badge/license-CC0-0a7bbb?style=for-the-badge)

![条目](https://img.shields.io/badge/%E6%9D%A1%E7%9B%AE-63-blueviolet?style=for-the-badge) ![总 Stars](https://img.shields.io/badge/%E6%80%BB%20Stars-1.3M-gold?style=for-the-badge) ![更新于](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E4%BA%8E-2026--11--02-brightgreen?style=for-the-badge)

[English](README.md) · **简体中文**

</div>

---

> **为什么是现在:** 同一周里出了三个开源权重模型：Reflection 的 [Beam](https://reflection.ai/blog/beam-is-available)（501B MoE，激活 23B，Apache 2.0，10 月 16 日放出权重）、[DeepSeek V4.1-Flash-1017](https://api-docs.deepseek.com/news/news261017/)（10 月 17 日）和 Liquid AI 的 [LFM2.5-24B-A2B](https://www.liquid.ai/blog/lfm2-5-24b-a2b)（10 月 14 日，激活 2B，面向端侧 Agent）。这三个模型都没有自己的 GitHub 仓库，所以在这里点名，不进下面的排名。据报道 Beam 首日即支持 vLLM 和 SGLang（见下方排名），第一个分区收录了能运行 LFM2.5 的 GitHub 项目。下面排的是让你在自己电脑上跑这类模型的 GitHub 项目。

---

## 目录

- [🏆 精选 Top](#top-picks)
- [Local Inference Engines](#sec-1) · 20
- [Open-Weight Coding & Agent Models](#sec-2) · 20
- [Local Coding Agents & IDE Plugins](#sec-3) · 20
- [Run LFM2.5 on Your Machine](#sec-4) · 3
- [📖 关于本列表](#about)

<a id="top-picks"></a>

## 🏆 精选 Top

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ollama/ollama**](https://github.com/ollama/ollama) | 185.6k | Go | 2026-11-02 | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. |
| 2 | [**ggml-org/llama.cpp**](https://github.com/ggml-org/llama.cpp) | 133.1k | C++ | 2026-11-02 | LLM inference in C/C++ |
| 3 | [**deepseek-ai/DeepSeek-V3**](https://github.com/deepseek-ai/DeepSeek-V3) | 104.7k | Python | 2025-08-28 | — |
| 4 | [**vllm-project/vllm**](https://github.com/vllm-project/vllm) | 96.1k | Python | 2026-11-02 | A high-throughput and memory-efficient inference and serving engine for LLMs |
| 5 | [**deepseek-ai/DeepSeek-R1**](https://github.com/deepseek-ai/DeepSeek-R1) | 92.0k | — | 2025-06-27 | — |

<a id="sec-1"></a>

## Local Inference Engines

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**ollama/ollama**](https://github.com/ollama/ollama) | 185.6k | Go | 2026-11-02 | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. |
| 2 | [**ggml-org/llama.cpp**](https://github.com/ggml-org/llama.cpp) | 133.1k | C++ | 2026-11-02 | LLM inference in C/C++ |
| 3 | [**vllm-project/vllm**](https://github.com/vllm-project/vllm) | 96.1k | Python | 2026-11-02 | A high-throughput and memory-efficient inference and serving engine for LLMs |
| 4 | [**nomic-ai/gpt4all**](https://github.com/nomic-ai/gpt4all) | 77.3k | C++ | 2025-05-27 | GPT4All: Run Local LLMs on Any Device. Open-source and available for commercial use. |
| 5 | [**CherryHQ/cherry-studio**](https://github.com/CherryHQ/cherry-studio) | 53.2k | TypeScript | 2026-11-02 | Your AI workspace for models, agents, and productivity. |
| 6 | [**exo-explore/exo**](https://github.com/exo-explore/exo) | 48.1k | Python | 2026-11-02 | Run frontier AI locally. |
| 7 | [**AlexsJones/llmfit**](https://github.com/AlexsJones/llmfit) | 38.6k | Rust | 2026-11-02 | Hundreds of models & providers. One command to find what runs on your hardware. |
| 8 | [**sgl-project/sglang**](https://github.com/sgl-project/sglang) | 38.4k | Python | 2026-11-02 | SGLang is a high-performance serving framework for large language models and multimodal models. |
| 9 | [**ml-explore/mlx**](https://github.com/ml-explore/mlx) | 29.0k | C++ | 2026-11-01 | MLX: An array framework for Apple silicon |
| 10 | [**mozilla-ai/llamafile**](https://github.com/mozilla-ai/llamafile) | 26.5k | C++ | 2026-10-12 | Distribute and run LLMs with a single file. |

<details>
<summary>展开其余 10 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**jundot/omlx**](https://github.com/jundot/omlx) | 23.3k | Python | 2026-11-02 | LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu b… |
| 12 | [**Lightning-AI/litgpt**](https://github.com/Lightning-AI/litgpt) | 13.7k | Python | 2026-11-01 | 20+ high-performance LLMs with recipes to pretrain, finetune and deploy at scale. |
| 13 | [**bentoml/OpenLLM**](https://github.com/bentoml/OpenLLM) | 12.6k | Python | 2026-10-26 | Run any open-source LLMs, such as DeepSeek and Llama, as OpenAI compatible API endpoint in the cloud. |
| 14 | [**openvinotoolkit/openvino**](https://github.com/openvinotoolkit/openvino) | 11.1k | C++ | 2026-11-02 | OpenVINO™ is an open source toolkit for optimizing and deploying AI inference |
| 15 | [**RunanywhereAI/runanywhere-sdks**](https://github.com/RunanywhereAI/runanywhere-sdks) | 10.3k | C++ | 2026-11-02 | Production ready toolkit to run AI locally |
| 16 | [**Tiiny-AI/PowerInfer**](https://github.com/Tiiny-AI/PowerInfer) | 9.9k | C++ | 2026-05-11 | High-speed Large Language Model Serving for Local Deployment |
| 17 | [**xorbitsai/inference**](https://github.com/xorbitsai/inference) | 9.6k | Python | 2026-11-02 | Swap GPT for any LLM by changing a single line of code. Xinference lets you run open-source, speech, and mult… |
| 18 | [**FareedKhan-dev/kimi-k3-in-c**](https://github.com/FareedKhan-dev/kimi-k3-in-c) | 9.3k | C | 2026-10-02 | A 2.78-trillion-parameter Kimi K3 running inference on a single CPU in 8.24 GB of RAM. Portable C99: no BLAS,… |
| 19 | [**InternLM/lmdeploy**](https://github.com/InternLM/lmdeploy) | 8.1k | Python | 2026-10-30 | LMDeploy is a toolkit for compressing, deploying, and serving LLMs. |
| 20 | [**ml-explore/mlx-lm**](https://github.com/ml-explore/mlx-lm) | 7.5k | Python | 2026-10-30 | Run LLMs with MLX |

</details>

<a id="sec-2"></a>

## Open-Weight Coding & Agent Models

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**deepseek-ai/DeepSeek-V3**](https://github.com/deepseek-ai/DeepSeek-V3) | 104.7k | Python | 2025-08-28 | — |
| 2 | [**deepseek-ai/DeepSeek-R1**](https://github.com/deepseek-ai/DeepSeek-R1) | 92.0k | — | 2025-06-27 | — |
| 3 | [**QwenLM/qwen-code**](https://github.com/QwenLM/qwen-code) | 28.9k | TypeScript | 2026-11-02 | An open-source AI coding agent that lives in your terminal. |
| 4 | [**QwenLM/Qwen3**](https://github.com/QwenLM/Qwen3) | 27.7k | Python | 2026-01-09 | Qwen3 is the large language model series developed by Qwen team, Alibaba Cloud. |
| 5 | [**deepseek-ai/DeepSeek-Coder**](https://github.com/deepseek-ai/DeepSeek-Coder) | 24.3k | Python | 2025-11-11 | DeepSeek Coder: Let the Code Write Itself |
| 6 | [**QwenLM/Qwen**](https://github.com/QwenLM/Qwen) | 22.0k | Python | 2026-03-05 | The official repo of Qwen (通义千问) chat & pretrained large language model proposed by Alibaba Cloud. |
| 7 | [**QwenLM/Qwen3-Coder**](https://github.com/QwenLM/Qwen3-Coder) | 16.8k | Python | 2026-03-24 | Qwen3-Coder is the code version of Qwen3, the large language model series developed by Qwen team. |
| 8 | [**MoonshotAI/Kimi-K2**](https://github.com/MoonshotAI/Kimi-K2) | 11.1k | — | 2026-01-21 | Kimi K2 is the large language model series developed by Moonshot AI team |
| 9 | [**zai-org/GLM-5**](https://github.com/zai-org/GLM-5) | 7.4k | — | 2026-10-15 | GLM-5: From Vibe Coding to Agentic Engineering |
| 10 | [**deepseek-ai/DeepSeek-LLM**](https://github.com/deepseek-ai/DeepSeek-LLM) | 7.3k | Makefile | 2024-02-04 | DeepSeek LLM: Let there be answers |

<details>
<summary>展开其余 10 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**deepseek-ai/DeepSeek-Coder-V2**](https://github.com/deepseek-ai/DeepSeek-Coder-V2) | 7.0k | — | 2025-11-11 | DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence |
| 12 | [**deepseek-ai/DeepSeek-V2**](https://github.com/deepseek-ai/DeepSeek-V2) | 5.1k | — | 2024-09-25 | DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model |
| 13 | [**gptme/gptme**](https://github.com/gptme/gptme) | 4.5k | Python | 2026-11-02 | Your agent in your terminal, equipped with local tools: writes code, uses the terminal, browses the web. Make… |
| 14 | [**zai-org/GLM-4.5**](https://github.com/zai-org/GLM-4.5) | 4.4k | Python | 2026-02-01 | GLM-4.5: Agentic, Reasoning, and Coding (ARC) Foundation Models |
| 15 | [**QwenLM/Qwen3.8**](https://github.com/QwenLM/Qwen3.8) | 4.4k | — | 2026-08-17 | Qwen3.8 is the large language model series developed by Qwen team, Alibaba Group. |
| 16 | [**twinnydotdev/twinny**](https://github.com/twinnydotdev/twinny) | 3.7k | TypeScript | 2026-10-16 | Open-source AI coding assistant for VS Code. Coding agent, code completion, chat, edits and reviews with loca… |
| 17 | [**bigcode-project/starcoder2**](https://github.com/bigcode-project/starcoder2) | 2.1k | Python | 2024-03-21 | Home of StarCoder2! |
| 18 | [**huggingface/llm-ls**](https://github.com/huggingface/llm-ls) | 882 | Rust | 2026-09-23 | LSP server leveraging LLMs for code completion (and more?) |
| 19 | [**bin123apple/AutoCoder**](https://github.com/bin123apple/AutoCoder) | 847 | Python | 2024-07-06 | We introduced a new model designed for the Code generation task. Its test accuracy on the HumanEval base data… |
| 20 | [**Fast-Editor/Lynkr**](https://github.com/Fast-Editor/Lynkr) | 639 | JavaScript | 2026-10-31 | Streamline your workflow with Lynkr, a CLI tool that acts as an HTTP proxy for efficient code interactions us… |

</details>

<a id="sec-3"></a>

## Local Coding Agents & IDE Plugins

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**continuedev/continue**](https://github.com/continuedev/continue) | 36.4k | TypeScript | 2026-11-01 | open-source coding agent |
| 2 | [**TabbyML/tabby**](https://github.com/TabbyML/tabby) | 33.9k | Rust | 2026-06-30 | Self-hosted AI coding assistant |
| 3 | [**itayinbarr/little-coder**](https://github.com/itayinbarr/little-coder) | 2.7k | TypeScript | 2026-09-18 | A harness optimized to smaller LLMs |
| 4 | [**ggml-org/llama.vscode**](https://github.com/ggml-org/llama.vscode) | 1.5k | TypeScript | 2026-11-01 | VS Code extension for LLM-assisted code/text completion |
| 5 | [**xNul/code-llama-for-vscode**](https://github.com/xNul/code-llama-for-vscode) | 568 | Python | 2024-07-31 | Use Code Llama with Visual Studio Code and the Continue extension. A local LLM alternative to GitHub Copilot. |
| 6 | [**danishashko/geo-aeo-tracker**](https://github.com/danishashko/geo-aeo-tracker) | 315 | TypeScript | 2026-10-19 | Open-source AI visibility tracker. Track how ChatGPT, Perplexity, Gemini, Copilot and Google AI Mode mention… |
| 7 | [**plaxtoris/codehamr**](https://github.com/plaxtoris/codehamr) | 222 | Go | 2026-09-25 | A minimal, local-first coding agent for the terminal. |
| 8 | [**autohandai/code-cli**](https://github.com/autohandai/code-cli) | 214 | TypeScript | 2026-11-02 | Open-source terminal coding agent. Use 15+ model providers, local models or your own key. Plan mode before ed… |
| 9 | [**AlysisAi/AlysisCode**](https://github.com/AlysisAi/AlysisCode) | 188 | Python | 2026-11-01 | Open-source, multi-model agent for coding, research, and everyday workflows. Independently built engine with… |
| 10 | [**mjasnikovs/pi-task**](https://github.com/mjasnikovs/pi-task) | 147 | TypeScript | 2026-10-24 | Deterministic spec-orchestration for local LLMs in the pi coding agent — drives prompts through refine→resear… |

<details>
<summary>展开其余 10 项</summary>

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 11 | [**nathansutton/chad**](https://github.com/nathansutton/chad) | 143 | Python | 2026-10-31 | chad: a coding agent for your macbook pro |
| 12 | [**L-Forster/open-jet**](https://github.com/L-Forster/open-jet) | 130 | Python | 2026-11-01 | An offline coding agent for local models. One command sets up the best model your GPU can run, and on 24 GB+… |
| 13 | [**templetongroup/radiant**](https://github.com/templetongroup/radiant) | 117 | JavaScript | 2026-10-29 | A local coding harness for Mac. Chat with coding agents across cloud and local models, watch every tool call… |
| 14 | [**slaveOftime/open-relay**](https://github.com/slaveOftime/open-relay) | 109 | Rust | 2026-10-30 | oly runs coding agents and long-running commands in persistent, supervised terminal sessions. The daemon owns… |
| 15 | [**KenKaiii/gg-framework**](https://github.com/KenKaiii/gg-framework) | 94 | TypeScript | 2026-11-01 | The coding agent that gets more out of your AI subscription. Fastest and leanest of 20 agents tested, with un… |
| 16 | [**drawthingsai/local-code-community**](https://github.com/drawthingsai/local-code-community) | 85 | C | 2026-11-02 | Source code of Local Code, a private AI agent for Mac, iPad and iPhone. Runs DeepSeek 4.1 on device, with Pyt… |
| 17 | [**sergezuber/FABULA-LLM-5**](https://github.com/sergezuber/FABULA-LLM-5) | 82 | TypeScript | 2026-09-22 | A local-first coding agent that doesn't take "done" on faith: the engine keeps the run going until the projec… |
| 18 | [**Ninnix/q36**](https://github.com/Ninnix/q36) | 77 | C | 2026-10-30 | Qwen3.8-27B and Qwen3.6-35B-A3B local inference engine for Vulkan and Metal |
| 19 | [**raullenchai/rapid-mlx-dsh-provider**](https://github.com/raullenchai/rapid-mlx-dsh-provider) | 70 | JavaScript | 2026-08-19 | Native Rapid-MLX provider for DeepSeek Harness (dsh) — dsh reads model facts from the server instead of your… |
| 20 | [**RealDealCPA-VR/Iron-Jarvis**](https://github.com/RealDealCPA-VR/Iron-Jarvis) | 65 | Python | 2026-11-02 | A local-first AI control plane for orchestrating agents, models, tools, and machines from one desktop app. |

</details>

<a id="sec-4"></a>

## Run LFM2.5 on Your Machine

| # | 项目 | ⭐ Stars | 语言 | 更新 | 简介 |
|:-:|:--|--:|:-:|:-:|:--|
| 1 | [**Liquid4All/LeapSDK-Examples**](https://github.com/Liquid4All/LeapSDK-Examples) | 77 | Kotlin | 2026-10-08 | Example apps for LeapSDK |
| 2 | [**maximecb/bebelm**](https://github.com/maximecb/bebelm) | 70 | Rust | 2026-06-16 | CPU-only, pure-Rust implementation of LiquidAI's LFM2.5-8B-A1B LLM |
| 3 | [**gyunggyung/Tiny-MoA**](https://github.com/gyunggyung/Tiny-MoA) | 39 | Python | 2026-02-07 | Running Mixture of Agents on CPU: LFM2.5 Brain (1.2B) + Falcon-R Reasoner (600M) + Tool Caller (90M). CPU-onl… |

<a id="about"></a>

## 📖 关于本列表

本列表从 GitHub 自动采集，经过去重、链接检查，按 Stars 排名（Stars 相同时按最近更新排序），并定时自动刷新，数据始终保持最新。

---

<div align="center">

<sub>自动生成 · 定时刷新 · 按 GitHub Stars 排名 · 2026-11-02</sub>

</div>
