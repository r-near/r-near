<h1 align="center">hey, i'm ricky 👋</h1>

<p align="center">
  <strong>Developer Experience @ <a href="https://near.org">NEAR</a></strong><br/>
  <em>Responsible for 30+ repos across the NEAR stack — from the core binary to frontend SDKs</em>
</p>

<p align="center">
  <a href="https://github.com/near"><code>near</code></a> ·
  <a href="https://github.com/Near-One"><code>Near-One</code></a> ·
  <a href="https://github.com/r-near"><code>r-near</code></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" />
  <img src="https://img.shields.io/badge/NEAR-00C08B?style=flat-square&logo=near&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

---

I lead Developer Experience at [NEAR Protocol](https://near.org), where my team owns the developer-facing surface of the entire chain — SDKs, CLI tools, testing infrastructure, documentation, and contract toolchains across TypeScript, Rust, and Python.

I'm a contributor to [nearcore](https://github.com/near/nearcore) (the NEAR node implementation), and actively maintain or contribute to **30+ repositories** across the [near](https://github.com/near) and [Near-One](https://github.com/Near-One) organizations.

---

### 🛠 Developer Infrastructure

Build tools, CLI tools, testing infrastructure, and the repos that keep the NEAR developer platform running.

| Project | What it does |
|---|---|
| [**nearcore**](https://github.com/near/nearcore) | NEAR node implementation in Rust — consensus, runtime, state storage |
| [**near-sdk-rs**](https://github.com/near/near-sdk-rs) | Rust smart contract SDK — macros, collections, cross-contract calls, host function bindings |
| [**cargo-near**](https://github.com/near/cargo-near) | Cargo extension for building, testing & deploying NEAR contracts |
| [**near-cli-rs**](https://github.com/near/near-cli-rs) | Full-featured NEAR CLI in Rust — account management, contract interaction, key management |
| [**near-sandbox-js**](https://github.com/near/near-sandbox-js) | Local NEAR sandbox for JavaScript testing environments |
| [**near-sandbox-rs**](https://github.com/near/near-sandbox-rs) | Local NEAR sandbox for Rust testing environments |
| [**near-http-fetch**](https://github.com/r-near/near-http-fetch) | Call off-chain HTTP APIs from smart contracts using yield/resume |
| [**pagoda-relayer-rs**](https://github.com/near/pagoda-relayer-rs) | Meta-transaction relayer — gasless transactions for end users |

---

### 🔧 Serialization & Code Generation

NEAR uses [Borsh](https://borsh.io) for binary serialization. I built a suite of tools that make Borsh ergonomic across languages and enable cross-language code generation.

| Project | What it does |
|---|---|
| [**zorsh**](https://github.com/r-near/zorsh) | TypeScript-first Borsh serialization with a Zod-like API and full type inference |
| [**zorsh-gen-rs**](https://github.com/r-near/zorsh-gen-rs) | Code generator: Rust Borsh structs → Zorsh TypeScript schemas |
| [**zorsh-schema-gen**](https://github.com/r-near/zorsh-schema-gen) | Generate Zorsh schemas from Borsh schema definitions |
| [**borsh-schema-export**](https://github.com/r-near/borsh-schema-export) | Export BorshSchemaContainer as JSON for cross-language codegen |
| [**near-abi-ts**](https://github.com/r-near/near-abi-ts) | Pure TypeScript type inference from NEAR smart contract ABIs |

---

### 📦 Client SDKs & Libraries

Frontend and backend libraries for building on NEAR — from low-level RPC clients to high-level React integrations.

| Project | What it does |
|---|---|
| [**near-kit**](https://github.com/r-near/near-kit) | Ergonomic TypeScript library for NEAR — RotatingKeyStore, meta-transactions, NEP-413 signing |
| [**near-api-js**](https://github.com/near/near-api-js) | The primary JavaScript library for interacting with NEAR |
| [**near-api-rs**](https://github.com/near/near-api-rs) | Rust client library for interacting with NEAR |
| [**wallet-selector**](https://github.com/near/wallet-selector) | Browser wallet integration — connect any NEAR wallet to your dApp |
| [**near-stream**](https://github.com/r-near/near-stream) | Real-time SSE stream of NEAR blocks — hosted at [live.near.tools](https://live.near.tools) |
| [**omni-transactions-sdk**](https://github.com/r-near/omni-transactions-sdk) | TypeScript SDK for NEAR Chain Signatures (MPC) — multi-chain transaction signing |

---

### 🌉 Cross-Chain Bridge Infrastructure

The [Omni Bridge](https://github.com/Near-One/omni-bridge) connects NEAR to Ethereum, Solana, Bitcoin, and more. I architected the SDK and maintain key bridge infrastructure — from smart contracts and light clients to Kubernetes deployments.

| Project | What it does |
|---|---|
| [**bridge-sdk-js**](https://github.com/Near-One/bridge-sdk-js) | Omni Bridge TypeScript SDK — initiate and track cross-chain transfers |
| [**omni-bridge**](https://github.com/Near-One/omni-bridge) | Core bridge smart contracts — token locking, minting, and cross-chain messaging |
| [**rainbow-bridge**](https://github.com/Near-One/rainbow-bridge) | Ethereum ↔ NEAR trustless bridge — light clients, proofs, and relayer infrastructure |
| [**bridge-infra-k8s**](https://github.com/Near-One/bridge-infra-k8s) | Kubernetes infrastructure for bridge services — RPC proxies, relayers, container orchestration |
| [**x402-near-demo**](https://github.com/r-near/x402-near-demo) | Gasless HTTP payments on NEAR via meta-transactions (x402 protocol) |

---

### 🐍 Python Smart Contracts

NEAR smart contracts compile to WebAssembly. Traditionally, that's been Rust-only territory. I built a full toolchain that lets developers write smart contracts in **Python** and compile them to WASM that runs on NEAR.

| Project | What it does |
|---|---|
| [**near-sdk-py**](https://github.com/r-near/near-sdk-py) | Pythonic SDK for NEAR smart contracts — decorators, collections, cross-contract calls |
| [**nearc**](https://github.com/r-near/nearc) | Python contract compiler — compiles Python to WASM with reproducible builds & ABI |
| [**monty-near-cli**](https://github.com/r-near/monty-near-cli) | Alternative approach: compile Python → Rust → WASM via the Monty compiler |
| [**near-pytest**](https://github.com/r-near/near-pytest) | pytest-native testing framework for NEAR smart contracts |
| [**pyborsh**](https://github.com/r-near/pyborsh) | Pydantic-native Borsh serialization for Python |

---

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=r-near&show_icons=true&theme=transparent&hide_border=true&hide_title=true&count_private=true&icon_color=00C08B" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=r-near&layout=compact&theme=transparent&hide_border=true&hide_title=true&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=r-near&theme=transparent&hide_border=true&ring=00C08B&fire=00C08B&currStreakLabel=00C08B" />

</div>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=r-near&color=00C08B&style=flat-square&label=Profile+Views" />
</p>
