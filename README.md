# [Quantova Network](http://Quantova.org/) - Developer Documentation

Welcome to the official internal documentation repository for the [**Quantova Network**](#project-overview) project.
This repository serves as the central hub for all technical documentation, guides, and
resources needed by developers to understand, build, and contribute to the project.

---

## **Project Overview**

The [**Quantova Network**](http://Quantova.org/) is a next-generation blockchain platform designed to address the emerging threats posed by
quantum computing. Traditional blockchains rely on cryptographic algorithms (e.g., ECDSA, RSA) that are vulnerable to
quantum attacks, such as **Shor's Algorithm** (which breaks public-key cryptography) and
**Grover's Algorithm** (which weakens symmetric-key cryptography). This project integrates
**post-quantum cryptographic (PQC) algorithms** to ensure long-term security and resilience against quantum computing
threats.

## **Key Features**

1. [**Quantova Network Consensus**](https://github.com/Quantova/Quantova-network-docs/blob/main/2.0%20Core%20Blockchain%20Features/2.1%20consensus-mechanism.md): CRYSTALS-Dilithium ensures secure block validation in a PoS model.
2. [**Secure Transactions**](https://github.com/Quantova/Quantova-network-docs/blob/main/2.0%20Core%20Blockchain%20Features/2.2%20transaction-layer.md): FALCON enables compact, quantum-resistant transaction signatures.
3. [**Quantum-Safe Networking**](https://github.com/Quantova/Quantova-network-docs/blob/main/3.0%20Security%20Layers/3.2%20networking-layer.md): Kyber secures node communication via post-quantum key exchange.
4. [**Tamper-Proof Storage**](https://github.com/Quantova/Quantova-network-docs/blob/main/3.0%20Security%20Layers/3.3%20storage-and-state-management.md): SPHINCS+ and KangarooTwelve protect Merkle tree integrity.
5. [**Light Client Support**](https://github.com/Quantova/Quantova-network-docs/blob/main/4.0%20Supporting%20Features/4.1%20light-client-support.md): VDFs allow lightweight, quantum-safe state verification.
6. [**Governance & Economics**](https://github.com/Quantova/Quantova-network-docs/blob/main/5.0%20Governance%20and%20Economics/5.1%20governance.md): Rainbow signatures secure stakeholder decision-making.
7. [**Fair Randomness Generation**](https://github.com/Quantova/Quantova-network-docs/blob/main/4.0%20Supporting%20Features/4.2%20randomness-generation.md): SHA-3 powers tamper-proof entropy for critical processes.
8. [**Pure Proof-of-Stake**](https://github.com/Quantova/Quantova-network-docs/blob/main/5.0%20Governance%20and%20Economics/5.2%20pure-proof-of-stake.md): Energy-efficient consensus with staked validators.
9. **Quantum Attack Mitigations**: SHA-3 and AES-256 counter Shor’s and Grover’s threats.

---

## **Network Information**

| Parameter              | Value                            |
|------------------------|----------------------------------|
| **Network Name**       | Quantova Network                  |
| **RPC URL**            | https://rpc.quantova.org                        |
| **Chain ID**           | QTOV20                            |
| **Symbol**             | QTOV                              |
| **Block Explorer URL** | [QtovaScan.io](https://QtovaScan.io) |
| **Website**            | [Quantova.org](https://Quantova.org) |

---

## **Quantova Tokenomics**

### **Native Deflationary Coin: QTOV**

The native currency of the Quantova Network, **QTOV**, is designed with a **deflationary model**, ensuring long-term
sustainability. Key aspects:

- **Consensus Participation**: Validators and delegators stake QTOV to secure the network and earn rewards.
- **Transaction Fees & Burning**: A portion of each transaction fee is **burned**, gradually reducing the total supply.
- **Ecosystem Utility**: QTOV is used for governance, smart contract execution, and ecosystem services.
- **Inflation Control**: Unlike traditional models, Quantova ensures controlled emission through staking while
  maintaining a decreasing total supply.

### **Bridged BEP-20 Token: QTOV**

Quantova Network also supports a **BEP-20 bridged version of QTOV**, allowing interoperability with the Binance Smart
Chain (BSC).
This bridged token has a **fixed total supply of 52 million** and follows a structured burn mechanism:

- **Total Supply**: 52,000,000 QTOV (fixed)
- **Use Cases**: Trading, DeFi applications, and cross-chain interoperability.
- **Bridge Mechanism**: Users can swap between the native and bridged versions of QTOV via the official bridge.

---

## **Getting Started**

This section will guide you through setting up your development environment, building the project, and contributing to
the codebase.

### **Quick Start**

1. **Set Up Your Environment**: Follow the [development setup guide](/6.0%20Development/setup.md).
2. **Build the Project**: Learn how to build and run the blockchain in the [building guide](/6.0%20Development/building.md).
3. **Explore the Architecture**: Dive into the technical design in
   the [architecture section](/3.0%20Security%20Layers/).

### **Key Sections**

- [Development Guides](/6.0%20Development/): Setup, building, testing, and debugging.
- [API Reference](/api-reference/): RPC endpoints and runtime modules.
- [Security](/security/): Attack models, mitigations, and audit reports.

---

## **Contributing**

Please read the [CONTRIBUTING.md](/CONTRIBUTING.md) for guidelines on how to contribute to the codebase and
documentation.

## **Questions?**

Reach out to the team on [Slack/Teams] or contact the [Quantova Support team](mailto:info@Quantova.org).
