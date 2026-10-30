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

<table>
  <tbody>
    <tr><th colspan="2" align="left">Core Protocol</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-abci">xian-abci</a></td>
      <td>CometBFT-facing node runtime, deterministic chain execution, state snapshots, and indexing services</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-contracting">xian-contracting</a></td>
      <td>Contract compiler, VM crates, source and artifact utilities, local test harness, and runtime packages</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">Node Operations</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-cli">xian-cli</a></td>
      <td>Operator CLI for network setup, node lifecycle, health checks, and automation</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-configs">xian-configs</a></td>
      <td>Canonical network manifests, genesis assets, templates, and system contracts</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-stack">xian-stack</a></td>
      <td>Docker images, Compose topology, localnet, monitoring, and the runtime backend used by the CLI</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-deploy">xian-deploy</a></td>
      <td>Ansible deployment of released node images and prepared node homes to Linux hosts</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-governance-web">xian-governance-web</a></td>
      <td>Validator governance console for proposals, voting, and chain status</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-migration">xian-migration</a></td>
      <td>Optional offline tooling to convert exported legacy chain state into genesis for the current VM and verify the result</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">SDKs and Developer Tools</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-py">xian-py</a></td>
      <td>Python SDK for wallets, transactions, contracts, and asynchronous integrations</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-js">xian-js</a></td>
      <td>JavaScript / TypeScript SDK for browser apps, wallets, providers, and dapps</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-linter">xian-linter</a></td>
      <td>Contract linting with PyFlakes and authoritative Rust compiler diagnostics</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-playground-web">xian-playground-web</a></td>
      <td>Browser contract playground with an isolated VM sandbox for authoring, linting, deployment, and calls</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-ide-web">xian-ide-web</a></td>
      <td>Web IDE for writing, testing, deploying, and interacting with contracts</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">Wallets</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-wallet-browser">xian-wallet-browser</a></td>
      <td>Browser wallet built on the official JavaScript / TypeScript SDK</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-wallet-mobile">xian-wallet-mobile</a></td>
      <td>Mobile wallet app for the Xian ecosystem</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">Contract Standards and Examples</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-xips">xian-xips</a></td>
      <td>Xian standards and improvement proposals, reference implementations, and interoperability tests</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-contracts">xian-contracts</a></td>
      <td>Python contract examples and reference contracts</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-contracting-hub-web">xian-contracting-hub-web</a></td>
      <td>Curated contract catalog for browsing, inspecting, rating, and deploying contracts</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">AI and Agents</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-mcp-server">xian-mcp-server</a></td>
      <td>Local MCP and HTTP tools for AI assistants to work with wallets, contracts, indexed data, and DEX flows</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-ai-guides">xian-ai-guides</a></td>
      <td>LLM context guides for contracts, GraphQL queries, and tests</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-ai-skills">xian-ai-skills</a></td>
      <td>Reusable agent skills for SDK, node, and contract development workflows</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-intentkit">xian-intentkit</a></td>
      <td>IntentKit fork for building AI agents with reusable skills and blockchain actions</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-tg-bot">xian-tg-bot</a></td>
      <td>Plugin-first Telegram bot framework for Xian</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">Applications, Protocols, and Integrations</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-dex">xian-dex</a></td>
      <td>DEX contracts, bootstrap tooling, and the SnakX web frontend</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-dex-automation">xian-dex-automation</a></td>
      <td>Deterministic DEX automation sidecar for event-driven trading rules</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-nft">xian-nft</a></td>
      <td>XSC-0005 contracts, bootstrap tooling, and the PixelSnek NFT marketplace</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-stable-protocol">xian-stable-protocol</a></td>
      <td>Overcollateralized stable-vault protocol and bootstrap tooling</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-bridge">xian-bridge</a> (private)</td>
      <td>Solana–Xian token bridge service, user interface, and operator console; repository access required</td>
    </tr>
  </tbody>
  <tbody>
    <tr><th colspan="2" align="left">Documentation and Organization</th></tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-docs-web">xian-docs-web</a></td>
      <td>Source for the Xian Technology documentation site</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-technology-web">xian-technology-web</a></td>
      <td>Source for the Xian Technology website</td>
    </tr>
    <tr>
      <td><a href="https://github.com/xian-technology/xian-meta">xian-meta</a></td>
      <td>Workspace inventory, shared conventions, cross-repository designs, and launch planning</td>
    </tr>
  </tbody>
</table>

## Contributing and Community

Use the [workspace guide](https://github.com/xian-technology/xian-meta/blob/main/docs/WORKSPACE.md)
to find the owning repository, then follow its README and contribution guidance.
For vulnerabilities, follow the [security policy](https://github.com/xian-technology/.github/blob/main/SECURITY.md).

[Telegram](https://t.me/xian_network) · [Discord](https://discord.gg/8W9ZMxUYuA) · [Forum](https://forum.xian.org)
