# Ammora Swap

Exchange on GIWA Sepolia testnet (chain 91342), built with `@ammora-protocol/sdk@0.3.9` for the Ammora Season 2 Builder mission.

- Pay with native ETH (default): one click swaps — the app wraps the exact amount you need into WETH automatically as part of the swap flow, because the Ammora native router has not enabled these launch curves. WETH is also selectable directly.
- Live quotes from real Ammora V4 launch curves (discovered on-chain via `discoverAmmoraPools`)
- Swap via `AmmoraSwapClient` direct dbc `prepareExactIn` + wallet execution (approvals + simulation)
- Wallet connect (MetaMask) with automatic GIWA Sepolia network add/switch
- Wrap testnet ETH → WETH helper

Testnet only.
