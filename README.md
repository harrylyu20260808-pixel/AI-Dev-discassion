```markdown
[![GitHub stars](https://img.shields.io/github/stars/harrylyu20260808-pixel/AI-Dev-discassion)](https://github.com/harrylyu20260808-pixel/AI-Dev-discassion/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/harrylyu20260808-pixel/AI-Dev-discassion)](https://github.com/harrylyu20260808-pixel/AI-Dev-discassion/network)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

# 🧠 AI Dev Discussion & Skills Collection

> Curated collection of AI-powered development skills, prompts, and automation scripts — designed for Claude Code, GLM, and other LLM coding agents.

## 🎯 What's Inside

This repository contains battle-tested **skills** (workflow templates) that turn AI into a productive coding partner. Originally crafted for bounty hunting, bug fixing, and automated code review, they work with any LLM that supports function calling or structured prompting.

### ✨ Featured Skills

| Skill | Description |
|-------|-------------|
| **`github-bounty-scanner`** | Scan GitHub issues for reproducible bugs with clear rewards |
| **`auto-pr-generator`** | Generate fix, run tests, and create PR with AI-assisted disclaimer |
| **`code-review-assistant`** | Review PR diffs for security, performance, and style issues |
| **`test-writer`** | Generate unit tests from code context (pytest/jest) |
| **`doc-updater`** | Automatically update README and inline docs on code changes |

### 🛠️ Prerequisites

- Node.js 18+ / Python 3.9+
- Claude Code (`npm install -g @anthropic-ai/claude-code`) or any LLM proxy (LiteLLM, OpenRouter)
- GitHub CLI (`gh`) authenticated

## 🚀 Quick Start

```bash
git clone https://github.com/harrylyu20260808-pixel/AI-Dev-discassion.git
cd AI-Dev-discassion
# Copy a skill to your Claude projects directory
cp skills/github-bounty-scanner.md ~/.claude/skills/
```

Then in any Claude Code session, just type /github-bounty-scanner to activate.

📚 How to Use

Each skill is a self-contained .md file that you can:

· Place in ~/.claude/skills/ (global) or project's .claude/skills/
· Invoke with slash command: /skill-name
· Customize by editing the YAML frontmatter and instructions

🤝 Contributing

We welcome new skills! Please see CONTRIBUTING.md (coming soon).
Ideas needed:

· Dockerfile linter
· Dependency vulnerability checker
· Commit message generator (Conventional Commits)

📄 License

MIT — free for personal and commercial use.

💬 Community

· GitHub Discussions (coming soon)
· 中文用户交流：后续补充

⭐ Star History

If this helps you earn your first coffee money, please star the repo!
