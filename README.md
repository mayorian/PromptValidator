# ⚡🦎 PROMPT VALIDATION TOOL 🦎🦎🦎🦎🦎🦎
### Measure your prompts before the model does.

![Prompt Validator Tool](https://raw.githubusercontent.com/mayorian/PromptValidator/refs/heads/main/imgs/prompt%20intro.png)
---

## 🧠 The Rocket Introduction!

**Prompt Validator** is a real-time, static syntax analysis engine for Large Language Model prompts.

It inspects your prompt *before* it reaches an LLM and evaluates:

- Instruction strength  
- Signal density  
- Ambiguity  
- Structural clarity  
- Token footprint  

All inside a live, zero-backend, browser-based interface.

No API calls.  
No model execution.  
No cost.

Just signal.

---

## 🔬 Core Philosophy

Most AI failures are not model failures.  
They are **prompt architecture failures**.

Weak verbs.  
Missing constraints.  
Conversational filler.  
Conflicting instructions.

Prompt Validator transforms prompt writing from trial-and-error into measurable engineering.

---

## 🛰️ Real-Time Signal Mapping

Every word you type is analyzed and categorized into impact layers:

| Impact Level      | Meaning |
|-------------------|----------|
| 🔴 HIGH_IMPACT    | Directive, constraint-defining, outcome-shaping language |
| 🟠 MEDIUM_IMPACT  | Contextual guidance and framing |
| 🔵 LOW_IMPACT     | Weak, ambiguous, or low-signal wording |

The system computes a dynamic **Clarity Score (0–100%)** based on:

- Weighted instruction density  
- Impact distribution  
- Prompt length normalization  
- Directive entropy  

You don’t just write prompts.  
You see their structural integrity.

---

## 📊 Built-In Analytics Engine

### Quantitative Metrics
- Characters
- Words
- Estimated tokens (GPT-compatible encoding)
- Impact counts per category

### Visual Intelligence
- Impact distribution chart  
- Clarity gauge  
- Length composition breakdown  

All updated in real time.

---

## 🛠️ Engine Architecture

-**Electron framework is v40.6.1**
- **Vanilla JavaScript**
- **CodeMirror 5** (live structured editor)
- **Chart.js 4** (data visualization layer)
- Optional GPT token encoder

Runs fully client-side.

No tracking.  
No storage.  
No external dependencies beyond CDN libraries.

---

## 🚀 Why This Matters

When building:

- System prompts  
- Agent frameworks  
- RAG pipelines  
- Structured output chains  
- Evaluation harnesses  
- Guardrail logic  

Prompt reliability becomes critical.

Prompt Validator gives you visibility into prompt strength **before deployment**.

It’s a linting layer for AI language.

---

## ⚙️ Getting Started

Welcome to the offline desktop version of **Prompt Validator**.

Follow these steps to launch the application:

- 🧩 Download `PromptValidator.zip` from the repository releases
- 📦 Unzip the archive to any folder on your computer
- 🖥️ The application is built with **Electron** — no web browser is required
- ▶️ After extracting, open **`Prompt Validator.exe`**

Once started:

- 🌐 The internal web interface will automatically load
- ✍️ You can immediately begin writing your prompt
- 📊 Real-time analysis and visual metrics will appear as you type

Additional behavior:

- 🔄 On **each launch**, the application downloads the latest **word databank**
- 🧠 This keeps impact detection and clarity scoring continuously up to date

You're now ready to engineer your prompts.


