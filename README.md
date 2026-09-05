# Mahdi Darabi

I build protocol and cryptographic infrastructure: bridges, wallets, and the
cryptography underneath them.

Founding engineer on **TeleSwap**, a Bitcoin↔EVM bridge that processed **$350M+**
in cross-chain volume with zero critical incidents. I designed the trust model
(validator collateral and slashing, a Bitcoin light client on EVM, Bitcoin-to-EVM
messaging) and wrote the upgradeable Solidity contracts behind it.

After that I owned wallet infrastructure at a major exchange, **securing $150M+
across 20+ chains**. The production signing system has run for over a year with
minimal intervention. Alongside it I built a **threshold signature (TSS/MPC)
custody system** in Go, with a fully distributed key recovery module on
cryptographic secret sharing and BIP44, validated end to end in staging.

Most recently I shipped a **Zcash-style shielded pool** live on Sepolia.

## Selected work

**[ctf-buidl-guidl](https://github.com/mahdiidarabi/ctf-buidl-guidl)** Solidity
CTF write-ups and exploit walkthroughs, with the reasoning behind each one.

**[zcash-pour-contracts](https://github.com/mahdiidarabi/zcash-pour-contracts)**
Zcash-style shielded pool, live on Sepolia. circom circuit (4,612 constraints),
generated Solidity verifier, subgraph, and a browser client that generates real
Groth16 proofs in-tab. The [protocol doc](https://github.com/mahdiidarabi/zcash-pour-contracts/blob/main/docs/protocol.md)
lists every way it is weaker than real Zcash, including the problems I have not fixed.
[Live demo](https://zcash-pour-contracts.vercel.app/)

**[DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs)** contributed a
proof-of-concept reproduction to the open-source DeFi exploit archive.

**[ecdsa-affine](https://github.com/mahdiidarabi/ecdsa-affine)** reproduction of
the Upbit 2025 hack, showing how nonce and affine relationships enable key recovery.

## Writing

A four-part zkSNARK series built from first principles: mental models through
R1CS/QAP/pairings to Groth16, with a TornadoCash reimplementation. Plus pieces on
BLS aggregation, cross-chain messaging, and Bitcoin L2 architecture.
→ [mahdidarabi.medium.com](https://mahdidarabi.medium.com)

## Working with

Go · TypeScript · Solidity · Hardhat · Foundry · circom · Python

Open to protocol, wallet infrastructure, and applied cryptography roles.
Remote, contractor or full-time. Istanbul.

[LinkedIn](https://linkedin.com/in/mahdi-darabi) · [X](https://x.com/MadDiDrb) · mahdi.darabi.official@gmail.com
