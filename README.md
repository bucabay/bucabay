<div align="center">

# Gabirieli Lalasava

**Senior full-stack engineer · founder of [MailKite](https://mailkite.dev)**

I build email and agent infrastructure, and open-source the parts that do not need to be a company.

[Portfolio](https://gabe.mailkite.dev) · [Blog](https://bucabay.github.io/dev-blog/) · [LinkedIn](https://www.linkedin.com/in/bucabay) · [X](https://x.com/bucabay) · [Email](mailto:bucabay@gmail.com)

</div>

---

Fifteen years of production systems, mostly where product, API and database meet. I founded **Seedess** (peer-to-peer video CDN), **MailKite** (email API) and **SendHub.ai** (WhatsApp support), and stayed to run them.

Most of what I publish here starts as a problem that would not go away: mail that has to be received, agents that have to be scheduled, secrets that have to stay out of files.

## Things I maintain

| Project | What it does | Stack |
| --- | --- | --- |
| **[Breathing Room](https://github.com/bucabay/breathing-room-app)** | A free, open-source macOS maintenance app: see what fills the disk, review what can go, and watch what grows back. | Rust · Apache-2.0 |
| **[Seal](https://github.com/bucabay/seal)** | A secrets manager CLI and GUI backed by the OS keychain — vaults, environments, and nothing sensitive written to disk. | TypeScript · Tauri |
| **[agentq](https://github.com/bucabay/agentq)** | A Postgres queue for scheduled agent runs. Lanes decide what runs in parallel; leases survive crashes. | JavaScript · Postgres |
| **[agent-workflow](https://github.com/bucabay/agent-workflow)** | AWL: an indented state-machine DSL for multi-agent tasks, with routing, evidence traces and cost hooks. | JavaScript |
| **[dlna-cast](https://github.com/bucabay/dlna-cast)** | A zero-dependency DLNA/UPnP control point for Node — discover MediaRenderers on the LAN and drive playback. | TypeScript · npm |
| **[saas-idea-hunt](https://github.com/bucabay/saas-idea-hunt)** | A Claude Code skill that mines complaints, scores the evidence, and validates demand before you build. | Claude skill |
| **[dev-blog](https://github.com/bucabay/dev-blog)** | Notes and post-mortems from building on the web. | Astro |
| **[homebrew-tap](https://github.com/bucabay/homebrew-tap)** | Homebrew formulae for Seal and the other tools here. | Ruby |

## MailKite

[MailKite](https://mailkite.dev) is where most of my time goes. It receives mail on your own verified domain and POSTs it to your endpoint as signed JSON, then sends outbound through the same API. The reusable parts are open source:

- **[mailkite/server](https://github.com/mailkite/server)** — self-hosted inbound email: Haraka MX, submission and IMAP behind one small backend contract.
- **[mailkite/webmail](https://github.com/mailkite/webmail)** — a framework-native webmail client that drops into Next.js, Astro, Nuxt and SvelteKit.
- **[mailkite/mailkite-mcp](https://github.com/mailkite/mailkite-mcp)** — an MCP server, so agents can receive and send mail.
- SDKs for Node, Python, PHP, Ruby, Go, Java and .NET, plus integrations for **[n8n](https://github.com/mailkite/n8n-nodes-mailkite)**, **[Zapier](https://github.com/mailkite/zapier-mailkite)**, **[Pipedream](https://github.com/mailkite/pipedream)**, Next.js, Nuxt, Astro and Better Auth.

The platform repository is **[mailkite/mailkite](https://github.com/mailkite/mailkite)**.

## Outside my own repos

Recent contributions:

- **[Prof-bilal/Warden](https://github.com/Prof-bilal/Warden)** — architectural principles and an isolation-backend contract for sandboxing AI agents and MCP servers.
- **[botseverywhere-ai/BotsEverywhere](https://github.com/botseverywhere-ai/BotsEverywhere)** — install documentation and stale-claim fixes for the open-source bot team-management tool.
- **[better-auth/better-auth](https://github.com/better-auth/better-auth)** — added the MailKite inbox plugin to the community plugin docs.
- **[PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream)** — MailKite's inbound-email source and Send Email action for Pipedream.

## Elsewhere

[gabe.mailkite.dev](https://gabe.mailkite.dev) is the long version: skills, experience, and the systems behind each company. I am open to senior and lead engineering roles.
