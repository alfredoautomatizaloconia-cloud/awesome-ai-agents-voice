# Awesome AI Agents & Voice 🤖🔊

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e882d/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![Link Check](https://github.com/thabs1234/awesome-ai-agents-voice/actions/workflows/links.yml/badge.svg)](https://github.com/thabs1234/awesome-ai-agents-voice/actions/workflows/links.yml)
[![Last Updated](https://img.shields.io/badge/updated-2026--08--08-blue.svg)](https://github.com/thabs1234/awesome-ai-agents-voice/commits/main)

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

- [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) — Multimodal, low-latency speech-to-speech with tool calls.
- [LiveKit](https://github.com/livekit/livekit) — Open-source WebRTC stack for realtime voice/video agents.
- [Vapi](https://vapi.ai/) — Voice API for building phone-call and web voice agents fast.
- [Pipecat](https://github.com/pipecat-ai/pipecat) — Framework for voice & multimodal conversational AI pipelines.
- [Retell](https://www.retellai.com/) — Realtime voice agent platform with telephony built in.
- [RTPingo / WebRTC](https://webrtc.org/) — The underlying realtime transport standard.

## Agent Protocols & Standards

How agents talk to tools, to each other, and to UIs.

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) — Open standard for connecting models to tools/context (Anthropic).
- [Agent2Agent (A2A)](https://github.com/google/A2A) — Google's protocol for agent-to-agent interoperability.
- [AG-UI](https://github.com/ag-ui-protocol/ag-ui) — Protocol for connecting agents to front-end UI.
- [Agent Client Protocol (ACP)](https://github.com/lastmile-ai/ACP) — Standard interface for agent clients.
- [OpenAI Plugins / Function Calling](https://platform.openai.com/docs/guides/function-calling) — The de-facto tool-calling spec.

## Memory & Knowledge

Give agents durable,检索able context.

- [Mem0](https://github.com/mem0ai/mem0) — Self-improving memory layer for personalized agents.
- [Zep](https://github.com/getzep/zep) — Long-term memory and knowledge graph for LLM apps.
- [LangMem](https://github.com/langchain-ai/langmem) — Library for agent memory management.
- [Letta (formerly MemGPT)](https://github.com/letta-ai/letta) — Agents with OS-style memory and state.

## Tools, Integrations & Browsers

- [Browser-use](https://github.com/browser-use/browser-use) — Enable LLMs to control a web browser.
- [Composio](https://github.com/ComposioHQ/composio) — 250+ tool integrations for AI agents.
- [Agent Reach](https://github.com/agent-reach/agent-reach) — Local gateway that lets agents/devices reach the internet safely.
- [LangChain Tools](https://python.langchain.com/docs/integrations/tools/) — Vast catalog of prebuilt agent tools.
- [Toolhouse](https://toolhouse.ai/) — Managed tool library for any model.

## Observability & Evaluation

Ship agents you can actually debug.

- [LangSmith](https://github.com/langchain-ai/langsmith-sdk) — Tracing, eval, and monitoring for LLM apps.
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM engineering platform (traces, evals, prompt mgmt).
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — Open-source LLM observability and evals.
- [Braintrust](https://github.com/braintrustdata/braintrust-sdk) — Eval-driven development for AI.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) — OpenTelemetry instrumentation for LLM apps.

## Local / Privacy-first Inference

Run models on your own hardware.

- [Ollama](https://github.com/ollama/ollama) — Run LLMs locally with one command.
- [LM Studio](https://lmstudio.ai/) — Desktop app for local model management and serving.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Inference engine powering most local tooling.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput serving for open models.
- [LocalAI](https://github.com/mudler/LocalAI) — OpenAI-compatible drop-in for local inference.

## Companion & Home Assistant Agents

JARVIS-style and voice-first personal assistants.

- [Mark-L (JARVIS)](https://github.com/FatihMakes/Mark-L) — Local, extensible voice assistant with wake-word + skills.
- [Home Assistant](https://github.com/home-assistant/core) — Open-source home automation with rich voice pipelines.
- [OpenVoiceOS](https://github.com/OpenVoiceOS/ovos) — Voice-first, privacy-respecting assistant framework.
- [Leon](https://github.com/leon-ai/leon) — Open-source personal assistant running on your own server.
- [Jarvis (nextcode)](https://github.com/nextcode50/Jarvis) — Lightweight local voice assistant.

## Learning Resources

- [Build Your Own X](https://github.com/codecrafters-io/build-your-own-x) — Recreate tech from scratch, including LLM/agent pieces.
- [Anthropic — Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — The canonical agent-design essay.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Recipes for agents, RAG, and function calling.
- [LLM Agents Course (Hugging Face)](https://github.com/huggingface/agents-course) — Free, hands-on agent curriculum.
- [Model Context Protocol Docs](https://modelcontextprotocol.io/) — Everything MCP, with SDK examples.

---

## Contributing

Additions, fixes, and new categories are welcome! Please read
[CONTRIBUTING.md](CONTRIBUTING.md) first — keep entries alphabetical, include a
one-line description, and run the link checker before opening a PR.

## License

[CC0 1.0 Universal](LICENSE) — public domain. Do whatever you want with it.
