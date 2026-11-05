# Hi, I'm Kishore

## About me

I study when AI systems should trust themselves, and when we should trust them. Most of my work comes back to one question: does a model's confidence actually match how often it's right? That question started in calibration research, followed me into clinical AI, and is now the core of the company I'm building.

I'm aiming at the overlap of AI reliability, neuroscience, and medicine. I'm based in the Atlanta area.

## Research

**Probabilistic Chain-of-Thought: Sequential Bayesian Inference over Latent Reasoning Correctness**  
Accepted at four ICML 2026 workshops (AI4Math, SPIGM, CTB, EIML). We treat each reasoning step as evidence about whether the final answer is correct and update a belief as the chain unfolds. On MATH and GSM8K it cut Expected Calibration Error by 74% and raised accuracy by 14.7 points.

**Calibration Collapse in Multi-Turn Diagnostic Dialogue with Large Language Models**  
Accepted at the NeurIPS 2026 GenAI4Health workshop and IEEE ICHI. Stanford-mentored. Single-turn benchmarks say little about how a model behaves across a whole patient conversation, so we tracked how confidence drifts away from accuracy as a diagnostic dialogue goes on, comparing reasoning and non-reasoning backbones.

**In progress**
- Sycophantic uncertainty: how social pressure in a prompt erodes a language model's confidence calibration.
- [SteadyHand](https://github.com/kishoren18-hue/steadyhand): confidence cutoffs for muscle-controlled prosthetic hands that hold a target misfire rate for every user, even after the armband shifts. Built on LibEMG, working toward live control.
- A neuroscience literature review on why traumatic memories generalize so broadly and resist extinction therapy.

## What I'm building

**[Aptivae](https://aptivae.io)** (co-founder & CEO)  
The proof layer hiring has never had. Résumés claim skills; we want candidates to show them, with AI-led assessment and expert human graders behind every result.

**Second Thought Initiative**  
A student-led AI literacy initiative. We make classroom kits that teach students to question AI answers instead of copying them, and I'm building a companion web app that flags how much you should trust a chatbot's response.

## Projects

**Measuring whether confidence is honest**

| Repo | What it does |
|---|---|
| [calibrate-me](https://github.com/kishoren18-hue/calibrate-me) | A game that measures whether *your* confidence is honest, with class dashboards and a head-to-head against AI models |
| [metad-llm](https://github.com/kishoren18-hue/metad-llm) | Meta-d′ and M-ratio from cognitive neuroscience, applied to language model confidence |
| [metacognition-gap](https://github.com/kishoren18-hue/metacognition-gap) | Scores models and humans with identical code to ask whether LLMs know what they know as well as people do |
| [calibkit](https://github.com/kishoren18-hue/calibkit) | Calibration metrics (ECE, Brier and more) with bootstrap confidence intervals |
| [calibration-ci](https://github.com/kishoren18-hue/calibration-ci) | Unit tests for model confidence: fails the build when a change makes a model overconfident, even if accuracy stays flat |
| [flipcheck](https://github.com/kishoren18-hue/flipcheck) | Asks the same question ten ways and counts how often the answer changes |

**AI that's safe to act on**

| Repo | What it does |
|---|---|
| [note-drift](https://github.com/kishoren18-hue/note-drift) | Flags facts that get dropped, changed or invented when a clinical note is summarized, ranked by patient risk |
| [medsched](https://github.com/kishoren18-hue/medsched) | Turns pharmacy labels into a large-print medicine schedule and refuses to guess when a label is unclear |
| [steadyhand](https://github.com/kishoren18-hue/steadyhand) | Prosthetic hand confidence cutoffs with misfire-rate guarantees ([live demo](https://kishoren18-hue.github.io/steadyhand/)) |
| [agentguard](https://github.com/kishoren18-hue/agentguard) | Tests whether AI shopping agents make safe payment decisions, checked against the ledger instead of the agent's own story |

calibrate-me, flipcheck, and note-drift are being turned into live web apps (Supabase + Claude).

## Stack

Python · NumPy · TypeScript · Next.js · Supabase · Claude / OpenAI / OpenRouter APIs

## Get in touch

[LinkedIn](https://www.linkedin.com/in/knuthalapati) · kishorenuthalapat@gmail.com

Always happy to talk about calibration, clinical AI, or early-stage startups.
