# Ping-Pong dApp - MultiversX Blockchain

This project is a guide for creating a simple decentralized application (dApp) on the MultiversX Blockchain. In the Ping-Pong dApp, users send tokens (ping) and after a certain period, they can retrieve those tokens (pong). The project allows users to securely lock their tokens and retrieve them later.

## Project Overview

**Ping**: Users deposit 1 xEGLD into the smart contract.  
**Pong**: After the specified lock period (10 minutes), users can retrieve their tokens.
**Rules**: Each user can have only one active ping transaction at a time, and each deposit is fixed at 1 xEGLD.

## Requirements

To develop this project, you will need the following tools:

- **mxpy**: It helps you create wallets and deploy your smart contract. You can install it by following the. [mxpy installation guide](https://docs.multiversx.com/developers/tutorials/your-first-dapp) üzerinden kurabilirsiniz.
- **Rust**:Required for building the smart contract. Follow this [rehberi](https://docs.multiversx.com/developers/tutorials/your-first-dapp) for installation instructions for Rust and `sc-meta`.

