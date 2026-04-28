<div align="center">

# 🛠️ Crafted LLMs Portfolio
**Fine-tuning, Model Merging, Quantization & SLMs**

[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/TitleOS)

</div>

---

## About This Collection

This repository serves as a living portfolio of my work with Large and Small Language Models. My research bridges the gap between theoretical architectures and practical daily use. I focus heavily on local home automation control, experimental model distillation, and outfitting older architectures with modern reasoning capabilities.

---

## Model Showcase

### 🛡️ Purple Team & Secure Coder Models

> **Highlight:** `Eve-4B` scores **26.22%** on Pass@1 (LCB), outperforming existing models 5 to 30 times its size including Mixtral-8x22B and Mistral-Large. 

I developed a custom dataset using a unique ratioed combination of sources like `samantha-data`, `hermes-function-calling-v1`, and `Code_Vulnerability_Security_DPO`. Training a heretic version of Qwen 3 4B on this data produced Eve-4B. The heretic method applied before fine-tuning successfully restored minor intelligence damage often caused by the process. Eve can identify and patch CVEs just as easily as it can write ransomware. It operates without refusals and utilizes function calling seamlessly.

| Model Name | Role | Description | Link |
| :--- | :--- | :--- | :--- |
| **Eve-4B** | Small Secure Coder | A purple-teaming model that punches above its weight class. Runs GPT-3.5-Turbo level performance on a laptop with <5GB RAM. Uncensored, agentic, and built for tools. | [View Collection](https://huggingface.co/collections/TitleOS/eve-4b-small-secure-coder) |
| **Metis-4B** | Purple Utility Agent | Sister model to Eve-4B based on Heretic'd Qwen 3.5-4B. Optimized for desktop and CLI usage as an offensive-aware utility agent. | *Private* |

### 🎓 Efficient & Distilled Models (Teacher-Student)

This collection showcases my work with the "Textbooks Are All You Need" methodology. It focuses on creating highly efficient Micro Utility models via synthetic data distillation.

| Model Name | Role | Description | Link |
| :--- | :--- | :--- | :--- |
| **Lightning-1.7B** | The Teacher | High-efficiency sidecar model based on Qwen3-1.7B. Generates synthetic training data for the Spark series. | [![Model](https://img.shields.io/badge/🤗-Open_Model-blue)](https://huggingface.co/TitleOS/Lightning-1.7B-Q8_0-GGUF) |
| **Spark-270m** | The Student | 270M parameter Gemma 3 derivative. Inherits Hermes 3 creativity but is optimized specifically for summarization and query generation. | [![Model](https://img.shields.io/badge/🤗-Open_Model-blue)](https://huggingface.co/TitleOS/Spark-270M-FP16) |

### 🏠 Specialized Models

| Model Name | Description | Link |
| :--- | :--- | :--- |
| **HomePhi4** | Phi-4-mini-reasoning fine-tuned for reasoning-based local home control. Available in FP16 and GGUF. | [![Collection](https://img.shields.io/badge/🤗-Collection-red)](https://huggingface.co/collections/TitleOS/homephi4-home-assistant-reasoning-llm-67634f31c237890f50767172) |
| **HomeGem4Bn** | A conversational 4-bit Gemma 3n-e4b fine-tune optimized to control Home Assistant environments locally. | [![Model](https://img.shields.io/badge/🤗-Open_Model-red)](https://huggingface.co/TitleOS/HomeGem4Bn) |
| **MindGem27B** | A LoRA experiment bringing Chain of Thought (CoT) and reasoning capabilities to Gemma 3 27B. | [![Model](https://img.shields.io/badge/🤗-Open_Model-blue)](https://huggingface.co/TitleOS/MindGem27B) |
| **LokiHA-2B** | A helpful, sassy, and theatrical Qwen3.5-2B fine-tune built for CPU-based Home Assistant actions and natural conversation. | [![Model](https://img.shields.io/badge/🤗-Open_Model-yellow)](https://huggingface.co/TitleOS/LokiHA-2B-FP32) |
| **ADBait-1B** | Built on granite-4.0-h-1b. Powers a dynamic Android 14 Debug Bridge honeypot with realistic CLI responses. | [![Collection](https://img.shields.io/badge/🤗-Collection-green)](https://huggingface.co/collections/TitleOS/adbait-1b-android-14-debug-bridge-dynamic-honeypot) |

### 🔬 Experimental & Research

| Model Name | Description | Link |
| :--- | :--- | :--- |
| **Galactic Reasoning** | Modernizing Meta's OPT-based Galactica by adding Chain of Thought reasoning via LoRA adapters. | [![Collection](https://img.shields.io/badge/🤗-Collection-blue)](https://huggingface.co/collections/TitleOS/galactic-reasoning-galactica-with-chain-of-thought) |
| **Elohim-3.8B** | A non-biased religious scholar model based on Phi-4-Mini-Reasoning. Trained on 1500 distilled English Torah and Quran pairs. | [![Collection](https://img.shields.io/badge/🤗-Collection-pink)](https://huggingface.co/collections/TitleOS/elohim-38b-jewish-and-islamic-english-scholar) |
| **Seahorse 350m** | A compact text generation model trained on OPT using Alpaca. | [![Model](https://img.shields.io/badge/🤗-Open_Model-blue)](https://huggingface.co/TitleOS/Seahorse-350m) |

---

## 🔓 Decensoring & Jailbreaking

| Model Name | Description | Link |
| :--- | :--- | :--- |
| **Gwen3 Coder 30B A3B** | A collection of decensored Qwen3 Coder 30B A3B models. Decensoring performed using Heretic. Available in original FP16 and quantizations. | [![Collection](https://img.shields.io/badge/🤗-Collection-blue)](https://huggingface.co/collections/TitleOS/qwen3-coder-heretic-decensored) |

---

## 🗄️ Datasets

I curate and release specialized datasets used to train specific behaviors and agentic capabilities.

* **[Eve-Secure-Coder](https://huggingface.co/datasets/TitleOS/Eve-Secure-Coder):** A composite dataset curated to fine-tune Qwen3-4b-Heretic into a security-conscious coding assistant. Bridges the gap between robotic coding tools and engaging conversational AI without sacrificing technical accuracy.
* **[Metis-Purple-Utility-Agent](https://huggingface.co/datasets/TitleOS/Metis-Purple-Utility-Agent):** An offensive-aware utility agent dataset built on Eve-Secure-Coder. Augmented with CLI commands, terminal explanations, and configuration languages like Docker.
* **[ADB-CursedHoneyComb](https://huggingface.co/datasets/TitleOS/ADB-CursedHoneyComb):** A collection of 250 Android ADB commands with realistic output for an Android 14 system. Includes fake popular user and system apps to enable dynamic modern honeypots.
* **[Scripture_1500_pairs_gemini_flash_lite](https://huggingface.co/datasets/TitleOS/scripture_1500_pairs_gemini_flash_lite):** 1500 pairs distilled by Gemini 3.1 Flash Lite from an English translation of the Torah and Quran. Used to train Elohim-3.8B.
* **[RocketRaccoon Personality Alpaca](https://huggingface.co/datasets/TitleOS/rocketraccoon_personality_alpaca):** A personality-driven dataset used to imbue models with a specific character voice in the Alpaca style.

---

## 🧠 Featured Methodologies

### Eve-4B: Beating the Heavyweights
My Eve-4B model demonstrates the raw impact of quality data. The fine-tuning process successfully repaired damage done by heretic processes. I trained Eve-4B for $5 on vast.ai, proving that high-performance custom LLMs are accessible to anyone with the right data. I plan to apply an updated Eve-Secure-Coder dataset focusing on computer usage knowledge to Qwen3.5-4B soon.

| Model | Parameter Size / Tier | Approximate Pass@1 |
| :--- | :--- | :--- |
| LLama-3-70b-Instruct | 70B | ~28.3% |
| GPT-4o-mini (2024-07) | Small Proprietary | ~27.7% |
| Claude 3 Sonnet | Large Proprietary | ~26.9% |
| Mixtral-8x22B-Instruct | 141B (MoE) | ~26.4% |
| **Eve-4B (Q8_0)** | **4B (Quantized)** | **26.22%** |
| Mistral-Large | Large Proprietary | ~26.0% |
| GPT-3.5-Turbo-0125 | Mid Proprietary | ~24.6% |
| Claude 3 Haiku | Small Proprietary | ~24.5% |
| Codestral-Latest | 22B | ~23.8% |
| Llama-3-8b-Instruct | 8B | ~15.3% |

### Local AI for Home Assistant
A major focus of my early work was enabling high-quality, privacy-focused AI for local environments. **HomePhi4** leverages the reasoning capabilities of Phi-4-mini to understand complex user intents. **HomeGem** provides a lightweight conversational interface based on Gemma. 

Recently, I produced **LokiHA**, a Small Language Model designed to run entirely via CPU directly on the Home Assistant host. It utilizes the `acon96/Home-Assistant-Requests-V2` dataset combined with a custom personality dataset to create a helpful, snarky, and theatrical assistant.

### ADBait-1B: Dynamic Android 14 Honeypot
Another recent SLM focus is CPU-based deployment without GPU acceleration. ADBait-1B is trained on my custom `ADB-CursedHoneycomb` dataset to generate realistic responses to ADB commands. Care was taken to include popular app packages like Call of Duty Mobile and WhatsApp alongside default system apps. The engine powers the [ADBNectar Honeypot](https://github.com/TitleOS/ADBNectar). It builds a Docker container supporting both CUDA and CPU-only environments. Files pushed by ADB are automatically zipped and encrypted to prevent local anti-virus interference.

---

<div align="center">

**[Hugging Face](https://huggingface.co/TitleOS) • [Blog](https://blog.titleos.dev) • [BlueSky](https://bsky.app/profile/titleos.dev)**

*If you have questions about training methodologies, datasets, or specific model weights, feel free to reach out.*

</div>
