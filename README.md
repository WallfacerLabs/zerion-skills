# vaults.fyi Partner Skills for Zerion CLI

Draft partner skills for the [Zerion CLI](https://github.com/zeriontech/zerion-ai), combining [vaults.fyi](https://vaults.fyi) yield intelligence with Zerion wallet analysis and execution.

Each skill follows the [Zerion partner skill format](https://github.com/zeriontech/zerion-ai/tree/main/skills/zerion-partner-skill-creator) and lives in its own directory as a single `SKILL.md` file.

## Skills

| Skill | What it does |
|-------|-------------|
| [yield-optimizer](skills/zerion-vaultsfyi-yield-optimizer/) | Audit a wallet's positions against benchmarks, quantify opportunity cost, surface idle assets |
| [deposit](skills/zerion-vaultsfyi-deposit/) | Vault due diligence + safety-gated deposit with pre-flight risk checks |
| [market-intel](skills/zerion-vaultsfyi-market-intel/) | Benchmark rate environments, side-by-side vault comparison, curator profiles |
| [rebalance](skills/zerion-vaultsfyi-rebalance/) | Full exit-to-enter vault rotation with cross-chain bridging via Zerion |
| [watchlist](skills/zerion-vaultsfyi-watchlist/) | Multi-wallet yield monitoring using Zerion's watchlist |
| [strategist](skills/zerion-vaultsfyi-strategist/) | Backtesting, rate environment analysis, curator track records |
| [risk-monitor](skills/zerion-vaultsfyi-risk-monitor/) | Flag and incident tracking, score degradation, capital flight detection, withdrawal readiness |

## How the tools work together

- **Zerion CLI** handles wallet analysis (`zerion analyze`, `zerion positions`), execution (`zerion swap`, `zerion bridge`), and wallet management (`zerion watch`).
- **vaults.fyi MCP** provides yield intelligence: vault search and ranking, risk scores, curator data, benchmark rates, historical APY/TVL, and transaction construction.

Zerion answers "what do I have?" vaults.fyi answers "how is it performing and what should I do about it?"

## Requirements

- [Zerion CLI](https://github.com/zeriontech/zerion-ai) installed with API key
- [vaults.fyi hosted MCP v2](https://mcp.vaults.fyi/mcp) connected

## Status

These are drafts for review. Feedback welcome via issues or directly.

## License

MIT
