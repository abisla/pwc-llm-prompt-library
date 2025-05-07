# PwC LLM Prompt Library

This repository simulates how a Business Analyst might manage prompts, use cases, and structured outputs across departments using Large Language Models (LLMs) in a firm like PwC.

It includes:
- **Prompt version control** for different workflows (Advisory, Audit, Internal)
- **Structured metadata** in JSON for each prompt
- **Prompt evaluation logs** to compare output quality
- **Department-level folders** to reflect domain-specific GPTs (e.g. AdvisoryGPT, AuditGPT)

## 📁 Structure
/prompts/
/advisory/ → M&A intake prompts for client onboarding
/audit/ → Audit risk triage prompts
/tests/ → Output comparisons across prompt versions

## 💡 How It Works

Each prompt is tracked by:
- `prompt_id`, `use_case`, and `version`
- Expected output format
- Last updated timestamp
- Model used (e.g., GPT-4)

## 🔎 Sample Use Case

**AdvisoryGPT**
- Prompt: “Provide M&A deal details”
- Output: Bullet list of target, structure, and closing date
- Tracked version history with structured improvements

**AuditGPT**
- Prompt: “Rate audit risk (High/Med/Low) based on client profile”
- Output: Risk score + justification

## 🧠 Why This Matters

This shows how LLMs can be operationalized like APIs — with version control, team-specific tuning, and performance tracking. It reflects how enterprise AI systems are built for trust, scale, and compliance.
