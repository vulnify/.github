<p align="center">
  <img src="logo.svg" width="72" alt="Vulnify logo">
</p>

<h3 align="center">Runtime authorization for AI agents</h3>

<p align="center">
  Before a sensitive tool call runs, ask Vulnify and get <b>ALLOW</b>, <b>REVIEW</b> or <b>BLOCK</b>,<br>
  with a 0–100 risk score and the reasons behind it.
</p>

<p align="center">
  <a href="https://www.vulnify.io">Website</a> ·
  <a href="https://docs.vulnify.io">Docs</a> ·
  <a href="https://docs.vulnify.io/mcp/">MCP server</a> ·
  <a href="https://x.com/vulnify">X</a>
</p>

---

**How it works**

- Your agent's code calls `check()` or `guard()` before it reads, writes, deletes, exports or sends data.
- **REVIEW** pauses only that action until a different person approves it, in Vulnify or in Slack.
- Start in monitor mode. Checks fail closed by default.
- Policies are code: pull, test and apply them from the CLI.
- Every decision lands in a hash-chained audit log, exportable as JSON or CSV.

**Open source**

| Repo | What it is |
|---|---|
| [vulnify-sdk](https://github.com/vulnify/vulnify-sdk) | Node.js SDK and CLI · `npm i @vulnify/sdk` · LangChain, Vercel AI SDK, OpenAI Agents SDK and MCP adapters |
| [vulnify-sdk-python](https://github.com/vulnify/vulnify-sdk-python) | Python SDK and CLI · `pip install vulnify` · CrewAI and LangGraph adapters |
| [vulnify-mcp](https://github.com/vulnify/vulnify-mcp) | MCP server for Claude, Cursor and Grok · hosted at `https://mcp.vulnify.io/mcp` with OAuth |

**Get started:** [free plan](https://app.vulnify.io) · **Security:** [security@vulnify.io](mailto:security@vulnify.io)
