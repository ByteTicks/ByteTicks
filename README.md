# ByteTicks

ByteTicks is a desktop trading and analysis terminal for cryptocurrency markets. It brings price charts, order-flow analysis, locally recorded market history, and paper trading into one workspace for traders and market researchers.

The focus is on understanding market activity: how price moves, where trading volume is concentrated, and how visible liquidity changes. Recorded data lets users revisit that activity and investigate trading ideas.

## Core capabilities

| Area | What it enables |
| --- | --- |
| **Market observation** | Follow live exchange trades and order-book data alongside price charts and indicators. |
| **Order-flow analysis** | Examine buying and selling volume with footprint charts, inspect visible liquidity with heatmaps, and set alerts on market conditions. |
| **History and research** | Record market data locally for later analysis. Historical replay and backtesting tools are being developed around the available recorded data. |
| **Paper trading** | Place simulated orders, manage simulated positions, and review trading results without committing real funds. |

![ByteTicks product map: market observation, order-flow analysis, history and research, and paper trading](product-map/ByteTicks-Product-Map.png)

[Editable Obsidian Canvas](product-map/ByteTicks-Product-Map.canvas)

## Engineering scope

The work spans streaming market data, chart rendering, local storage, and simulated order execution. Key engineering tasks include:

- Keeping live updates and historical views consistent when users change instruments or time ranges.
- Maintaining responsive charts while market data arrives and users interact with the workspace.
- Keeping simulated orders, fills, positions, and account balances consistent throughout a trading session.

**Stack:** React, TypeScript, Rust, and Tauri.

## Status

ByteTicks is under active development toward its first MVP. There is no commercial release yet. The main application source code is private; this repository contains its public overview.
