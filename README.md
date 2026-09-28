<img src="https://symbioza.dev/brand/symbioza-appicon-dark-512.png" width="72" alt="Symbioza" align="left">

### Symbioza

**Run GPU jobs without managing GPU infrastructure.**

<br clear="left">

Symbioza runs a containerized GPU job on a rented cloud machine under a hard dollar ceiling and collects available artifacts. An agent submits an image, a command and a budget through one MCP connector. Symbioza selects compute, runs the job and reports output delivery and billing separately. Recovery depends on job policy, available compute, remaining budget and compatible checkpoint support.

**Use it from Claude Code**, with one plugin:

```bash
claude plugin marketplace add symbioza/claude-plugin
claude plugin install symbioza@symbioza
```

Or connect an MCP client to `https://symbioza.dev/mcp`. Sign in through the browser; estimates are free.

[symbioza.dev](https://symbioza.dev) · [For agents](https://symbioza.dev/agent) · [Examples](https://symbioza.dev/examples) · [The plugin](https://github.com/symbioza/claude-plugin) · [X @SymbiozaDev](https://x.com/SymbiozaDev)
