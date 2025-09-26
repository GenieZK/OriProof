<div align="center">
  <h1>OriProof Protocol</h1>
  <p><strong>Immutable Proof of Origin for the Creator Economy.</strong></p>
</div>

<p align="center">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/GenieZK/OriProof?style=for-the-badge&logo=github&color=58a6ff">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/GenieZK/OriProof?style=for-the-badge&logo=github&color=58a6ff">
  <img alt="Contributions Welcome" src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge&logo=handshake">
  <img alt="License" src="https://img.shields.io/github/license/GenieZK/OriProof?style=for-the-badge&color=58a6ff">
</p>

---

## 📌 Abstract

OriProof is a decentralized, trust-minimized protocol designed to fundamentally solve the problem of digital content attribution and unauthorized redistribution. By leveraging a powerful combination of on-chain cryptographic proofs and off-chain AI-driven content analysis, OriProof creates a persistent, verifiable link between a creator and their original work.

The protocol establishes an **immutable "Proof of Origin"** on the **Midnight** blockchain and automates the detection, tracking, and monetization of content across the public web, ensuring creators are fairly compensated for their intellectual property.

## 🎯 The Core Problem

The current digital content landscape is fundamentally broken for creators. The ease of duplication and distribution has led to a systemic problem where:
1.  **Proof of Authorship is Fragile:** Proving you were the first to create a piece of viral content is a complex, often impossible legal battle.
2.  **Value is Siphoned:** Unauthorized re-uploads on platforms like YouTube, TikTok, and Instagram divert billions of views—and the associated ad revenue—away from the original creators.
3.  **Monetization is Centralized & Opaque:** Creators are subject to the arbitrary rules, high commission fees, and opaque payment processes of centralized platforms.
4.  **Privacy is an Afterthought:** Licensing deals, revenue streams, and even the creator's identity are often exposed publicly or held by centralized entities, creating security risks.

## 💡 The OriProof Solution: A Hybrid Architecture

OriProof addresses this through a robust, two-part architecture: an on-chain registry for immutable proof and an off-chain infrastructure for real-world detection.

### 1. On-Chain Registry: The "Proof" Layer (Midnight)
This is the protocol's source of truth. All core ownership data is registered on the Midnight blockchain.
*   **Content Fingerprinting:** Upon submission, content is processed to generate a set of robust perceptual hashes (pHash) and audio fingerprints.
*   **Immutable Timestamping:** A hash of the original content and its unique digital fingerprint are permanently recorded in a transaction on Midnight, creating an indisputable proof of existence.
*   **Ownership via NFTs:** The Proof of Origin is tokenized as an NFT, serving as a digital certificate of authenticity and a programmable title of ownership.
*   **ZK-Powered Smart Contracts:** Licensing and royalty rules are defined in a smart contract. Midnight's ZK capabilities ensure that these transactions can remain **private**, protecting sensitive business logic and financial data.

### 2. Off-Chain Engine: The "Detection" Layer
This layer acts as the protocol's eyes and ears on the public internet.
*   **AI-Powered Matching:** A network of crawlers scans major content platforms. Each piece of discovered content is fingerprinted and compared against the on-chain database of registered works.
*   **Event Reporting:** When a match is found, the system logs the event, including the URL of the re-upload and performance metrics (views, likes).

### 3. The Oracle Bridge
To bridge the off-chain and on-chain worlds, OriProof utilizes a decentralized oracle network to securely relay verified data (e.g., view counts) to the appropriate smart contract, triggering automated royalty distributions.

## ✨ Core Features
- **Immutable Proof of Ownership:** Generate a permanent, timestamped record of your creation on the blockchain.
- **Automated Re-upload Detection:** Our AI engine actively scans the web to find unauthorized copies of your work.
- **Private & Automated Royalty Distribution:** Receive your earnings instantly and privately through ZK-powered smart contracts.
- **Decentralized Licensing:** Create flexible, on-chain licensing agreements for your content without intermediaries.

## 🛠️ Tech Stack
- **Blockchain:** Midnight (for ZK-privacy), Cardano
- **Cryptography:** ZK-SNARKs, Perceptual Hashing, Audio Fingerprinting
- **Off-Chain:** Rust / Python (for crawlers & AI engine)
- **Decentralized Storage:** IPFS / Arweave

## 🚀 Project Status

**[ CONCEPTUAL / PRE-ALPHA ]**

The core architecture and protocol design are being finalized. We are actively researching and prototyping the off-chain content fingerprinting and matching engine. Smart contract development on the Midnight DevNet will commence shortly.

## 🤝 How to Contribute

We are looking for passionate developers and cryptographers to join our mission! If you have experience in decentralized systems, AI/ML for media analysis, or ZK cryptography, please feel free to:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

Please check the `Issues` tab for areas where you can contribute.

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
