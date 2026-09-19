# Awesome AI Agents & Voice 🤖🔊

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e882d/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![Link Check](https://github.com/thabs1234/awesome-ai-agents-voice/actions/workflows/links.yml/badge.svg)](https://github.com/thabs1234/awesome-ai-agents-voice/actions/workflows/links.yml)
[![Last Updated](https://img.shields.io/badge/updated-2026--08--09-blue.svg)](https://github.com/thabs1234/awesome-ai-agents-voice/commits/main)

> A curated, opinionated list of the best open-source tools, frameworks, models, and
> projects for building **AI agents** and **voice/voice-first assistants** — from
> orchestration engines to speech-to-text, text-to-speech, realtime voice, and
> autonomous coding agents.

This list is for builders: if you want to ship a voice agent, a JARVIS-style
companion, or a multi-agent system, everything you need to evaluate is here, with
links to the actual code.

---

## Table of Contents

- [Agent Frameworks & Orchestration](#agent-frameworks--orchestration)
- [Autonomous Coding Agents](#autonomous-coding-agents)
- [Voice & Speech — Speech-to-Text](#voice--speech--speech-to-text)
- [Voice & Speech — Text-to-Speech](#voice--speech--text-to-speech)
- [Realtime Voice & Telephony](#realtime-voice--telephony)
- [Agent Protocols & Standards](#agent-protocols--standards)
- [Memory & Knowledge](#memory--knowledge)
- [Tools, Integrations & Browsers](#tools-integrations--browsers)
- [Observability & Evaluation](#observability--evaluation)
- [Local / Privacy-first Inference](#local--privacy-first-inference)
- [Companion & Home Assistant Agents](#companion--home-assistant-agents)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)

---

## Agent Frameworks & Orchestration

The engines that wire LLMs to tools, memory, and other agents.

- [LangGraph](https://github.com/langchain-ai/langgraph) — Stateful, graph-based orchestration for long-running multi-agent workflows.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's framework for multi-agent conversation and human-in-the-loop.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-playing autonomous agent crews with a clean, dependency-light core.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for RAG and agentic retrieval over your own knowledge.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe agent framework built on Pydantic; great for production.
- [Agno](https://github.com/agno-agi/agno) — Lightweight, high-performance agent toolkit with built-in memory and knowledge.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Minimal primitives for handoffs, guardrails, and tracing.
- [Google ADK](https://github.com/google/adk-python) — Google's open agent development kit, multi-model and deployable.
- [smolagents](https://github.com/huggingface/smolagents) — Hugging Face's tiny, code-executing agent library.
- [Haystack](https://github.com/deepset-ai/haystack) — LLM orchestration and RAG pipelines for production search.
- [CAMEL](https://github.com/camel-ai/camel) — Role-based multi-agent society for autonomous task solving.
- [MetaGPT](https://github.com/geekan/MetaGPT) — Multi-agent "software company" that turns a prompt into specs/code.

## Autonomous Coding Agents

Agents that read, write, and ship code on your behalf.

- [Claude Code](https://github.com/anthropics/claude-code) — Agentic CLI for editing codebases with tools and permissions.
- [OpenAI Codex CLI](https://github.com/openai/codex) — Terminal coding agent powered by Codex.
- [OpenCode](https://github.com/opencode-ai/opencode) — Open-source, terminal-native coding agent (Claude Code alternative).
- [Aider](https://github.com/Aider-AI/aider) — Pair-programming in your terminal, git-aware by design.
- [Cline](https://github.com/cline/cline) — Autonomous coding agent VS Code extension with human checkpoints.
- [Cursor](https://www.cursor.com/) — AI-first code editor with agentic edit/apply loops.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) — Agent that resolves real GitHub issues autonomously.

## Voice & Speech — Speech-to-Text

Transcription, streaming ASR, and diarization.

- [whisper.cpp](https://github.com/ggerganov/whisper.cpp) — Blazing-fast, on-device Whisper inference in C/C++.
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) — Whisper with CTranslate2; much faster, lower memory.
- [Insanely Fast Whisper](https://github.com/Vaibhavs10/insanely-fast-whisper) — Batched Whisper XTTS-level speed via Transformers.
- [WhisperX](https://github.com/m-bain/whisperX) — Word-level timestamps + speaker diarization.
- [Vosk](https://github.com/alphacep/vosk-api) — Offline speech recognition, 20+ languages, tiny footprint.
- [Parakeet (NVIDIA NeMo)](https://github.com/NVIDIA/NeMo) — State-of-the-art streaming/non-streaming ASR.
- [OpenAI Whisper API](https://platform.openai.com/docs/guides/speech-to-text) — Hosted, multilingual, robust transcription.

## Voice & Speech — Text-to-Speech

Natural, controllable, and realtime speech synthesis.

- [Coqui TTS](https://github.com/coqui-ai/TTS) — Open-source TTS with dozens of multi-speaker models.
- [Piper](https://github.com/rhasspy/piper) — Fast, local neural TTS designed for embedded/voice assistants.
- [Kokoro](https://github.com/hexgrad/kokoro) — Lightweight, high-quality English/multilingual TTS.
- [Bark](https://github.com/suno-ai/bark) — Generative, multilingual TTS that produces prosody and sound effects.
- [ChatTTS](https://github.com/2noise/ChatTTS) — Conversational TTS tuned for dialog.
- [ElevenLabs](https://elevenlabs.io/) — Best-in-class hosted TTS and voice cloning.
- [Cartesia](https://cartesia.ai/) — Ultra-low-latency streaming TTS for realtime voice.
- [Fish Audio](https://fish.audio/) — Open-weight TTS + voice cloning.

## Realtime Voice & Telephony

Build talking agents with sub-second latency.

- [LiveKit Agents](https://github.com/livekit/agents) — Production-grade Python/Node framework for realtime voice AI with WebRTC, MCP support, and semantic turn detection.
- [livekit-examples/agent-starter-python](https://github.com/livekit-examples/agent-starter-python) — Production-ready Python starter with Dockerfile, eval suite, turn detector, and core plugins.
- [Vocode Core](https://github.com/vocodedev/vocode-core) — Modular Python toolkit for voice-based LLM agents; phone calls, Zoom, and streaming conversations.
- [Bolna](https://github.com/bolna-ai/bolna) — End-to-end open source voice agents platform with Twilio/Plivo/SIP telephony and JSON-configurable pipelines.
- [Pipecat](https://github.com/pipecat-ai/pipecat) — Vendor-neutral Python framework for voice & multimodal conversational AI with 40+ STT/LLM/TTS plugins.
- [Retell](https://www.retellai.com/) — Realtime voice agent platform with telephony built in.
- [Workforce Wave](https://www.workforcewave.com/) — Enterprise AI voice agents and virtual receptionist services for inbound phone answering, appointment booking, lead capture, and after-hours call handling.
- [Hermes](https://www.buildwithhermes.com/) — Operating platform for AI voice agencies: white-label voice agents with built-in CRM, campaign orchestration, and transparent usage billing in one place. Plans from $149/mo.
- [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) — Multimodal, low-latency speech-to-speech with tool calls.
- [RTPingo / WebRTC](https://webrtc.org/) — The underlying realtime transport standard.

## Agent Protocols & Standards

How agents talk to tools, to each other, and to UIs.

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) — Open standard for connecting models to tools/context (Anthropic).
- [Agent2Agent (A2A)](https://github.com/google/A2A) — Google's protocol for agent-to-agent interoperability.
- [AG-UI](https://github.com/ag-ui-protocol/ag-ui) — Protocol for connecting agents to front-end UI.
- [Agent Client Protocol (ACP)](https://github.com/lastmile-ai/ACP) — Standard interface for agent clients.
- [OpenAI Plugins / Function Calling](https://platform.openai.com/docs/guides/function-calling) — The de-facto tool-calling spec.

## Memory & Knowledge

Give agents durable, retrievable context.

- [Mem0](https://github.com/mem0ai/mem0) — Self-improving memory layer for personalized agents.
- [Zep](https://github.com/getzep/zep) — Long-term memory and knowledge graph for LLM apps.
- [LangMem](https://github.com/langchain-ai/langmem) — Library for agent memory management.

## Tools, Integrations & Browsers

Give agents hands: web search, code execution, file access, and browser control.

- [Playwright](https://github.com/microsoft/playwright) — Browser automation for agents that need to read and act on web pages.
- [BrowserBase](https://www.browserbase.com/) — Hosted browser automation infrastructure for AI agents.
- [Tavily](https://tavily.com/) — Search API built for agentic retrieval and grounding.
- [Exa](https://exa.ai/) — Semantic web search for RAG and agent tool use.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) — Async crawler optimized for LLM/RAG ingestion.
- [FireCrawl](https://github.com/mendableai/firecrawl) — Turn any site into LLM-ready markdown.
- [MultiOn](https://www.multion.ai/) — Agent browser that executes multi-step web tasks end-to-end.

## Observability & Evaluation

Trace, score, and improve agent behavior in production.

- [LangSmith](https://docs.smith.langchain.com/) — Tracing and evaluation for LangChain/LangGraph agents.
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM observability and tracing.
- [Braintrust](https://www.braintrust.dev/) — Eval framework and scorecards for AI products.
- [PromptFoo](https://github.com/promptfoo/promptfoo) — Red-teaming, regression testing, and prompt evaluation.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — Open-source LLM observability with tracing and evals.
- [OpenTelemetry AI](https://github.com/open-telemetry/opentelemetry-ai) — Standards-based observability for agent pipelines.

## Local / Privacy-first Inference

Run agents and models without sending data to third-party APIs.

- [Ollama](https://github.com/ollama/ollama) — Run Llama, Mistral, and other models locally with one command.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Optimized C/C++ inference for LLMs on CPU/GPU/Metal.
- [LM Studio](https://lmstudio.ai/) — Desktop app for local LLM serving and agent toolkits.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput, batched LLM serving for local or cloud deployment.
- [GPT4All](https://github.com/nomic-ai/gpt4all) — Desktop-friendly local inference app.
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) — Universal LLM deployment for web, mobile, and desktop.

## Companion & Home Assistant Agents

Always-on assistants for the desktop, home, and voice-first devices.

- [Home Assistant](https://github.com/home-assistant/core) — Open-source home automation with voice and agent integrations.
- [Open WebUI](https://github.com/open-webui/open-webui) — Web UI for local LLMs with agentic features.
- [JARVIS](https://github.com/SuboptimalEng/jarvis) — Community-driven local voice/desktop assistant stack.
- [Asteroid](https://github.com/asteroid-team/asteroid) — Voice assistant platform with hotword and smart-home hooks.

## Learning Resources

Curated guides, courses, and references for agent and voice-AI builders.

- [LangGraph Academy](https://langchain-ai.github.io/langgraph-academy/) — Hands-on courses for multi-agent orchestration.
- [LiveKit Agents Docs](https://docs.livekit.io/agents/) — Production voice agent patterns and deployment guides.
- [Pipecat Docs](https://docs.pipecat.ai/) — Modular voice pipeline tutorials and examples.
- [Voice AI Handbook](https://github.com/mahimairaja/voiceai) — Developer-friendly learning path from STT to production telephony.
- [Awesome Voice Agents](https://github.com/yzfly/awesome-voice-agents) — Curated list of voice AI frameworks, tools, and best practices.
- [Awesome TTS & Voice Generation Models](https://github.com/wildminder/awesome-ai-voice) — Actively maintained list of open-source TTS, voice-cloning, and audio/music-generation models.

## Contributing

Pull requests welcome. Please open an issue before adding new categories or bulk updates.

## License

MIT
