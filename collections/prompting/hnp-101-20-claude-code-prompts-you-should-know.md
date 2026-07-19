---
title: "20 Claude Code prompts you should know"
domain: prompting
source_url: "https://www.facebook.com/aniksingalcom/posts/20-claude-code-prompts-you-should-knowsave-this-use-it-today-/1517933699696022/"
platform: facebook
author: "Anik Singal"
---

# 20 Claude Code prompts you should know

[← All prompt packs](../../CATALOG.md) · **Prompting** · [Original post ↗](https://www.facebook.com/aniksingalcom/posts/20-claude-code-prompts-you-should-knowsave-this-use-it-today-/1517933699696022/)

## Prompts

Copy a prompt and replace the bracketed text with your own context.

### 1. The Brain Dump Kickoff

```text
I have never used you before. I am going to describe my project and what I want to build. Ask me every question you need before writing a single line of code.
```

### 2. The CLAUDE.md Setup

```text
Read my codebase and write me a CLAUDE.md file that captures everything you need to know to work on this project effectively. Include architecture, conventions, and things to never do.
```

### 3. The Plan First

```text
Before touching any code, write me a detailed implementation plan for [feature]. I will approve it before you start.
```

### 4. The Rubber Duck

```text
Do not fix anything yet. Just explain to me line by line what this code is actually doing and where you think it might be going wrong.
```

### 5. The Error Explainer

```text
Here is the error I am getting: [paste error]. Explain what is causing it in plain English, then show me the fix.
```

### 6. The Second Opinion

```text
Forget everything you suggested before. Look at this bug with fresh eyes and give me a completely different approach.
```

### 7. The Brutal Review

```text
Review this code like a senior engineer who has seen every mistake. Do not be kind. Tell me what is wrong, what is fragile, and what will break in production.
```

### 8. The Security Audit

```text
Review this code specifically for security vulnerabilities. Check for injection risks, exposed credentials, broken auth, and anything that could be exploited.
```

### 9. The Performance Check

```text
Identify every performance bottleneck in this code. Prioritize them by impact and suggest fixes starting with the highest value changes.
```

### 10. The Spec Writer

```text
Turn this rough idea into a proper technical spec: [describe feature]. Include edge cases, error states, and anything a junior dev would miss.
```

### 11. The Test Writer

```text
Write comprehensive tests for this function. Cover happy paths, edge cases, and failure modes. Explain why each test matters.
```

### 12. The Refactor

```text
Refactor this code without changing its behavior. Make it cleaner, more readable, and easier to maintain. Show me a before and after diff.
```

### 13. The Context Setter

```text
Here is what I am trying to accomplish overall: [goal]. Keep this in mind for everything we do in this session. Ask me if you are ever unsure whether something serves this goal.
```

### 14. The Decision Log

```text
Every time you make a non-obvious technical decision, explain why you made it and what the alternative was. I want to understand the tradeoffs.
```

### 15. The Checkpoint

```text
Stop. Before we go further, summarize everything we have built so far, what is working, and what still needs to be done.
```

### 16. The Agent Delegator

```text
Break this large task into subtasks a team of agents could work on in parallel. Define clear inputs and outputs for each subtask.
```

### 17. The Documentation Writer

```text
Generate full documentation for this codebase. Include setup instructions, architecture overview, API reference, and common troubleshooting scenarios.
```

### 18. The Migration Planner

```text
I need to migrate from [old system] to [new system]. Write me a step-by-step migration plan that minimizes downtime and risk.
```

### 19. The Code Explainer

```text
I just inherited this codebase and I have no idea what it does. Walk me through it like you are onboarding a new engineer on their first day.
```

### 20. The Exit Interview

```text
We are ending this session. Write a handoff document summarizing what we built, every decision we made, and exactly where to pick up next time.
```
