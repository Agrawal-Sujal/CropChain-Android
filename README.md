# CropChain-Android

CropChain-Android is a blockchain-enabled Android app for farmers to upload crop images, get AI and scientist reviews. Images are stored securely on IPFS (Pinata), and all verification and reviews happen via smart contracts on the blockchain.

---
## Demo

Watch the demo video: [CropChain-Android Demo](https://youtu.be/Fdxx4Vq2s8s?si=a4IqJJCTEaYOpStj)

---

## How It Works

### 1. Farmer Crop Upload

- **Image Upload:** Farmers use the app to capture and upload crop images.
- **IPFS Storage:** Images are uploaded to Pinata (IPFS) for decentralized storage.
- **Blockchain Transaction:** Details of the crop and image URLs are recorded on the blockchain for immutability and traceability.

### 2. Review Process

- **AI Review:** Each uploaded crop image first receives an automated review from an AI model.
- **Scientist Review:** After the AI review, a registered scientist reviews the crop.
- **Peer Verification:** The scientist's review is further verified by 5 other scientists.
- **Majority Decision:** If the majority (at least 3 out of 5) verifiers agree with the scientist's review, the result is finalized.
- **Farmer Notification:** The farmer receives the collective review decision and feedback within the app.

### 3. Trust & Transparency

- **All reviews and verifications are recorded as blockchain transactions.**
- **Scientist and verifier reputation is tracked and updated based on their review accuracy.**

---

## Features

- **Farmer Portal:** Register, upload crop images, track review status.
- **Scientist Portal:** Review crops, verify peer reviews, build reputation.
- **AI Integration:** Automated crop analysis for fast initial feedback.
- **Blockchain Backend:** All critical actions and transactions are securely logged on-chain.
- **IPFS Integration:** Decentralized image storage via Pinata.
- **Activity History:** View all uploads, reviews, and transactions.

---



## Tech Stack

- **Android (Kotlin)**
- **Solidity Smart Contracts (Ethereum/EVM)**
- **Pinata (IPFS) for Decentralized Storage**
- **Web3 Libraries for Blockchain Connectivity**

---

## Getting Started

### Prerequisites

- Android Studio (latest)
- MetaMask app (for blockchain/transaction signing)
- Pinata account (for IPFS uploads)

### Installation

```bash
git clone https://github.com/sujalagrawal2/CropChain-Android.git
```
- Open the project in Android Studio.
- Configure your API keys for Pinata and blockchain endpoints.
- Build and run the app on your device.

---

