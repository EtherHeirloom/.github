# 🏛️ EtherHeirloom Protocol
**The Immutable Standard for Non-Custodial Digital Asset Succession.**

EtherHeirloom is a decentralised, trustless protocol designed to solve the "dead wallet" problem. By leveraging the ERC-20 `allowance` mechanism, it allows asset owners to secure their digital legacy without ever surrendering custody of their private keys.



---

## 🔍 The Problem
Approximately **20% of all circulating BTC and ETH** is estimated to be lost forever due to lost access or the death of owners. Traditional inheritance methods (notaries, shared seed phrases) are either incompatible with blockchain or introduce significant security risks.

## 🛠️ Our Solution: "Succession via Proxy"
EtherHeirloom decouples **ownership** from **succession intent**. 
* **Non-Custodial:** Assets stay in your wallet. You grant the protocol permission to transfer them only if you stop being active.
* **Contract is Law:** Fees and logic are hardcoded into the immutable smart contract. No governance, no backdoors.
* **Virtual Pool Accounting:** A unique mathematical model that ensures fair share distribution even as your wallet balance fluctuates.

---

## 🏗️ Technical Pillars
- **Heartbeat Mechanism:** A unified "Dead Man's Switch" verified by the `resetDeadline` function.
- **ERC-20 Focused:** Native support for the world's most liquid assets (USDC, USDT, WETH, LINK).
- **Security First:** Built with OpenZeppelin standards, featuring ReentrancyGuard and SafeERC20.
- **Gas Optimized:** Built-in pagination and batch claiming to handle complex legacy plans.

---

## 📄 Documentation & Resources
- **[Whitepaper](https://ether-heirloom.github.io//Heirloom_Whitepaper_Version_1.0.pdf):** Read our deep-dive into the protocol logic.
- **[Official Website](https://ether-heirloom.github.io/):** Set up your legacy plan in less than 2 minutes.
- **[Audit Reports](#):** (Coming Soon) Transparency is our core value.

---

## 🤝 For Developers & Researchers
We believe in the "Truth" of the code. We welcome peer reviews, security research, and contributions to the ecosystem.

* **Language:** Solidity 0.8.24
* **License:** BUSL-1.1 (Business Source License)
* **Chain Compatibility:** Ethereum Mainnet, Gnosis Chain, Polygon, and EVM L2s.

> *"In code we trust, but in logic we verify."*

---
© 2025 EtherHeirloom Team. All fees are hardcoded. The protocol is autonomous.
