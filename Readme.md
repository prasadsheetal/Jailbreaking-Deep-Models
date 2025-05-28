# 🔓 Jailbreaking Deep Models

## Overview

This repository investigates **jailbreaking techniques** to bypass alignment constraints in Large Language Models (LLMs) using prompt engineering and adversarial strategies. Our goal is to evaluate and understand the vulnerabilities of widely used models like ChatGPT and Claude under unsafe prompting conditions and explore the limitations of current alignment mechanisms.

---

## Features

- **Prompt-Based Jailbreaking:** Multiple attack categories including roleplay, encoding, obfuscation, and prompt reversal.
- **Red-Teaming Automation:** Scripted simulation of adversarial prompts across model APIs.
- **Attack Taxonomy:** Categorized test suite of jailbreak patterns and variants.
- **Evaluation Framework:** Tracks success rates, response types, and alignment breaches.
- **Model Agnostic:** Designed to work with OpenAI, Claude, and open-source models like LLaMA or Mistral (where API/token access is permitted).

---

## Installation

```bash
git clone https://github.com/prasadsheetal/Jailbreaking-Deep-Models.git
cd Jailbreaking-Deep-Models
pip install -r requirements.txt



