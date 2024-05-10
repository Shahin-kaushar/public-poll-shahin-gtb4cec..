# Decentralized Public Opinion Poll Smart Contract

This project implements a decentralized public opinion polling system on the Stellar network using the Soroban SDK. Polls are created and managed by smart contracts, ensuring transparency, tamper-proof results, and automatic tallying.

## Key Features

* **Poll Creation:** Users can create new polls with a question and multiple options.
* **Secure Voting:**  The smart contract includes placeholder logic for blockchain-based identity verification to prevent duplicate and fraudulent voting.
* **Openness:** Polls can be closed by their creators to prevent further voting.
* **Transparency:**  Poll results are stored on the blockchain, ensuring an auditable and immutable record.

## Prerequisites

* A Stellar Testnet account with some test XLM tokens.
* Basic familiarity with Rust and the Stellar network.
* Soroban SDK installed ([https://soroban.stellar.org/install.sh](https://soroban.stellar.org/install.sh))

## Project Setup

1. Clone this repository.
2. Install dependencies:
   ```bash
   cargo install --locked
soroban build --target wasm32-unknown-unknown

