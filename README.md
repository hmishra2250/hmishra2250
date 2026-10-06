# Himadri Mishra

I build agents, and the MCP servers, CLIs and SDKs they run on.

[himadri.dev](https://www.himadri.dev/) · [Agent Experience field guide](https://agentexperience.tech/) · [LinkedIn](https://www.linkedin.com/in/hmishra2250/) · [X](https://x.com/hmishra2250)

## Shipped in 2026

**At Mudita Studios**, where I build AI products end to end (private work)

- A coding agent that takes a Slack or Jira request to a tested, reviewed draft pull request. It works in a sandbox, tests its change in a real browser, and a second model checks the result before a person reviews it.
- A research product in production, where every claim in a report cites a source or is marked unverifiable, built on a sandboxed agent runtime with spend limits and tracing.

**At Firecrawl**, where I owned the Agent Experience programme ([merged open-source PRs](https://github.com/pulls?q=is%3Apr+author%3Ahmishra2250+org%3Afirecrawl+is%3Amerged))

- Measured and improved how AI agents discover, choose and correctly use Firecrawl across Claude Code, Codex, Cursor and other agents, and shipped the fixes.
- Contributed to the hosted MCP server: OAuth and keyless setup, a move onto upstream FastMCP, and errors that tell an agent how to recover.
- Improved tool descriptions, docs, CLI help and skills so agents choose the right tool, and added CI checks that run the docs' code samples.
- Built a daily benchmark of whether agents pick a tool and use it correctly, and a sandboxed experiment harness behind the shipped fixes. Agent Experience owner for the Developer Index and Government and Legal launches.

**My own work**

- [agentexperience.tech](https://agentexperience.tech/): a field guide to Agent Experience, with an agent-readiness rubric and a public, read-only MCP server.
- [awesome-agent-experience](https://github.com/hmishra2250/awesome-agent-experience): a curated library of sources on tool use, discovery and evaluation.
- [qwen-3.6-35b-consumer-gpu](https://github.com/hmishra2250/qwen-3.6-35b-consumer-gpu): Qwen3.6-35B running at 43 tokens per second with 128K context on my 8 GB laptop GPU, with launch scripts, a tuning guide and a coding benchmark.

## How I work

- **A tool call is not a finished task.** I check the result, not just whether the answer sounds right.
- **Agents read text, not screens.** Tool descriptions, error messages and docs are the interface, so I write them for the agent.
- **A person stays in the loop** wherever work ships.

Before that, I built Knit's agentic research platform, which cut report turnaround from 2-3 days to under an hour, after nearly six years of production ML in search, recommendations and computer vision.

<details>
<summary>Use my field guide from an agent</summary>

The public, read-only MCP endpoint is `https://agentexperience.tech/api/mcp`. See the [discovery manifest](https://agentexperience.tech/.well-known/ard.json) for the published interface.

</details>

Some professional work is private. I share the ideas and patterns, not client code, names or internal results.
