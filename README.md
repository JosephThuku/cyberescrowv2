# cyber Escrow

## Overview

CyberEscrow System is a decentralized application acting as a DEFI and a DAO simultaneously, hosted on the Internet Computer. The escrow system facilitates seamless trades, protecting users from scams while earning escrow coins. Here's how it works:

The seller sends coins to the escrow node.
The escrow node holds the coins and lists them for sale.
The buyer views the listed ads and selects the desired one.
The buyer initiates the transaction, and the node provides a wallet for payment.
Upon payment confirmation, the node releases coins to the buyer and payments to the seller.

- [Quick Start](https://internetcomputer.org/docs/current/developer-docs/setup/deploy-locally)
- [SDK Developer Tools](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- [Motoko Programming Language Guide](https://internetcomputer.org/docs/current/motoko/main/motoko)
- [Motoko Language Quick Reference](https://internetcomputer.org/docs/current/motoko/main/language-manual)

If you want to start working on your project right away, you might want to try the following commands:

```bash
cd cyberescro/
dfx help
dfx canister --help
```

## Running the project locally

If you want to test Cyberescrow project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```



Which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 4943.

### Note the frontend
The frontend of this canister is hosted on  a diffrent repo and we will share upon publish
