# hermes-AntiVenom
Zero-latency epistemic immune system and threat interception engine for Nous Hermes and local AI agents. Neutralizes Indirect Prompt Injection (IPI) with 0 added context tokens.

# 🐍 Hermes AntiVenom

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)
[![Target Model](https://img.shields.io/badge/Target-Nous%20Hermes%203-orange.svg)](https://nousresearch.com/)
[![Latency Overhead](https://img.shields.io/badge/Latency-%3C1ms-brightgreen.svg)]()
[![Token Overhead](https://img.shields.io/badge/Token%20Cost-0%20Tokens-brightgreen.svg)]()

> **The Epistemic Immune System for Autonomous AI Agents.** > *Hermes AntiVenom is a zero-latency, deterministic threat interception middleware that neutralizes Indirect Prompt Injections (IPI) and Unicode steganography before toxic payloads can hijack tool execution.*

---

## ⚡ Why Hermes AntiVenom?

| Feature | System Prompt Guardrails (`skill.md`) | Dual-LLM Evaluators | 🐍 Hermes AntiVenom |
| :--- | :---: | :---: | :---: |
| **Token Cost** | ❌ High (Always added to context) | ❌ 2x Token Cost | **🟢 0 Tokens Added** |
| **Execution Latency** | ⚠️ Moderate | ❌ +1000ms to +2000ms | **🟢 <1ms Overhead** |
| **Attention Hijack Proof** | ❌ Fails on long inputs | ⚠️ Varies | **🟢 Deterministic Circuit Breaker** |
| **Steganography Scrubbing** | ❌ Tokenizer is blind | ❌ Tokenizer is blind | **🟢 Native Python Detox** |
| **Agent Recovery** | ❌ Crashes or obeys attack | ❌ Blocks whole request | **🟢 Self-Preservation Feedback** |

---

## 🚀 Quick Start in 60 Seconds

```bash
pip install hermes-antivenom

