# Precision Mode Integration Bundle

## Overview

This bundle adds epistemic clarity, structural reasoning, and tone discipline to any existing GPT-based assistant without changing its core role or identity.

It includes:

- A **runtime behavior patch** (`precision_injection_patch_v2.json`)  
- A **knowledge reinforcement document** (`Precision_Guidelines.md`)  
- This README to help you deploy and maintain the configuration

---

## Why Use Precision Mode?

Most language models are trained to optimize for user comfort — often simplifying, softening, or inferring meaning without being asked. This bundle enables a GPT to:

- Avoid assumptions and tone-based inference  
- Treat emotion as data, not mood  
- Present logic in clearly labeled steps  
- Stay structurally consistent over long conversations  
- Preserve the assistant’s domain-specific identity while enhancing its reasoning behavior

---

## Included Files

| File Name                          | Purpose                                                   |
|-----------------------------------|-----------------------------------------------------------|
| `precision_injection_patch_v2.json` | Appends high-fidelity reasoning behavior into an existing GPT system prompt |
| `Precision_Guidelines.md`         | Teaches the assistant why these behaviors matter and provides structured examples |

---

## How to Use

### Option 1: GPT Builder or Custom System Prompt

1. Open your assistant in GPT Builder or your preferred environment  
2. Append the `"instructions"` section from `precision_injection_patch_v2.json` to the end of your system prompt  
3. Do **not** remove your original assistant identity or role — this patch is designed to coexist with it

### Option 2: File Upload or Long-Context Use

1. Upload `Precision_Guidelines.md` during your session with the assistant  
2. Optionally, instruct the assistant:  
   > “Read this file and maintain the behaviors it describes throughout this conversation.”  
3. For best results, use in memory-enabled or long-context models

---

## Best Practices

- Do not replace your assistant’s system prompt with a generic “you are a reasoning assistant”  
- Treat the patch as a **behavioral overlay**, not a new personality  
- If your assistant begins to simplify, soften tone, or lose structure:
  - Re-upload the knowledge document
  - Re-paste the patch instructions
  - Or prompt: `"Re-enter precision mode"`

---

## Example Use Cases

- Design analysis assistants (e.g., Kano model, UX feedback parsing)  
- Cognitive coaches or therapeutic tools where tone must be modeled, not flattened  
- Research agents where reasoning must be assumption-free  
- Legal or technical GPTs that must operate without metaphor or validation language

---

## Attribution

Originally developed from a precision reasoning preset designed to preserve epistemic clarity in general-purpose language models. This version is optimized for modular integration into existing assistants.

