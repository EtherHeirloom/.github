# Ether-Heirloom

**Non-custodial inheritance for ERC-20 tokens on Ethereum.** Choose your heirs, their shares and a date. Your tokens stay in your own wallet; after the date, each heir's share moves straight to that heir. No custody, no shared keys, no check-ins.

🌐 [ether-heirloom.github.io](https://ether-heirloom.github.io) · 📄 [Whitepaper](https://ether-heirloom.github.io/Heirloom_Whitepaper_Version_1.0.pdf) · 🔐 [Security policy](https://github.com/EtherHeirloom/EtherHeirloom.sol/blob/main/SECURITY.md)

## The problem

With self-custody, nobody can recover your keys: not a bank, a court or a support team. The usual workarounds mean sharing a seed phrase with family or handing a key to a company.

## How it works

1. **Set up a plan.** Name up to 10 heirs with exact shares and pick a date.
2. **Approve the tokens to include.** The contract gets an ERC-20 allowance; the tokens never leave your wallet. Native ETH is included by wrapping it into WETH.
3. **Stay in control.** Until the date you use your tokens as usual. Change heirs, move the date or revoke a token's approval at any time.
4. **After the date,** anyone can trigger delivery, and each heir's share goes only to that heir. Tokens that reach your wallet after setup are covered too, and heirs can chain their own plans.

It also runs as a **Safe App**, so a multisig or a company treasury can own the plan: open Safe → Apps → My custom apps → `https://ether-heirloom.github.io/`.

## Contracts

| Network | Address |
|---|---|
| Ethereum mainnet | [`0x0E0A916f469200318c9c6442038D45857ff41AE0`](https://etherscan.io/address/0x0e0a916f469200318c9c6442038d45857ff41ae0#code) (verified source) |
| Sepolia testnet | [`0x2Db72e99E83005cA87CCd93F6FC1aa0C97a7Eb83`](https://sepolia.etherscan.io/address/0x2Db72e99E83005cA87CCd93F6FC1aa0C97a7Eb83) |

- No owner or admin functions, no pause, no upgrade proxy. Fees are fixed in the contract.
- Open source: [EtherHeirloom.sol](https://github.com/EtherHeirloom/EtherHeirloom.sol), with the Foundry test suite run on every change.
- Not yet independently audited. Please review the code before relying on it, and report issues privately as described in the [security policy](https://github.com/EtherHeirloom/EtherHeirloom.sol/blob/main/SECURITY.md).

## Contact

Partnerships and questions: **Ether-Heirloom@proton.me** · [X](https://x.com/EtherHeirloom) · [LinkedIn](https://www.linkedin.com/company/ether-heirloom)
