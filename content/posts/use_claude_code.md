---
date: '2025-11-16T07:57:02-08:00'
title: 'Start Using Claude-code'
categories: ["AI"]
tags: ["LLM", "agent"]
---

AI agents are the next big breakout. Based on my recent research, only two application directions show truly remarkable potential: **deep research** and **vibe coding**. Claude Code is one of the best examples of vibe coding.

# What is Claude Code

Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows -- all through natural language commands. 

**Learn more in the [official documentation](https://docs.anthropic.com/en/docs/claude-code/overview)**.

# Personal Practice

Here is a guide to install, set and use claude code

## Install nodejs

After my practice, install from node is the current best way.
```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
```

check node and npm version
```
node -v
npm -v
```

## Install claude code

```
sudo npm install -g @anthropic-ai/claude-code
claude --version # check version
```

## Set 3-part API
You can use any other LLM service you want, here is an example of using kimi API.
```
export ANTHROPIC_BASE_URL="https://api.moonshot.cn/anthropic/"
export ANTHROPIC_API_KEY="sk---"
```

start using command **claude**

And now you can get the claude code, and start your vibe coding career!

![claude-code](https://github.com/anthropics/claude-code/blob/main/demo.gif?raw=true)
