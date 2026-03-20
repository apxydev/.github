<p align="center">
  <img src="https://apxy.dev/logo.png" alt="APXY logo" width="88" />
</p>

<h1 align="center">APXY</h1>

<p align="center">
  <strong>Network Proxy for Developers &amp; AI Agents</strong>
</p>

<p align="center">
  Capture, inspect, mock, replay, and diff HTTP/HTTPS traffic from a CLI or Web UI.
</p>

<p align="center">
  <a href="https://apxy.dev"><strong>Start Free</strong></a> |
  <a href="https://apxy.dev/license">Pricing</a> |
  <a href="https://apxy.dev/docs">Docs</a> |
  <a href="https://apxy.dev/examples">Examples</a> |
  <a href="https://apxy.dev/for/claude-code">Claude Code Workflow</a>
</p>

APXY helps developers debug with evidence instead of guesswork.

It sits between your app and the network so you can see what actually happened: the full request, the response, the headers, the timing, and the failure pattern. Then you can mock the dependency, replay the request after a fix, diff the result, and hand the exact evidence to a teammate or AI coding agent.

## Products

### Free

Try APXY without an account or credit card.

Features:

- Web UI access
- 200 traffic records
- 3 active mock rules
- Core CLI commands
- 30-minute sessions

Best for: first-time users, quick debugging, and evaluating the workflow

### Pro - $59 one-time

Unlimited captures and advanced debugging on one machine.

Features:

- Full Web UI
- All CLI commands unlocked
- Unlimited traffic and mock rules
- Replay, diff, and API diagnosis
- Interceptors, scripts, and breakpoints
- Network simulation
- 1 year of updates

Best for: daily debugging, solo developers, and AI-assisted workflows

### Personal - $79 one-time

Everything in Pro on two machines.

Features:

- Everything in Pro
- 2 devices simultaneously
- Easy device transfer
- 1 year of updates

Best for: developers who want one license across work and personal environments

See current pricing and license recovery at [apxy.dev/license](https://apxy.dev/license).

## Why Teams Use APXY

- Capture the exact failing request instead of inferring from source code
- Mock broken or unfinished APIs so frontend and QA can keep moving
- Replay requests after a fix and prove the response changed
- Export reproducible artifacts for bug reports, reviews, and debugging handoff
- Give Claude Code, Cursor, Codex, or Copilot the network context your editor cannot see

## Quick Start

```bash
brew tap apxydev/apxy https://github.com/apxydev/apxy
brew install apxy

apxy start
curl https://httpbin.org/get
```

Open `http://localhost:8082` to inspect traffic in the Web UI.

## Repositories

| Repository | Purpose |
| --- | --- |
| [apxy](https://github.com/apxydev/apxy) | Public entry point, releases, mock templates, examples, and installation paths |
| [apxy-core](https://github.com/apxydev/apxy-core) | Core proxy engine, CLI, Web UI integration, and product internals |
| [apxy-docs](https://github.com/apxydev/apxy-docs) | Documentation site |
| [apxy-website](https://github.com/apxydev/apxy-website) | Marketing site, pricing, workflow pages, and distribution content |

## How It Works

1. Start APXY and reproduce the failing workflow.
2. Inspect the request, response, headers, body, and timing.
3. Mock, replay, diff, or export the traffic until the problem is isolated.
4. Patch the code with real network evidence in hand.
5. Re-run the request and verify the fix.

## Good Fit For

- Frontend teams blocked on unstable backends
- Backend engineers debugging real client traffic
- QA teams that need deterministic responses
- Product teams adopting AI coding tools
- Developers replacing ad hoc proxy debugging with a repeatable system

## Support

- Website: [apxy.dev](https://apxy.dev)
- Docs: [apxy.dev/docs](https://apxy.dev/docs)
- Main repo: [github.com/apxydev/apxy](https://github.com/apxydev/apxy)
- Issues: [github.com/apxydev/apxy/issues](https://github.com/apxydev/apxy/issues)
- Discussions: [github.com/apxydev/apxy/discussions](https://github.com/apxydev/apxy/discussions)
- Email: [support@apxy.dev](mailto:support@apxy.dev)

---

Built for developers who debug with evidence.
