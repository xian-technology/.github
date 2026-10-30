# Xian Technology

**Python-first infrastructure for programmable networks and decentralized applications.**

Write smart contracts in Python, run application-specific networks, and connect
shared state to your software through Python and JavaScript / TypeScript SDKs.
Xian brings together CometBFT consensus, a deterministic contract compiler and
VM, and tools for building, testing, and operating the full stack.

The project prioritizes ease of use, flexible network composition, and
operational clarity.

*Xian [ shee - ahn ]: an immortal or transcendent being in Taoist tradition.*

[Website](https://xian.technology) · [Documentation](https://docs.xian.technology) · [Contract playground](https://playground.xian.technology)

## Start Here

| I want to… | Start with |
| --- | --- |
| Learn and try smart contracts | [Documentation](https://docs.xian.technology), the [sandbox playground](https://playground.xian.technology), and [example contracts](https://github.com/xian-technology/xian-contracts) |
| Build an application | The [Python SDK](https://github.com/xian-technology/xian-py) or [JavaScript / TypeScript SDK](https://github.com/xian-technology/xian-js) |
| Run a local node or network | [xian-cli](https://github.com/xian-technology/xian-cli), backed by [xian-stack](https://github.com/xian-technology/xian-stack) and [xian-configs](https://github.com/xian-technology/xian-configs) |
| Work with AI assistants | [Agent skills](https://github.com/xian-technology/xian-ai-skills), [context guides](https://github.com/xian-technology/xian-ai-guides), and the [MCP server](https://github.com/xian-technology/xian-mcp-server) |
| Contribute across repositories | The [workspace guide](https://github.com/xian-technology/xian-meta/blob/main/docs/WORKSPACE.md) and each repository's README |

## Network Status

The current codebase has no active public mainnet or public testnet. Start with
local nodes or localnet. Public-network deployment requires an accepted launch
manifest; see the [mainnet launch plan](https://github.com/xian-technology/xian-meta/blob/main/docs/MAINNET_LAUNCH_PLAN.md)
and [compiler/runtime readiness](https://github.com/xian-technology/xian-meta/blob/main/docs/COMPILER_RUNTIME_LAUNCH_STATUS.md).

Historical public-network material belongs to the `xian.org` ecosystem and is
not a default target for these repositories.

## Repositories

### Core Protocol

| Repository | Purpose |
| --- | --- |
| [xian-abci](https://github.com/xian-technology/xian-abci) | CometBFT-facing node runtime, deterministic chain execution, state snapshots, and indexing services |
| [xian-contracting](https://github.com/xian-technology/xian-contracting) | Contract compiler, VM crates, source and artifact utilities, local test harness, and runtime packages |

### Node Operations

| Repository | Purpose |
| --- | --- |
| [xian-cli](https://github.com/xian-technology/xian-cli) | Operator CLI for network setup, node lifecycle, health checks, and automation |
| [xian-configs](https://github.com/xian-technology/xian-configs) | Canonical network manifests, genesis assets, templates, and system contracts |
| [xian-stack](https://github.com/xian-technology/xian-stack) | Docker images, Compose topology, localnet, monitoring, and the runtime backend used by the CLI |
| [xian-deploy](https://github.com/xian-technology/xian-deploy) | Ansible deployment of released node images and prepared node homes to Linux hosts |
| [xian-governance-web](https://github.com/xian-technology/xian-governance-web) | Validator governance console for proposals, voting, and chain status |
| [xian-migration](https://github.com/xian-technology/xian-migration) | Optional offline tooling to convert exported legacy chain state into genesis for the current VM and verify the result |

### SDKs and Developer Tools

| Repository | Purpose |
| --- | --- |
| [xian-py](https://github.com/xian-technology/xian-py) | Python SDK for wallets, transactions, contracts, and asynchronous integrations |
| [xian-js](https://github.com/xian-technology/xian-js) | JavaScript / TypeScript SDK for browser apps, wallets, providers, and dapps |
| [xian-linter](https://github.com/xian-technology/xian-linter) | Contract linting with PyFlakes and authoritative Rust compiler diagnostics |
| [xian-playground-web](https://github.com/xian-technology/xian-playground-web) | Browser contract playground with an isolated VM sandbox for authoring, linting, deployment, and calls |
| [xian-ide-web](https://github.com/xian-technology/xian-ide-web) | Web IDE for writing, testing, deploying, and interacting with contracts |

### Wallets

| Repository | Purpose |
| --- | --- |
| [xian-wallet-browser](https://github.com/xian-technology/xian-wallet-browser) | Browser wallet built on the official JavaScript / TypeScript SDK |
| [xian-wallet-mobile](https://github.com/xian-technology/xian-wallet-mobile) | Mobile wallet app for the Xian ecosystem |

### Contract Standards and Examples

| Repository | Purpose |
| --- | --- |
| [xian-xips](https://github.com/xian-technology/xian-xips) | Xian standards and improvement proposals, reference implementations, and interoperability tests |
| [xian-contracts](https://github.com/xian-technology/xian-contracts) | Python contract examples and reference contracts |
| [xian-contracting-hub-web](https://github.com/xian-technology/xian-contracting-hub-web) | Curated contract catalog for browsing, inspecting, rating, and deploying contracts |

### AI and Agents

| Repository | Purpose |
| --- | --- |
| [xian-mcp-server](https://github.com/xian-technology/xian-mcp-server) | Local MCP and HTTP tools for AI assistants to work with wallets, contracts, indexed data, and DEX flows |
| [xian-ai-guides](https://github.com/xian-technology/xian-ai-guides) | LLM context guides for contracts, GraphQL queries, and tests |
| [xian-ai-skills](https://github.com/xian-technology/xian-ai-skills) | Reusable agent skills for SDK, node, and contract development workflows |
| [xian-intentkit](https://github.com/xian-technology/xian-intentkit) | IntentKit fork for building AI agents with reusable skills and blockchain actions |
| [xian-tg-bot](https://github.com/xian-technology/xian-tg-bot) | Plugin-first Telegram bot framework for Xian |

### Applications, Protocols, and Integrations

| Repository | Purpose |
| --- | --- |
| [xian-dex](https://github.com/xian-technology/xian-dex) | DEX contracts, bootstrap tooling, and the SnakX web frontend |
| [xian-dex-automation](https://github.com/xian-technology/xian-dex-automation) | Deterministic DEX automation sidecar for event-driven trading rules |
| [xian-nft](https://github.com/xian-technology/xian-nft) | XSC-0005 contracts, bootstrap tooling, and the PixelSnek NFT marketplace |
| [xian-stable-protocol](https://github.com/xian-technology/xian-stable-protocol) | Overcollateralized stable-vault protocol and bootstrap tooling |
| [xian-bridge](https://github.com/xian-technology/xian-bridge) (private) | Solana–Xian token bridge service, user interface, and operator console; repository access required |

### Documentation and Organization

| Repository | Purpose |
| --- | --- |
| [xian-docs-web](https://github.com/xian-technology/xian-docs-web) | Source for the Xian Technology documentation site |
| [xian-technology-web](https://github.com/xian-technology/xian-technology-web) | Source for the Xian Technology website |
| [xian-meta](https://github.com/xian-technology/xian-meta) | Workspace inventory, shared conventions, cross-repository designs, and launch planning |

## Contributing and Community

Use the [workspace guide](https://github.com/xian-technology/xian-meta/blob/main/docs/WORKSPACE.md)
to find the owning repository, then follow its README and contribution guidance.
For vulnerabilities, follow the [security policy](https://github.com/xian-technology/.github/blob/main/SECURITY.md).

[Telegram](https://t.me/xian_network) · [Discord](https://discord.gg/8W9ZMxUYuA) · [Forum](https://forum.xian.org)
