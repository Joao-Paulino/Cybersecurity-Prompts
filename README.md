# 🛡️ Cybersecurity-Prompts

> **AI prompts that turn security analysts into augmented operators.**
> This is not a list of curiosities. It's a prompt-engineering arsenal for SOC, Red Team, Blue Team, DFIR, and cybersecurity research.

---

## ⚡ Why this repository exists

Generative AI has already entered the SOC. The problem isn't the tool — it's the **quality of the instruction**.

A poorly written prompt produces hallucinations, data leaks, and false confidence. A well-structured prompt produces **faster triage, clearer reports, and more rigorous investigations**.

This repository curates the best open-source **cybersecurity prompt** projects, focused on:

- **Data safety** — anonymization before sending logs to LLMs
- **Methodology** — Chain-of-Thought, Chain-of-Verification, frameworks like PECIS
- **Real-world application** — SOC L1/L2, threat hunting, pentesting, DFIR, compliance
- **Technical rigor** — structured outputs (JSON, tables), MITRE ATT&CK mapping, CWE references

---

## 🎯 Featured repositories

### 1. 🔐 [AI-Cybersecurity-Prompts](https://github.com/novasntnl/AI-Cybersecurity-Prompts)

**The mandatory starting point.**

Over 50 safe prompts focused on SOC, threat hunting, and incident response. The differentiator is the **sanitization/tokenization scripts**: you learn how to strip real IPs, usernames, and credentials **before** sending logs to AI.

> **Best for:** analysts who want to use AI in real work without violating data policies.

---

### 2. 🧠 [ULTIMATE-CYBERSECURITY-MASTER-GUIDE](https://github.com/Pnwcomputers/ULTIMATE-CYBERSECURITY-MASTER-GUIDE)

**For those who want to write enterprise-grade prompts.**

A prompting guide for security professionals with a **Master System Prompt** template, **Chain-of-Thought** and **Chain-of-Verification** techniques, plus a curated list of classic tools (Metasploit, Nmap, Volatility, Ghidra).

> ⚠️ **Note:** check the specific prompts section when you access it — the repository also contains a lot of tooling and legal-document content.

> **Best for:** anyone who needs more rigorous, lower-hallucination responses in triage and analysis.

---

### 3. 🔬 [AI-Prompt-Engineering-for-Cybersecurity-Research](https://github.com/maramraboudi/AI-Prompt-Engineering-for-Cybersecurity-Research)

**Prompting meets applied research.**

Specialized in prompts for **cybersecurity research**, using the **PECIS** framework and **Chain-of-Thought (CoT)**. Clear structure, academically grounded.

> **Best for:** researchers, graduate students, and anyone who wants to understand *why* a prompt works.

---

### 4. 🤖 [CyberSec-GenAI](https://github.com/VladTepes84/CyberSec-GenAI)

**A ready-to-use system prompt for Red Team and Blue Team.**

Provides a **complete cybersecurity analyst system prompt**, ready to paste into Gemini or ChatGPT. Covers both offensive and defensive perspectives.

> **Best for:** those who want to start immediately with an AI assistant configured for security.

---

## 🧭 How to use this repository

| Goal | Start with |
|---|---|
| Apply AI in the SOC with data safety | **AI-Cybersecurity-Prompts** |
| Write rigorous enterprise prompts | **ULTIMATE-CYBERSECURITY-MASTER-GUIDE** |
| Research and ground your prompting | **AI-Prompt-Engineering-for-Cybersecurity-Research** |
| Get a ready-made Red/Blue Team assistant | **CyberSec-GenAI** |

---

## 🧩 Principles of a good cybersecurity prompt

1. **Define the role** — "You are an experienced SOC L2 analyst…"
2. **Delimit context** — separate instructions from data with `### INSTRUCTIONS ###` and `### DATA ###`
3. **Demand format** — table, JSON, severity-ranked list
4. **Ask for citations** — instruct the model to cite its source or write "unknown"
5. **Anonymize** — never paste real IPs, credentials, or internal URLs into public tools
6. **Verify** — use Chain-of-Verification to reduce hallucinations

---

## ⚠️ Security notice

> **Never** send sensitive data (real IPs, credentials, usernames, internal URLs) to public AI models.
> Use synthetic data, anonymization, or local/private instances.
> Data-handling responsibility always rests with the operator.

---

## 🤝 Contributing

Found a cybersecurity prompt repository that deserves a spotlight?
Open an **issue** or submit a **pull request** with:

- Repository name and link
- Focus area (SOC, Red Team, DFIR, compliance…)
- Technical differentiator
- Maturity level (experimental / production)

---

## 📜 License

The content of this README is available under the **MIT License**.
Each listed repository keeps its own license — check before reusing.

---

<p align="center">
  <strong>A well-written prompt is a security tool.<br/>A poorly written prompt is a vulnerability.</strong>
</p>
