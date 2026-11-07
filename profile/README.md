# Your AI agent asks. The right person answers, from their phone.

Pushary sends your AI coding agents' approvals and questions to your phone, Mac or dashboard, and the answer goes back to the session.

## Use Pushary with your coding agents

```bash
npx pushary@latest setup
```

One command connects Claude Code, Codex, Cursor, Gemini CLI, OpenCode, Hermes and more. Start with the [skill and agent integrations](https://github.com/Pushary/pushary-skill), or the [Cursor plugin](https://github.com/Pushary/cursor-plugin), [VS Code plugin](https://github.com/Pushary/vscode-plugin), [Claude Chat and Code plugin](https://github.com/Pushary/claude-plugin) or [Claude Cowork plugin](https://github.com/Pushary/cowork-plugin). Hermes users can install the [Pushary plugin](https://github.com/Pushary/hermes-plugin-pushary). Choose one Pushary installation per app. The plugin source is MIT-licensed; phone delivery needs a hosted Pushary plan.

## Pushary for Teams

Each person's agents ask that person. An owner can send a chosen step, such as `git push` to the `infra` repository, to a lead or a role instead, with one routing rule that covers Claude Code, Codex, Cursor and Gemini CLI. The team gets one record of whose agent asked and who answered. [See how it works](https://pushary.com/teams?utm_source=github&utm_medium=org-profile&utm_campaign=team&utm_content=teams).

## Build customer approvals into your own product

The framework adapters are MIT-licensed. Real phone delivery uses the hosted Pushary Partner service. Your customer installs the app; they do not need a Pushary account or paid plan.

| Your framework | Start here |
| --- | --- |
| Mastra | [Agent approvals, questions and persisted resume](https://github.com/Pushary/pushary-mastra) |
| Vercel AI SDK | [Question tools and enforced tool approvals](https://github.com/Pushary/pushary-ai-sdk) |
| LangGraph / LangChain | [Checkpointed reviews in TypeScript and Python](https://github.com/Pushary/pushary-langgraph) |
| OpenAI Agents SDK | [Questions and tool approval interruptions](https://github.com/Pushary/pushary-openai-agents) |
| Claude Agent SDK | [Phone approval hooks for agent tools](https://github.com/Pushary/pushary-claude-agent-sdk) |
| Eve | [Question tools and an installable extension](https://github.com/Pushary/pushary-eve) |
| Durable workflows | [Persist a decision and resume after review](https://github.com/Pushary/pushary-durable) |
| CrewAI | [Ask for a customer decision from a task](https://github.com/Pushary/pushary-crewai) |
| Pydantic AI | [Question tools and approval handling](https://github.com/Pushary/pushary-pydantic-ai) |
| Haystack | [Questions inside a pipeline](https://github.com/Pushary/pushary-haystack) |
| n8n | [Send updates and wait for an answer](https://github.com/Pushary/n8n-nodes-pushary) |

[Try the browser demo](https://pushary.com/try?utm_source=github&utm_medium=org-profile&utm_campaign=partner&utm_content=demo) · [Read the integration guide](https://pushary.com/docs/agents/adapters?utm_source=github&utm_medium=org-profile&utm_campaign=partner&utm_content=guide) · [Start Partner onboarding](https://pushary.com/sign-up?from=agent&plan=partner&utm_source=github&utm_medium=org-profile&utm_campaign=partner&utm_content=partner-start)

For Python examples, start with the [Python recipe hub](https://github.com/Pushary/pushary-python).

The browser demo uses temporary state and does not prove native push delivery. Repository examples explain how to run locally and connect a real test phone. Your application keeps ownership of authentication, execution, persistence and recovery.

## Help improve an integration

Open an issue or pull request in the relevant repository. Useful contributions include a small runnable example, a reproducible bug and clearer integration instructions. Read the [contribution guide](https://github.com/Pushary/.github/blob/main/CONTRIBUTING.md). Accepted patches are ported to the source packages and credited when shipped.

Pushary's public repositories contain integration and plugin source. The hosted service is not an open-source backend.
