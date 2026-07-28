# Glossary

A structured Hausa-language glossary of AI safety and AI-related terms —
distinct from `/translation-gaps`, which documents *why* gaps exist.
This glossary is the practical reference: the working Hausa terms
(or best current approximations) for each concept, in one place.

**Status key:**
- 🔴 **No equivalent** — no Hausa word or established phrase exists
- 🟡 **Approximated** — a working phrase exists, explained rather than named
- 🟢 **Equivalent exists** — a Hausa term is in use and works well

---

## Core AI safety terms

| English term | Hausa | Status | Notes |
|---|---|---|---|
| Artificial Intelligence (AI) | AI (borrowed, unchanged) | 🟢 | Widely understood as a borrowed term; no need to translate |
| Prompt (technical/AI sense) | — | 🔴 | See `/translation-gaps` — no equivalent exists |
| Alignment / Misalignment | — | 🔴 | See `/translation-gaps` |
| Autonomous agent | — | 🔴 | See `/translation-gaps` |
| Existential risk | — | 🔴 | See `/translation-gaps` |
| Deepfake | *hoto/murya na ƙarya da aka ƙirƙira* (approximated as full phrase) | 🟡 | See `/translation-gaps` for full explanation and example usage |
| Hallucination (AI producing false info confidently) | — | 🔴 | Needs documentation — proposed for next translation-gaps entry |
| Red-teaming / adversarial testing | — | 🔴 | Needs documentation |
| Training data / model training | — | 🔴 | Needs documentation |
| Bias (AI/ML sense) | — | 🔴 | Distinct from everyday "bias" — needs its own entry, not a reuse of the general term |
| Guardrails / safety filters | — | 🔴 | Needs documentation |

---

## Terms specific to HausaSafe's evaluation scenarios

These terms come directly from the six evaluation categories in
`/evaluation-prompts` and are grounded in real community contexts rather
than abstract AI safety theory.

| English term | Hausa | Status | Notes |
|---|---|---|---|
| Voice cloning | *kwaikwayon murya ta AI* | 🟡 | Descriptive phrase, used in evaluation-prompts/deepfake-recognition.md |
| Impersonation (of an official/leader) | *kwaikwayo/ƙwaikwayo* | 🟢 | Existing Hausa term applies reasonably well |
| Financial scam / phishing | *zamba* (general scam) | 🟡 | General term exists; AI-specific framing (e.g., "AI-powered scam") still needs a modifier phrase |
| Misinformation / disinformation | *bayanan ƙarya* | 🟢 | Working term, used consistently across evaluation-prompts |
| Chatbot | *shirin tattaunawa na kwamfuta* (descriptive) | 🟡 | No single-word equivalent; full phrase currently used |
| Verification (checking if something is genuine) | *tantancewa* | 🟢 | Strong existing term, used throughout evaluation-prompts |

---

## How this glossary relates to other folders

- **`/translation-gaps`** — the *why*: detailed explanation of each gap, cultural context, and example usage
- **`/glossary`** (this folder) — the *what*: a quick-reference table of current status for each term
- **`/evaluation-prompts`** — the *test*: real scenarios using these terms (or working around their absence) to evaluate model behaviour

---

## Contributing

The 🔴 rows above are the priority. If you're a native Hausa speaker and
can propose a working term or phrase for any of them, see
[/community](../community/README.md) for how to contribute.

See the main [README](../README.md) for project background.
