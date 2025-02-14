# Gradium Network - Developer Documentation

Welcome to the official internal documentation repository for the [**Gradium Network**](#project-overview) project.
This repository serves as the central hub for all technical documentation, guides, and
resources needed by developers to understand, build, and contribute to the project.

---

## **Project Overview**

The **Gradium Network** is a next-generation blockchain platform designed to address the emerging threats posed by
quantum computing. Traditional blockchains rely on cryptographic algorithms (e.g., ECDSA, RSA) that are vulnerable to
quantum attacks, such as **Shor's Algorithm** (which breaks public-key cryptography) and
**Grover's Algorithm** (which weakens symmetric-key cryptography). This project integrates
**post-quantum cryptographic (PQC) algorithms** to ensure long-term security and resilience against quantum computing
threats.

## **Key Features**

1. **Gradium Network Consensus**: CRYSTALS-Dilithium ensures secure block validation in a PoS model.
2. **Secure Transactions**: FALCON enables compact, quantum-resistant transaction signatures.
3. **Quantum-Safe Networking**: Kyber secures node communication via post-quantum key exchange.
4. **Tamper-Proof Storage**: SPHINCS+ and KangarooTwelve protect Merkle tree integrity.
5. **Light Client Support**: VDFs allow lightweight, quantum-safe state verification.
6. **Governance & Voting**: Rainbow signatures secure stakeholder decision-making.
7. **Fair Randomness Generation**: SHA-3 powers tamper-proof entropy for critical processes.
8. **Pure Proof-of-Stake**: Energy-efficient consensus with staked validators.
9. **Deflationary Tokenomics**: Transaction fee burning reduces token supply over time.
10. **Quantum Attack Mitigations**: SHA-3 and AES-256 counter Shor’s and Grover’s threats.

---

## **Network Information**

| Parameter              | Value                            |
|------------------------|----------------------------------|
| **Network Name**       | Gradium Network                  |
| **RPC URL**            | GrQ20 RPC                        |
| **Chain ID**           | GrQ20                            |
| **Symbol**             | GRD                              |
| **Block Explorer URL** | [GRQScan.io](https://GRQScan.io) |
| **Website**            | [Gradium.io](https://Gradium.io) |

---

## **Gradium Tokenomics**

### **Native Deflationary Coin: GRD**

The native currency of the Gradium Network, **GRD**, is designed with a **deflationary model**, ensuring long-term
sustainability. Key aspects:

- **Consensus Participation**: Validators and delegators stake GRD to secure the network and earn rewards.
- **Transaction Fees & Burning**: A portion of each transaction fee is **burned**, gradually reducing the total supply.
- **Ecosystem Utility**: GRD is used for governance, smart contract execution, and ecosystem services.
- **Inflation Control**: Unlike traditional models, Gradium ensures controlled emission through staking while
  maintaining a decreasing total supply.

### **Bridged BEP-20 Token: GRD**

Gradium Network also supports a **BEP-20 bridged version of GRD**, allowing interoperability with the Binance Smart
Chain (BSC).
This bridged token has a **fixed total supply of 52 million** and follows a structured burn mechanism:

- **Total Supply**: 52,000,000 GRD (fixed)
- **Burn Rate**: 3% per transaction
- **Use Cases**: Trading, DeFi applications, and cross-chain interoperability.
- **Bridge Mechanism**: Users can swap between the native and bridged versions of GRD via the official bridge.

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

Reach out to the team on [Slack/Teams] or contact the [Gradium Support team](mailto:info@gradium.io).
