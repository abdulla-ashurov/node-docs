# cheqd: Node Documentation

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/cheqd/cheqd-node?color=green&label=stable%20release&style=flat-square)](https://github.com/cheqd/cheqd-node/releases/latest) ![GitHub Release Date](https://img.shields.io/github/release-date/cheqd/cheqd-node?color=green&style=flat-square) [![GitHub license](https://img.shields.io/github/license/cheqd/cheqd-node?color=blue&style=flat-square)](https://github.com/cheqd/cheqd-node/blob/main/LICENSE)

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/cheqd/cheqd-node?include_prereleases&label=dev%20release&style=flat-square)](https://github.com/cheqd/cheqd-node/releases/) ![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/cheqd/cheqd-node/latest?style=flat-square) [![GitHub contributors](https://img.shields.io/github/contributors/cheqd/cheqd-node?label=contributors%20%E2%9D%A4%EF%B8%8F&style=flat-square)](https://github.com/cheqd/cheqd-node/graphs/contributors)

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/cheqd/cheqd-node/Workflow%20Dispatch?label=workflows&style=flat-square)](https://github.com/cheqd/cheqd-node/actions/workflows/dispatch.yml) [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/cheqd/cheqd-node/CodeQL?label=CodeQL&style=flat-square)](https://github.com/cheqd/cheqd-node/actions/workflows/codeql.yml) ![GitHub repo size](https://img.shields.io/github/repo-size/cheqd/cheqd-node?style=flat-square)

## ℹ️ Overview

[**cheqd**](https://www.cheqd.io) is a public self-sovereign identity (SSI) network for building secure 🔐 and private 🤫 self-sovereign identity systems on [Cosmos](https://cosmos.network) 💫. Our core vision is to add viable commercial models to decentralised digital 🆔

`cheqd-node` is the ledger/node component of the cheqd network tech stack, built using [Cosmos SDK](https://github.com/cosmos/cosmos-sdk) and [Tendermint](https://github.com/tendermint/tendermint).

## ▶️ Quick start for joining cheqd networks

Join our [**cheqd Community Slack**](http://cheqd.link/join-cheqd-slack) for help, questions, and support if you are looking to join our [mainnet](https://explorer.cheqd.io) or the [testnet](https://testnet-explorer.cheqd.io/).

Either the cheqd team, or one of your fellow node operators will be happy to offer some guidance.

### ✅ Mainnet

Getting started as a node operator on the cheqd network [mainnet](https://explorer.cheqd.io) is as simple as...

1. [Install the `cheqd-node` software](docs/setup-and-configure/README.md) (**version 0.5.0+**) on a hosting platform of your choice
2. Once you have acquired CHEQ tokens, [promote your node to a validator](docs/validator-guide/README.md)

If successfully configured, your node would become the latest validator on the cheqd mainnet. Welcome to the new digital ID revolution!

### 🚧 Testnet

Our [testnet](https://testnet-explorer.cheqd.io/) is the easiest place for developers and node operators to get started if you're not *quite* ready yet to dive into building apps on our mainnet. To get started...

1. Install [v0.5.0 of cheqd-node](https://github.com/cheqd/cheqd-node/releases/tag/v0.5.0) (same version as that on mainnet)
2. Acquire testnet CHEQ tokens through [our testnet faucet](https://testnet-faucet.cheqd.io).

## 🧑‍💻 Using cheqd

Once installed, `cheqd-node` can be controlled using the [cheqd Cosmos CLI guide](docs/cheqd-cli/README.md).

### 📌 Currently supported functionality

* Basic token functionality for holding and transferring tokens to other accounts on the same network
* Creating, managing, and configuring accounts and keys on a cheqd node
* Staking and participating in public-permissionless governance
* Governance framework for public-permissionless self-sovereign identity networks
* Creating [`did:cheqd` method DIDs](architecture/adr-list/adr-002-cheqd-did-method.md), DID Documents ("DIDDocs")
* Querying DIDs/DIDDocs using our [Universal Resolver driver](https://github.com/cheqd/did-resolver)
* Creating and managing Verifiable Credentials anchored to DIDs on cheqd mainnet

### 🔮 Upcoming functionality

A non-exhaustive list of future planned functionality (not necessarily in order of priority) is highlighted below:

* Defining persistent Schemas that can be referenced using DIDs

We plan on adding new functionality rapidly and on a regular basis and welcome feedback on our [cheqd Community Slack](http://cheqd.link/join-cheqd-slack) workspace.

## 🛠 Developing & contributing to cheqd

`cheqd-node` is written in Go and built using Cosmos SDK. The [Cosmos SDK Developer Guide](https://docs.cosmos.network/) explains a lot of the [basic concepts](https://docs.cosmos.network/main/basics/app-anatomy) of how the cheqd network functions.

If you want to build a node from source or contribute to the code, please read our guide to [building and testing](docs/build-and-networks/README.md).

### Creating a local network

If you are building from source, or otherwise interested in running a local network, we have [instructions on how to set up a new network](docs/setup-and-configure/README.md) for development purposes.

## 🐞 Bug reports & 🤔 feature requests

If you notice anything not behaving how you expected, or would like to make a suggestion / request for a new feature, please create a [**new issue**](https://github.com/cheqd/cheqd-node/issues/new/choose) and let us know.

## 💬 Community

The [**cheqd Community Slack**](http://cheqd.link/join-cheqd-slack) is our primary chat channel for the open-source community, software developers, and node operators.

Please reach out to us there for discussions, help, and feedback on the project.

## 🙋 Find us elsewhere

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cheqd) [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](http://cheqd.link/discord-github) [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/follow?screen_name=cheqd_io) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](http://cheqd.link/linkedin) [![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](http://cheqd.link/join-cheqd-slack) [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://blog.cheqd.io) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCBUGvvH6t3BAYo5u41hJPzw/)
