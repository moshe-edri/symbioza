<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/symbioza-logo-dark.png">
    <img alt="Symbioza" src="assets/symbioza-logo-light.png" width="300">
  </picture>
</p>
<h3 align="center">Cloud GPU jobs for AI agents, under a spending limit you set.</h3>
<p align="center">
  <a href="https://symbioza.dev">symbioza.dev</a> · <a href="https://symbioza.dev/examples">Examples</a> · <a href="https://symbioza.dev/pricing">Pricing</a> · <a href="https://x.com/SymbiozaDev">X</a>
</p>

Your AI agent sends a containerized job and a total spending limit. Symbioza runs it on a cloud GPU and collects
the files it writes, and you are never billed more than your spending limit. Estimates are free.

**Start from the client you use:**

| Client | How to connect |
|---|---|
| **Claude Code** | The plugin: [symbioza/claude-plugin](https://github.com/symbioza/claude-plugin) · [setup guide](https://symbioza.dev/plugins#claude-code) |
| **ChatGPT** | [Add Symbioza to ChatGPT](https://symbioza.dev/plugins#chatgpt) |
| **Claude** | [Add it in Claude](https://symbioza.dev/plugins#claude-ai) |
| **Any other remote MCP client** | [Connect `https://symbioza.dev/mcp`](https://symbioza.dev/plugins#other-clients) |

In Claude Code:

```bash
claude plugin marketplace add symbioza/claude-plugin
claude plugin install symbioza@symbioza
```

Then run `/mcp`, pick `plugin:symbioza:symbioza` and choose **Authenticate** to sign in. Ask for a free
estimate, and submit only when you are ready.
