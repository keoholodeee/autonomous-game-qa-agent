# Autonomous Game QA Agent (AGQA) 🚀

## Overview
AGQA is a multi-agent system designed to automate complex game testing scenarios. It moves beyond simple "record-and-play" automation by using LLMs to understand game logic.

## Key Features
- **State-Aware Testing:** Understands game states using Gemini 1.5 Pro Vision.
- **Self-Healing Scripts:** Automatically repairs broken test paths using Claude 3.5 Sonnet.
- **Root Cause Analysis:** DeepSeek-V3 powered reasoning to explain why a test failed.

## Architecture
- **Orchestrator:** OpenClaw
- **IDE:** Cursor / Claude Code
- **Models:** Claude 3.5, DeepSeek-V3, Gemini 1.5 Pro

## Current Impact
- 80% faster regression cycles.
- 1M+ tokens daily throughput for deep-scan mode.
