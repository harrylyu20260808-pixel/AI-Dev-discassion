---
name: github-bounty-scanner
description: Scan GitHub issues for reproducible bugs with clear rewards
---

# GitHub Bounty Scanner Skill

This skill helps you find and fix GitHub issues that have a clear path to bounty payment.

## When to Use
- When you want to find paid bug fixing opportunities
- When the user asks to "find a bounty" or "look for paid issues"

## What This Skill Does
1. Searches GitHub for issues with labels like `good first issue`, `bug`, `help wanted`
2. Filters by repos that have active maintainers (last commit < 30 days)
3. Checks if the issue has clear reproduction steps
4. Returns a ranked list of candidates with estimated difficulty

## Usage
Run: `/github-bounty-scanner` in Claude Code