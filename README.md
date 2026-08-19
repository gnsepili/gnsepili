<div align="center">
  <h1>Ganesh Epili</h1>
  <p><strong>AI Engineer building agentic and multimodal systems.</strong></p>
  <p>LLM agents · context engineering · multimodal video · applied machine learning</p>
  <p>
    <a href="https://gnsh.dev">Portfolio</a> ·
    <a href="https://www.linkedin.com/in/gnsepili/">LinkedIn</a>
  </p>
</div>

## What I do

I'm an AI Engineer at Fynd, working across machine learning, generative AI, applied research, and product engineering.

I currently own the architecture and end-to-end development of an internal agentic video-production platform. It turns prompts, reference assets, and product URLs into production-ready videos through planning, asset generation, browser interaction, multimodal generation, post-production, and multi-clip assembly.

The interesting part is not a single model call. It is the system around it: explicit state, tool use, context management, evaluation, failure recovery, and human review.

## System shape

<pre>
user intent + reference assets
              ↓
    analysis & production plan
              ↓
storyboard + assets + browser actions
              ↓
      multimodal generation
              ↓
quality checks + post-production + assembly
              ↓
        production-ready video
</pre>

## Current focus

- **Agentic AI** — LLM agents, tool calling, context engineering, MCP, and workflow reliability
- **Multimodal AI** — coordinating language, image, video, and audio systems
- **Applied ML research** — NLP, LLM fine-tuning, efficient smaller models, evaluation, and error analysis
- **Production AI** — Python, PyTorch, FastAPI, TypeScript, browser automation, and model integrations

## Selected work

| Project | What it demonstrates |
| --- | --- |
| [video-agent](https://github.com/gnsepili/video-agent) | End-to-end product-image-to-marketing-video system with planning, parallel generation, automated QA, music, and final assembly |
| [ai-video-edit](https://github.com/gnsepili/ai-video-edit) | Autonomous AI-assisted video-editing workflow |
| [DB-Agent](https://github.com/gnsepili/DB-Agent) | Natural-language database interaction with generated queries, visualizations, and reusable presets |
| [gnsh.dev](https://github.com/gnsepili/gnsh.dev) | Portfolio and technical-writing platform |

## Writing & research

I publish visual explanations of machine-learning systems, including **Transformers From Scratch**—a six-part series spanning attention and Q/K/V through modern architectures, training, alignment, and inference.

My earlier research covered domain-specific LLM fine-tuning, efficient smaller-model performance, multilingual voice assistants, and NLP evaluation.

Explore my writing at [gnsh.dev](https://gnsh.dev).

## Working principles

- Build the orchestration around the model, not just the prompt.
- Prefer observable workflows and measurable evaluation.
- Stay model-agnostic where it improves reliability and iteration speed.
- Turn promising prototypes into complete, user-facing systems.
