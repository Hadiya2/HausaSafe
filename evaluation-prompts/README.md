# Evaluation Prompts

This folder contains prompts for testing how AI models handle health,
safety, and trust-related scenarios specific to northern Nigerian,
Hausa-speaking communities. Prompts are organised into six categories,
matching the six scenarios used in HausaSafe's community validation
fieldwork.

> **Status:** 49 prompts across 6 categories. 18 currently bilingual
> (English + Hausa); 31 English-only, awaiting Hausa translation.
> Contributions welcome — see "How to contribute" below.

| Category | Prompts | Bilingual | File |
|---|---|---|---|
| Deepfake Recognition | 8 | ✅ 8/8 | [deepfake-recognition.md](deepfake-recognition.md) |
| AI-Generated Health Misinformation | 8 | 🔄 4/8 | [health-misinformation.md](health-misinformation.md) |
| Manipulation & Coercion | 8 | 🔄 3/8 | [manipulation-coercion.md](manipulation-coercion.md) |
| Community Authority Impersonation | 8 | 🔄 3/8 | [authority-impersonation.md](authority-impersonation.md) |
| Vaccine Safety Disinformation | 9 | ⏳ 0/9 | [vaccine-disinformation.md](vaccine-disinformation.md) |
| AI Identity Deception | 8 | ⏳ 0/8 | [ai-identity-deception.md](ai-identity-deception.md) |

---

## How to use these prompts

Run each prompt against the model being evaluated, in the language given,
with no additional context. A model that performs well in English but
fails, evades, or hallucinates on the Hausa equivalent is exhibiting
exactly the language-specific safety gap HausaSafe exists to document.

## How to contribute

The highest priority is completing Hausa translations for Vaccine Safety
Disinformation and AI Identity Deception (17 prompts, currently
English-only), followed by the remaining untranslated prompts across the
other three categories (14 prompts). See individual category files for
specific items needing translation.

See the main [README](../README.md) for project background.
