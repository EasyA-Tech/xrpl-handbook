# The XRP Ledger Handbook

Welcome. This is EasyA's legendary handbook. If you want to learn XRP Ledger like a legend, then you're in the right place.

# Purpose

This handbook serves as a guide to the XRP Ledger ecosystem, geared towards those just joining for the first time. It isn't just a beginners' handbook; it's a legendary handbook. Even if you've already immersed yourself in the ecosystem, you'll find tons of helpful tidbits around here!

# The EasyA App

Of course, the best place to start is always the [EasyA](https://www.easya.io) app! Download it here for the fastest and most fun way to learn about XRP Ledger. Download it directly right [here](https://links.easya.io/links/gotoapp)!

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Development Tools](#development-tools)
- [Smart Contracts](#smart-contracts)
- [XRP Ledger Network](#xrp-ledger-network)
- [Ecosystem Projects](#ecosystem-projects)
- [Resources](#resources)
- [Handy Code Snippets](#handy-code-snippets)
- [Contributing](#contributing)

## Introduction

What is XRP Ledger:

- [XRPL.org](https://xrpl.org) - The go-to resource for all things XRP Ledger, including comprehensive documentation and getting started guides.

## Getting Started

The no-fluff starter:

- [XRPL.org Explorer](https://livenet.xrpl.org) - A real-time explorer for the XRP Ledger, available for mainnet, testnet, and devnet.
- [XRP Toolkit](https://www.xrptoolkit.com) - Toolkit for XRP Ledger interactions, offering a user-friendly interface for various operations.
- [Testnet Faucet](https://xrpl.org/xrp-testnet-faucet.html) - Get testnet XRP to start experimenting with the XRP Ledger risk-free.

## Core Concepts

Explanation of fundamental concepts in the XRP Ledger ecosystem:

- [Consensus on XRP Ledger](https://xrpl.org/consensus.html) - An overview of the unique consensus mechanism used by the XRP Ledger.

## Development Tools

Key tools and environments for XRP Ledger:

- [xrpl.js](https://github.com/XRPLF/xrpl.js) - The official JavaScript/TypeScript library for interacting with the XRP Ledger.
- [xrpl4j](https://github.com/XRPLF/xrpl4j) - A pure Java implementation for interacting with the XRP Ledger.

## Smart Contracts

How to write and deploy smart contracts on XRP Ledger (not possible atm, so these are alternatives):

- [Hooks](https://xrpl.org/hooks-amendment.html) - An upcoming feature that will allow for smart contract functionality on the XRP Ledger.
- [EVM Sidechain](https://docs.xrplevm.org/docs/evm-sidechain/intro-to-evm-sidechain/) - The XRP Ledger's EVM sidechain

## XRP Ledger Network

Going into the network level:

- [XRP Ledger Live](https://livenet.xrpl.org) - A real-time view of the XRP Ledger network, including transactions and validator information.
- [Bithomp](https://bithomp.com) - A user-friendly XRP Ledger explorer with enhanced account viewing features.

## Ecosystem Projects

Cool projects built on XRP Ledger:

- [XUMM](https://xumm.app) - A non-custodial wallet for XRP Ledger with advanced features and xApp support.
- [Sologenic](https://www.sologenic.com) - A sophisticated trading platform built on the XRP Ledger.
- [Gatehub](https://gatehub.net) - A gateway for various digital assets on the XRP Ledger.

...and of course many more - check them out in the EasyA app!

## Resources

Extra stuff:

- [XRP Ledger Dev Blog](https://dev.to/ripplexdev) - Official development blog with insights and updates on XRP Ledger development.
- [XRPL Foundation GitHub](https://github.com/XRPLF/) - The hub for XRP Ledger Foundation's open-source projects and libraries.

## Handy Code Snippets

Get a taste of XRP Ledger development with these code snippets:

### Connecting to XRP Ledger

```javascript
const { Client } = require('xrpl');

async function main() {
  const client = new Client('wss://s1.ripple.com');
  await client.connect();
  
  console.log('Connected to XRP Ledger');
  
  client.disconnect();
}

main();
```

### Creating a new account

```javascript
const { Wallet } = require('xrpl');

const wallet = Wallet.generate();
console.log('New account address:', wallet.address);
console.log('New account seed:', wallet.seed);
```

These examples showcase:
1. How to connect to the XRP Ledger network.
2. How to create a new XRP Ledger account.

## Contributing

We welcome contributions to make this handbook even more legendary! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-addition`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-addition`)
6. Create a new Pull Request

Please ensure your contributions align with our code of conduct and contribution guidelines.

## Credit/Inspiration

This handbook was inspired by the famous awesome lists by sindresorhus and the Awesome XRPL list. We need awesome lists for Web3 ecosystems, with more of a hacker's guide to how they work. This is the answer to that need.
