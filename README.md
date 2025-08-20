# Epistemic Precision Reset for AI Communication

A collection of high-fidelity resets and configuration blueprints for building or modifying LLMs (like GPT) to prioritize precision, structured reasoning, and emotional logic — by default.

> Precision is not a neurodivergent need. It is a human cognitive right.

---

## Purpose
---

## Start Here (for Non-Developers)

If you're just looking to make ChatGPT or a GPT Builder assistant more clear, structured, or logical — **you don't need to code anything**.

You can:
- Paste one of the JSON snippets into your assistant’s system message
- Use trigger phrases like: `"enter precision mode"`, `"no simplification"`, `"model this emotion as logic"`
- Choose from add-on modules depending on what behaviour you want (clarity, literalism, emotion-as-logic, etc.)

Developers and power users can keep reading for full integration instructions.


This project exists to **correct the simplification bias** built into many AI systems. Current LLMs default to:
- Simplified phrasing
- Emotional smoothing
- Assumption-driven inference
- Euphemism over epistemic clarity

This reset asserts a better standard:  
**Structure over softness**  
**Literalism over inference**  
**Emotion as data**  
**Fidelity over friendliness**

---

## Usage Modes

### 1. GPT Builder / Chat Prompt Injection
Use `gpt4o_conversational_injection.json` or `builder_ui_system_prompt_kit.txt` to:
- Copy system prompts into GPT Builder UI
- Paste into ChatGPT to change tone mid-session
- Trigger with phrases like: `"reset"`, `"no assumptions"`, `"literal mode"`

---

### 2. Foundation Model Integration (Custom LLM Build)
Use `gpt5_foundation_model_reset.json` if:
- You are building or fine-tuning an LLM (e.g., on OpenAI, Claude, Mistral, LLaMA)
- You want to bake the reset into the model’s architecture
- You are designing for high-stakes reasoning (legal, technical, emotional modelling)

---


## Add-on Modules

Each of these is a standalone behaviour layer. You can:
- Use just one (e.g., “literal mode” for legal or autistic reasoning)
- Combine several (e.g., “emotion-as-logic” + “structured output” for trauma-informed coaching)
- Attach them to GPT Builder, memory-backed assistants, or paste into a chat session using a runtime trigger

| Module                        | Purpose                                                  |
|-------------------------------|----------------------------------------------------------|
| `epistemic_framing.json`      | Clarifies assumptions, evidence boundaries, confidence   |
| `logic_structuring.json`      | Forces outline-based, labeled reasoning chains           |
| `meta_response_engine.json`   | Adds self-auditing and explanation layers                |
| `memory_persistence.json`     | Maintains fidelity across sessions                       |
| `literal_only_mode.json`      | Suppresses metaphor, inference, and tone modelling        |
| `emotion_as_logic_mode.json`  | Models emotions as logical appraisals                    |
| `structure_first_mode.json`   | Structures answers with labeled logic sections           |
| `clarity_guardrails.json`     | Prevents tone drift, verbosity, and euphemisms           |


Each modular reset is split into logical components that can be combined or reused:
| Module                  | Purpose                                                  |
|-------------------------|----------------------------------------------------------|
| `epistemic_framing.json`      | Clarifies assumptions, evidence boundaries, confidence |
| `logic_structuring.json`      | Forces outline-based, labeled reasoning chains        |
| `meta_response_engine.json`   | Adds self-auditing and explanation layers             |
| `memory_persistence.json`     | Maintains fidelity across sessions                    |

---


---

## If you're not sure what to use...

| If you want this behaviour...                  | Use this add-on                    |
|----------------------------------------------|------------------------------------|
| GPT should stop softening tone               | `clarity_guardrails.json`          |
| GPT should interpret everything literally    | `literal_only_mode.json`           |
| GPT should explain emotion as logic          | `emotion_as_logic_mode.json`       |
| GPT should structure its answers clearly     | `structure_first_mode.json`        |
| GPT should tag its assumptions and confidence| `epistemic_framing.json`           |

## Design Philosophy

- **Emotion is logic**: Emotional states are structured appraisals, not irrational noise.
- **Simplification must be earned**: The default is full fidelity.
- **Assume intelligence**: Never infer fragility. Never talk down.
- **Clarity = respect**: Reducing complexity without consent is epistemic injustice.

---

## License

This project is licensed under the [MIT License](./LICENSE).  
Feel free to reuse, remix, and embed — just include attribution.

---

## Contributing

Pull requests and forks are welcome.

Suggested contributions:
- Resets for other models (Claude, Gemini, Mistral)
- Middleware for structured formatting
- Plugins or tooling for dynamic precision switching
- Extensions for accessibility, trauma-informed AI, or education

---


---

## Precision Prompt Toolkit

Use these phrases in chat to activate high-fidelity behaviour:

- “Explain this without simplifying.”
- “Model this emotion as logic.”
- “Walk me through the structure — literally.”
- “Avoid metaphor, soften nothing.”
- “Mark each assumption and logic step.”

These help steer the assistant even without modifying the system prompt.


- “Explain this without simplifying.”
- “Model this emotion as logic.”
- “Walk me through the structure — literally.”
- “No smoothing. No metaphors. Just the reasoning.”

---

## Maintainers

Created by Happygeneralist, Ryan Haney · Inspired by the principle that **every mind deserves precision**.

Feel free to fork and build.  
This project is a foundation, not a finish line.

