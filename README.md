# Arbitrum Interop Quickstart

This monorepo will help you get started with building on Arbitrum. It provides various simple demos showing and explaining how to interact with Arbitrum — deploying and using contracts directly on L2, moving Ether and tokens betweens L1 and L2, and more.

We show how you can use broadly supported Ethereum ecosystem tooling (Hardhat, Ethers-js, etc.) as well as our special [arb-ts](https://github.com/OffchainLabs/arbitrum/tree/master/packages/arb-ts) library for convenience.

## Installation

From root directory:

```bash
yarn install
```

## What's included?

#### :white_check_mark: Basics

- 🐹 [Pet Shop DApp]() (L2 only)

#### :white_check_mark: Moving Stuff around

- ⤴️ 🔹 [Deposit Ether](./packages/eth_deposit/README.md)
- ⤵️ 🔹 [Withdraw Ether](./packages/eth_withdraw/README.md)
- ⤴️ 💸 [Deposit Token](./packages/token_deposit/README.md)
- ⤵️ 💸 [Withdraw token](./packages/token_withdraw/README.md)

#### :white_check_mark: General Interop

- 🤝 [Greeter](./packages/greeter/README.md) (L1 to L2)
- 📤 [Outbox](./packages/outbox-execute/README.md) (L2 to L1)

#### :white_check_mark: Advanced Features

- ®️ [Arb Address Table](./packages/address_table/README.md)

<p align="center">
  <img width="350" height="100" src= "https://arbitrum.io/wp-content/uploads/2021/01/cropped-Arbitrum_Horizontal-Logo-Full-color-White-background-scaled-1.jpg" />
</p>
