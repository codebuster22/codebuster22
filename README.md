# Mihiir Parmar

Senior protocol engineer. I ship whole on-chain systems: contracts, indexers, keepers and the backend around them. I've written smart contracts since 2021, and they're live on 7 EVM mainnets.

I run Chain Labs, a studio that builds these systems for teams, and I write the core contracts myself. Remote from India (IST); I work my team's hours, as I did on New York hours for Movement Labs and German hours for Curve Labs.

## What I've shipped

- **Antigravity** (2024 to now, client). I was architect and lead smart-contract engineer of an on-chain mining game and token economy on PulseChain and Base. It has 13 contracts, a UUPS-upgradeable game layer, Chainlink VRF sourced cross-chain from Base (PulseChain has no VRF), a Ponder indexer across 5 networks and AWS Lambda keepers, and it went through four audit-fix rounds. The client raised $300k+ and the token peaked near $100M FDV.
- **Prime Launch** (2021–2022, for PrimeDAO at Curve Labs). I was #1 committer on the Seed-sale and Balancer LBP launch contracts, and I wrote the EIP-1271 Signer that limits PrimeDAO's Gnosis Safe to launch-only calls. Projects raised ~$20M through it. [PrimeDAO/contracts-v2](https://github.com/PrimeDAO/contracts-v2)
- **Supermigrate and Launchbox** (2024, client). I was smart-contract lead and top committer on an OP-Stack token-migration platform and its bonding-curve launchpad on Base: a virtual-reserve curve, 512-bit mulDiv and graduation to Aerodrome. I fixed the audit's high-severity findings. An estimated ~$600M of tokens migrated through it (self-reported). [ultra-co/contracts](https://github.com/ultra-co/contracts)
- **pm-ws** (2026). A Rust (tokio) prediction-market feed daemon. It keeps one authoritative order book per Limitless market and serves it to Rust, Python and TypeScript readers over a versioned shared-memory ABI, with exact 128-bit decimals. [v0.1.0 on crates.io](https://crates.io/crates/pm-ws), MIT.
- **SafeWord** (2026). A Gnosis Safe Guard on Polygon that locks a hot bot key to whitelisted calls. It blocks delegatecall, self-call and gas-refund bypasses, and has unit, fork and invariant tests. [codebuster22/safeword](https://github.com/codebuster22/safeword)
- **Toucan** (2022, at Curve Labs). I was primary engineer of the cross-chain carbon bridge between Celo and Polygon. It has handled ~$6M of volume.
- Also: Simplr and Schmint, which fire a collector's mint from their own Gnosis Safe through a Zodiac module; Kolektivo's price-stability layer on Celo; the dSafe SDK; and [ICI Core](https://github.com/sidetrip-ai/ici-core), an open-source RAG framework with 305 stars.

Grant-funded work: Safe $25k (dSafe), Arbitrum $25k (Simplr Events), Protocol Labs $15k (Impact Evaluator) and Lit Protocol $10k (Lit Privacy SDK).

## Contracts I wrote, live on mainnet

| Chain | Contract | Address |
| --- | --- | --- |
| Ethereum | Prime Launch SeedFactory | [0x1696…2e76](https://etherscan.io/address/0x16967bA683bFA5BD545AA196F30bd7fDc6e32e76) |
| Ethereum | Prime Launch Signer (EIP-1271) | [0x646C…B0C3](https://etherscan.io/address/0x646C01b59d05305103BF1Ed82EcA22D0D1CbB0C3) |
| Ethereum | Schmint SchedulerFactory | [0x57Db…031A](https://etherscan.io/address/0x57Dbc4437886fb27186665BbA333A926e913031A) |
| PulseChain | Antigravity MiningRig | [0x1Eca…9FBd](https://scan.pulsechain.com/address/0x1Eca1A64E18E72c46971a80D91F015a569FE9FBd) |
| Base | Antigravity MiningRig | [0x698A…d904](https://basescan.org/address/0x698Ae58B7AB13ad232A84d684e8111D2c6A6d904) |
| Base | Antigravity RNG (Chainlink VRF) | [0x4f1c…883A](https://basescan.org/address/0x4f1c4b65db4ADD90A30caf1194E8d4b318Db883A) |
| Base | Launchbox factory | [0x5946…8F34](https://basescan.org/address/0x594668EC8be3b44339eea4c24c8707A103328F34) |
| Optimism | Supermigrate SuperERC20Factory | [0x885E…c19F](https://optimistic.etherscan.io/address/0x885E7a50287d62Fc4b490EB38eA599bF2F48c19F) |
| Arbitrum | Simplr Events EventsFactory | [0x0864…2f5d](https://arbiscan.io/address/0x086403746969b97ee486A4a3519C1aFa18292f5d) |
| Celo | Kolektivo BalancerV2Proxy | [0x2BdE…FCD4](https://celoscan.io/address/0x2BdE6D6d622226b48A0d9F9066A0a3e38158FCD4) |
| Polygon | SafeWord GuardFactory | [0x5120…AdC5](https://polygonscan.com/address/0x5120F677C9a453AC960eCA1fb274D25D96aAAdC5) |
| Polygon | Polymarket CTF vault | [0x28a7…a2ae](https://polygonscan.com/address/0x28a702e64e53935e4d469b82d149ce7be86fa2ae) |
| Polygon and Celo | Toucan CrosschainMessenger (deployed by Toucan's team) | [0xABaC…Acaf](https://polygonscan.com/address/0xABaC3D6b281Bbe0Fc0F67b26247cB27994eaAcaf) |

## How I work

I work AI-native: a team of agents in a controlled setup, with my review and the tests gating every change. My contract work carries fuzz, invariant and fork tests.

I've run Chain Labs, my studio, in 2024 and again since September 2025. Building something on-chain? Write to me, or book a call at [mihiir.com](https://mihiir.com).

mihirsinh.parmar.it@gmail.com, [LinkedIn](https://www.linkedin.com/in/mihiirparmar/), [X](https://x.com/mihiir), [mihiir.com](https://mihiir.com)
