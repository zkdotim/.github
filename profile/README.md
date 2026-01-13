<div align="center">

# 🔐 zk.im

**Your Private Gateway to the Web3 Frontier**

[![Website](https://img.shields.io/badge/Website-zk.im-blue)](https://zk.im)
[![X (Twitter)](https://img.shields.io/badge/X-@zkdotim-black)](https://x.com/zkdotim)
[![Telegram](https://img.shields.io/badge/Telegram-@zkdotim-blue)](https://t.me/zkdotim)
[![Bluesky](https://img.shields.io/badge/Bluesky-@zk.im-blue)](https://bsky.app/profile/zk.im)
[![Substack](https://img.shields.io/badge/Substack-@zkdotim-orange)](https://substack.com/@zkdotim)
[![Email](https://img.shields.io/badge/Email-hi@zk.im-red)](mailto:hi@zk.im)

**Zero-Knowledge Messaging • Chain-Agnostic Seedless Wallets • Quantum-Resistant Security • No Central Dependencies**

</div>

---

## 🎯 Mission

We're working on a **zero-knowledge decentralized platform** where privacy is built-in from the ground up. Our goal is to contribute to an internet that's more open, trustless, and puts users in control of their own data.

We're exploring how the internet could be:
- 🔐 **Private by Default** - Zero-knowledge architecture means no server-side data access
- 🌐 **Decentralized** - Peer-to-peer communication without central servers
- 🛡️ **Quantum-Resistant** - Post-quantum cryptography for long-term security
- 💳 **User-Sovereign** - Wallet-based identity with full user control
- 🚫 **Censorship-Resistant** - Decentralized infrastructure that's harder to control

---

## 🏗️ What We Build

### Core Infrastructure

- **🔐 Zero-Knowledge Messaging** - End-to-end encrypted P2P communication
- **💼 Invisible Wallet** - Chain-agnostic zero-knowledge key management
- **📦 ZKIM File Format** - Three-layer encryption with privacy-preserving search
- **🌐 ZKIM P2P** - True peer-to-peer networking without central servers
- **🗄️ ZKIM CAS** - Content Addressable Storage with 95% deduplication
- **🔍 Searchable Encryption** - OPRF-based privacy-preserving search

### Key Technologies

- **Cryptography**: libsodium-wrappers-sumo, @noble/hashes, @noble/curves
- **Post-Quantum**: ML-KEM-768 (FIPS 203), ML-DSA-65 (FIPS 204)
- **Symmetric Encryption**: XChaCha20-Poly1305 (keys derived from ML-KEM-768)
- **Key Derivation**: Argon2id13 (password-based), BLAKE3 (hashing)
- **Networking**: WebRTC, Kademlia DHT, GossipSub
- **Storage**: ZKIM CAS, Arweave integration
- **Architecture**: Domain-Driven Design (DDD), TypeScript, Next.js

---

## 📦 Open Source Projects

### [@zkim-platform/file-format](https://github.com/zkdotim/zkim-file-format)

[![npm version](https://img.shields.io/npm/v/@zkim-platform/file-format)](https://www.npmjs.com/package/@zkim-platform/file-format)
[![npm downloads](https://img.shields.io/npm/dm/@zkim-platform/file-format)](https://www.npmjs.com/package/@zkim-platform/file-format)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://github.com/zkdotim/zkim-file-format/actions/workflows/ci.yml/badge.svg)](https://github.com/zkdotim/zkim-file-format/actions)
[![Test Coverage](https://img.shields.io/badge/coverage-92%25-brightgreen)](https://github.com/zkdotim/zkim-file-format)

Secure, encrypted file format with three-layer encryption, integrity validation, and privacy-preserving search capabilities.

**Features:**
- 🔐 Three-layer encryption (XChaCha20-Poly1305)
- 🔍 Privacy-preserving searchable encryption (OPRF-based)
- ✅ Integrity validation (BLAKE3 + ML-DSA-65)
- 📦 Optional compression (GZIP/Brotli)
- ⚡ Performance monitoring
- 🔒 Constant-time security

[📖 Documentation](https://github.com/zkdotim/zkim-file-format) • [📦 npm Package](https://www.npmjs.com/package/@zkim-platform/file-format)

---

### [@zkim-platform/post-quantum](https://github.com/zkdotim/zkim-post-quantum)

[![npm version](https://img.shields.io/npm/v/@zkim-platform/post-quantum)](https://www.npmjs.com/package/@zkim-platform/post-quantum)
[![npm downloads](https://img.shields.io/npm/dm/@zkim-platform/post-quantum)](https://www.npmjs.com/package/@zkim-platform/post-quantum)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://github.com/zkdotim/zkim-post-quantum/actions/workflows/ci.yml/badge.svg)](https://github.com/zkdotim/zkim-post-quantum/actions)
[![Test Coverage](https://img.shields.io/badge/coverage-77%25-brightgreen)](https://github.com/zkdotim/zkim-post-quantum)

Production-ready, developer-friendly wrapper for NIST-standardized post-quantum cryptography (ML-KEM-768, ML-DSA-65).

**Features:**
- 🔐 ML-KEM-768 (FIPS 203) - Key Encapsulation Mechanism
- ✍️ ML-DSA-65 (FIPS 204) - Digital Signature Algorithm
- 🛠️ Crypto-agility framework for future-proofing
- 🔑 Key management (serialization, fingerprinting, caching)
- ⚡ Error handling and validation
- 📦 Fully standalone, zero ZKIM dependencies

[📖 Documentation](https://github.com/zkdotim/zkim-post-quantum/wiki) • [📦 npm Package](https://www.npmjs.com/package/@zkim-platform/post-quantum)

---

## 🛠️ Technology Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?logo=typescript)
![Node.js](https://img.shields.io/badge/Node.js-20+-green?logo=node.js)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-blue?logo=react)

![libsodium](https://img.shields.io/badge/libsodium-SUMO-orange)
![BLAKE3](https://img.shields.io/badge/BLAKE3-Hash-green)
![WebRTC](https://img.shields.io/badge/WebRTC-P2P-blue)
![Arweave](https://img.shields.io/badge/Arweave-Storage-orange)

</div>

---

## 📊 Statistics

<div align="center">

![GitHub Repositories](https://img.shields.io/badge/Repositories-2-blue)
![Open Source](https://img.shields.io/badge/Open%20Source-MIT-green)
![Language](https://img.shields.io/badge/Language-TypeScript-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

</div>

---

## 🌟 What We've Built

- ✅ **Chain-agnostic wallet** - Support for multiple blockchain networks
- ✅ **Storage efficiency** - 95% deduplication through ZKIM CAS
- ✅ **Layered encryption** - Three-layer encryption architecture
- ✅ **Searchable encryption** - Privacy-preserving OPRF-based search
- ✅ **Post-quantum security** - ML-KEM-768 and ML-DSA-65 implementation
- ✅ **Decentralized architecture** - No central dependencies

---

## 📚 Resources

- **🌐 Website**: [zk.im](https://zk.im)
- **📖 Documentation**: [GitHub Repositories](https://github.com/zkdotim)
- **💬 Community**: [Telegram](https://t.me/zkdotim) • [X (Twitter)](https://x.com/zkdotim)
- **📧 Contact**: [hi@zk.im](mailto:hi@zk.im)

---

## 🤝 Contributing

We welcome contributions! Please see our repository-specific contributing guidelines:

- [zkim-file-format Contributing Guide](https://github.com/zkdotim/zkim-file-format/blob/main/CONTRIBUTING.md)
- [zkim-post-quantum Contributing Guide](https://github.com/zkdotim/zkim-post-quantum/blob/main/CONTRIBUTING.md)

---

## 📄 License

Our open-source projects are licensed under the **MIT License** - see individual repositories for details.

---

## 🔗 Connect With Us

<div align="center">

[![Website](https://img.shields.io/badge/Website-zk.im-blue)](https://zk.im)
[![X (Twitter)](https://img.shields.io/badge/X-@zkdotim-black)](https://x.com/zkdotim)
[![Telegram](https://img.shields.io/badge/Telegram-@zkdotim-blue)](https://t.me/zkdotim)
[![Bluesky](https://img.shields.io/badge/Bluesky-@zk.im-blue)](https://bsky.app/profile/zk.im)
[![Substack](https://img.shields.io/badge/Substack-@zkdotim-orange)](https://substack.com/@zkdotim)
[![Email](https://img.shields.io/badge/Email-hi@zk.im-red)](mailto:hi@zk.im)

</div>

---

<div align="center">

**Building the future of private, decentralized communication**

Made with ❤️ by the zk.im team

</div>

