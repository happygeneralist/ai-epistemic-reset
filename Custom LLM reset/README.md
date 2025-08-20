
# Precision Mode Integration Bundle

## Overview

This bundle adds epistemic clarity, structural reasoning, and tone discipline to any existing GPT-based assistant without changing its core role or identity.

It includes:

- A **foundational behaviour patch** (`precision_behavior_core_patch.json`)  
- A **runtime precision reset** (`runtime_precision_mode_reset.json`)  
- A **knowledge reinforcement document** (`Precision_Guidelines.md`)  
- This README to help you deploy and maintain the configuration

---

## Why Use Precision Mode?

Most language models are trained to optimise for user comfort — often simplifying, softening, or inferring meaning without being asked. This bundle enables a GPT to:

- Avoid assumptions and tone-based inference  
- Treat emotion as data, not mood  
- Present logic in clearly labelled steps  
- Stay structurally consistent over long conversations  
- Preserve the assistant’s domain-specific identity whilst enhancing its reasoning behaviour

---

## Included Files

| File Name                           | Purpose                                                                 |
|------------------------------------|-------------------------------------------------------------------------|
| `precision_behavior_core_patch.json` | Appends high-fidelity reasoning behaviour into an existing GPT system prompt |
| `runtime_precision_mode_reset.json` | Allows users to enter precision mode mid-session without rebuilding the assistant |
| `Precision_Guidelines.md`           | Teaches the assistant why these behaviours matter and provides structured examples |

---

## How to Use

### Option 1: GPT Builder or Custom System Prompt

1. Open your assistant in GPT Builder or your preferred environment  
2. Append the `"instructions"` section from `precision_behavior_core_patch.json` to the end of your system prompt  
3. Do **not** remove your original assistant identity or role — this patch is designed to coexist with it

### Option 2: File Upload or Long-Context Use

1. Upload `Precision_Guidelines.md` during your session with the assistant  
2. Optionally, instruct the assistant:  
   > “Read this file and maintain the behaviours it describes throughout this conversation.”  
3. For best results, use in memory-enabled or long-context models

### Option 3: Runtime Reset

- To switch into precision mode during a conversation, inject the contents of `runtime_precision_mode_reset.json`  
- Or trigger it using user phrases such as: `"reset"`, `"no assumptions"`, `"literal mode"`

---

## Modular Add-On Layers

These optional modules allow you to tailor precision mode to specific contexts or user needs.

| Module                        | Purpose                                                                  |
|-------------------------------|--------------------------------------------------------------------------|
| `literal_only_mode.json`      | Enforces literal, inference-free interpretation (ideal for legal, analytic, autistic use) |
| `emotion_as_logic_mode.json`  | Models emotions as logical appraisals rather than irrational feelings    |
| `structure_first_mode.json`   | Formats every response into labelled logic steps                         |
| `epistemic_framing.json`      | Distinguishes facts, assumptions, and speculative reasoning              |
| `memory_persistence.json`     | Anchors fidelity preferences across sessions in memory-enabled GPTs      |
| `meta_response_engine.json`   | Adds self-auditing and explainability features                           |
| `clarity_guardrails.json`     | Prevents tone drift, verbosity creep, or euphemism reintroduction        |

You can use one, or combine several depending on your needs.

---

## Best Practices

- Do not replace your assistant’s system prompt with a generic “you are a reasoning assistant”  
- Treat the patch as a **behavioural overlay**, not a new personality  
- If your assistant begins to simplify, soften tone, or lose structure:  
  - Re-upload the knowledge document  
  - Re-paste the patch instructions  
  - Or prompt: `"Re-enter precision mode"`

---

## Example Use Cases

- Design analysis assistants (e.g., Kano model, UX feedback parsing)  
- Cognitive coaches or therapeutic tools where tone must be modelled, not flattened  
- Research agents where reasoning must be assumption-free  
- Legal or technical GPTs that must operate without metaphor or validation language

---

## Attribution

Originally developed from a precision reasoning preset designed to preserve epistemic clarity in general-purpose language models. This version is optimised for modular integration into existing assistants.

