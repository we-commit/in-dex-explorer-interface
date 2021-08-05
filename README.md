#REPLACED BY MONOREPO & FULL CLIENT PROJECT

# Trojan Finance

An open source interface for Trojan Finance, based in Uniswap Interface. https://github.com/Uniswap/uniswap-interface

## What Trojan Finance can do for you?

The Trojan Finance platform gives the user the opportunity to take trading decisions based on future transactions.
It monitors the mempool (pending transactions) and displays the most possible future result of each trade, based on Uniswap SDK.

- **App**: [app.trojan.finance](https://app.trojan.finance)
- Website: [trojan.finance](https://trojan.finance)
- Twitter: [@trojanfinance](https://twitter.com/trojanfinance)
- Discord: [TrojanFinance](https://discord.gg/VZkFP78aeF)
- Medium: [@trojanfinance](https://medium.com/@trojanfinance)

# Accessing the Trojan Interface.

To access the Trojan Interface visit [app.trojan.finance](https://app.trojan.finance).

Trojan Finance Interface is based on Uniswap Interface, we had removed features that we dont use for now, like Pools, Votes, Staking.

We added a server connection to expose mempool transactions via web socket for live and fast updates. **This feature do not mess with any wallet integration** its a one way web socket and we dont send to our server any information about users.

We have opened this repository so **users can check this and trust that we follow the same way Uniswap works with wallets.** We will be updating any updates from Uniswap repository as soon as we can.

**Anyway use at your own risk. This is a beta version** and we are still improving our mempool scanner, decoder, compute and predictions.

# Development

Check the code by yourself. Download or clone this repository.

```bash
git clone https://github.com/we-commit/trojan-finance-interface.git
```

## Install Dependencies

```bash
yarn
```

## Run

```bash

yarn compile-contract-types

yarn dev

```

# Community

We are stronger together. Jump in [Discord](https://discord.gg/VZkFP78aeF) and stay tuned.
