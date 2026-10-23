# Alpie-Core × Team Transformer

**Forked for community contribution during Preptember / Hacktoberfest 2026**

---

## 🧠 About Alpie-Core

Alpie-Core is India’s first 4-bit quantized reasoning model — designed to deliver strong multi-step reasoning and coding performance while running efficiently on consumer hardware.

This fork exists as part of **Team Transformer**’s contribution to the 169Pi ecosystem.

---

## 🚀 Our Project: Quorum

**Quorum** is an adversarial, calibrated CVE triage system built for the **169Pi Track** at Hacktoberfest Hack Day Hamirpur × GDG Ludhiana.

Instead of trusting a model’s self-reported confidence, Quorum forces three AI personas (Proposer, Red Team, Referee) to argue over deterministic facts extracted from a codebase. Confidence is measured by agreement across multiple seeded runs.

### Dual Backend Support
- **Primary:** Local Gemma models via Ollama (fully offline)
- **Secondary:** 169Pi Playground API using **Alpie-Core**

The system can automatically fall back to Alpie-Core when local inference is unavailable, or be pinned to Alpie-Core entirely.

🔗 **Repository:** [Team-transformer/quorum-cve-triage](https://github.com/Team-transformer/quorum-cve-triage)

---

## 🎨 Community Entry

### @manuJL — Quorum: Adversarial CVE Triage with Alpie-Core

Quorum uses Alpie-Core (via the 169Pi Playground API) as a high-reasoning backend for claim extraction and refereeing, while keeping tool-calling local when needed. It demonstrates how Alpie-Core can power serious, evidence-driven security workflows — not just chat.

*What it represents:* Using Alpie-Core’s reasoning strength inside an adversarial multi-agent system for real-world vulnerability triage.

**Contributed by [@manuJL](https://github.com/manuJL)**  
**Team:** Team Transformer

---

## 🔗 Links

- **Main Alpie-Core Repo:** [169Pi/Alpie-Core](https://github.com/169Pi/Alpie-Core)
- **Our Project:** [Quorum – CVE Triage](https://github.com/Team-transformer/quorum-cve-triage)
- **Website:** [169pi.ai](https://169pi.ai)
- **Hugging Face:** [169Pi on Hugging Face](https://huggingface.co/169Pi)

---

Built with respect for open reasoning models.  
— **Team Transformer**
