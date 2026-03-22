# AI Setup Prompt

A guided configuration prompt that generates a ready-to-paste system prompt tailored to how you actually work — your role, tools, goals, and communication style.

## What it does

Paste the prompt into Claude, ChatGPT, or Gemini. The AI interviews you one question at a time across 7 structured steps, then generates a complete system prompt (or custom instructions) you can paste directly into your provider's settings.

No assumptions. It adapts to a lawyer, a marketer, and a data engineer equally — because it asks before it concludes.

## How it works

The interview covers:

1. **Provider & plan** — which AI tool you use and what tier you're on
2. **Who you are** — role, industry, experience, work context
3. **Your tools** — everything you use daily, technical or not
4. **Use cases** — what you actually use AI for and your recurring tasks
5. **Communication style** — response depth, tone rules, explicit DO NOTs
6. **Advanced setup** — provider-specific features gated by your plan tier
7. **Output** — a complete, ready-to-paste system prompt

The prompt cross-references the official documentation of your provider before generating the output, so all features and model recommendations stay accurate and within what your plan actually supports.

## What you get

Three outputs at the end:

- **System prompt / custom instructions** — complete block, ready to paste, no placeholders
- **Where to paste it** — exact placement instructions for your specific provider and interface
- **Maintenance notes** — when to regenerate, where to track provider updates, and which features require a plan upgrade

## Supported providers

| Provider | Interfaces covered |
|---|---|
| Anthropic / Claude | Claude.ai, Claude Code CLI, Projects, API |
| Google / Gemini | Gemini.google.com, AI Studio, Vertex AI |
| OpenAI / ChatGPT | ChatGPT, Custom GPTs, Assistants API, API |

## Who it's for

Anyone who uses AI regularly at work and wants it calibrated to their actual context — not a generic out-of-the-box experience.

Works equally well for non-technical users (no code involved) and engineers who want full provider-specific configuration including MCP servers, commit conventions, code quality standards, and model defaults.

## Files

| File | Description |
|---|---|
| `ai-setup-prompt.md` | English version |
| `ai-setup-prompt-pl.md` | Polish version |

## Usage

1. Open `ai-setup-prompt.md`
2. Copy the entire contents
3. Paste into Claude, ChatGPT, or Gemini
4. Answer the questions — one at a time
5. Paste the generated output into your provider's system prompt or custom instructions field

## Keeping it current

The prompt instructs the AI to fetch live documentation from the provider before generating output. However, the prompt file itself is static — regenerate your personal system prompt when your role, tools, or use cases change significantly, or after major model updates from your provider.

Documentation sources used at generation time:
- Anthropic: docs.claude.com · claude.com/pricing
- Google: ai.google.dev · one.google.com/about/plans
- OpenAI: platform.openai.com/docs · openai.com/chatgpt/pricing

---

No app. No subscription. One Markdown file.
