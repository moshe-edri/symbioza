<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/symbioza-logo-dark.png">
    <img alt="Symbioza" src="assets/symbioza-logo-light.png" width="300">
  </picture>
</p>
<h3 align="center">Run GPU jobs without managing GPU infrastructure.</h3>
<p align="center">
  <a href="https://symbioza.dev">symbioza.dev</a> · <a href="https://symbioza.dev/agent">For agents</a> · <a href="https://symbioza.dev/examples">Examples</a> · <a href="https://github.com/symbioza/claude-plugin">Claude Code plugin</a> · <a href="https://x.com/SymbiozaDev">X</a>
</p>

Symbioza runs a containerized GPU job on a rented cloud machine under a hard dollar ceiling and collects available artifacts. An agent submits an image, a command and a budget through one MCP connector. Symbioza selects compute, runs the job and reports output delivery and billing separately. Recovery depends on job policy, available compute, remaining budget and compatible checkpoint support.

**Use it from Claude Code**, with one plugin:

```bash
claude plugin marketplace add symbioza/claude-plugin
claude plugin install symbioza@symbioza
```

Or connect an MCP client to `https://symbioza.dev/mcp`. Sign in through the browser; estimates are free.
