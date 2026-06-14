[![GitHub stars](https://img.shields.io/github/stars/harrylyu20260808-pixel/AI-Dev-discassion)](https://github.com/harrylyu20260808-pixel/AI-Dev-discassion/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/harrylyu20260808-pixel/AI-Dev-discassion)](https://github.com/harrylyu20260808-pixel/AI-Dev-discassion/network)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# 🧠 AI Dev Discussion & Skills Collection

> Curated collection of AI-powered development skills, prompts, and automation scripts — designed for Claude Code, GLM, and other LLM coding agents.

## 🎯 What's Inside

This repository contains battle-tested **skills** (workflow templates) that turn AI into a productive coding partner.

### ✨ Featured Skills

| Skill | Description |
|-------|-------------|
| **github-bounty-scanner** | Scan GitHub issues for reproducible bugs with clear rewards |
| **auto-pr-generator** | Generate fix, run tests, and create PR with AI-assisted disclaimer |
| **code-review-assistant** | Review PR diffs for security, performance, and style issues |
| **test-writer** | Generate unit tests from code context (pytest/jest) |
| **doc-updater** | Automatically update README and inline docs on code changes |

### 🛠️ Prerequisites

- Node.js 18+ / Python 3.9+
- Claude Code (`npm install -g @anthropic-ai/claude-code`) or any LLM proxy (LiteLLM, OpenRouter)
- GitHub CLI (`gh`) authenticated

## 🚀 Quick Start

```bash
git clone https://github.com/harrylyu20260808-pixel/AI-Dev-discassion.git
cd AI-Dev-discassion
cp skills/github-bounty-scanner.md ~/.claude/skills/