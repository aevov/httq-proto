# HTTQ Protocol Specification (v1.0)

This project is licensed under the **Sovereign Commons** model.

PS: This overall license style ensures that we can protect and enable httq's potential for the future of integrated Quantum systems starting with the Quantum Web which is crucial to our collective evolution to the future of Web 5 starting with a native browser built specifically for that purpose: lucibrowser.com

- **Source Code**: [GNU General Public License v3.0 (GPL-3.0)](./LICENSE-CODE)
- **Protocol Specification**: [Polyform Non-Commercial License 1.0.0](./LICENSE-NC.md)

See [LICENSE](./LICENSE) for full details.

---

**Hyper-Text Transport Quantum** is the decentralized transport layer for the Nara Web 4.0 ecosystem.

## 1. Philosophy
HTTQ replaces the location-based addressing of TCP/IP/DNS with **Identity-Based Routing**.
- **Old Web**: "Where is this resource?" (IP Address)
- **New Web**: "Who signed this resource?" (Cryptographic Identity)

## 2. Addressing Scheme (`httq://`)
An HTTQ address is a **Quantum Identity Key (QIK)** hash.

```
httq://[QIK_HASH]/[RESOURCE_PATH]
```

### 2.1 Resolution (QNS)
The **Quantum Name System (QNS)** maps human-readable `.q` domains to QIK hashes.
- `wakanda.q` -> `0x7f...3a` (Current Orbital Identity)

## 3. Cryptography (HTTQS)
**HTTQS** enforces end-to-end encryption using post-quantum algorithms.

### 3.1 Handshake
- **Algorithm**: `Kyber-1024` (Key Encapsulation)
- **Signature**: `Dilithium-5` (Identity Verification)

### 3.2 Transport
- **Traffic Obfuscation**: All packets are padded to fixed sizes to prevent traffic analysis.
- **Onion Routing**: Traffic is routed through **Tansu Relays** to hide origin/destination.

## 4. Implementation
This repository serves as the canonical spec. Reference implementations will be provided in Rust.

---
© 2026 WPWakanda LLC / Aevov AI Technologies.
