# Quorix Architecture

High-level overview:

- **Frontend/UI**: React / [your choice] – simplistic chat + call UI
- **P2P Layer**: libp2p / [Matrix-inspired / custom] for discovery & transport
- **E2EE**: Double-ratchet (libs: olm/megolm or libsodium)
- **Voice/Video**: WebRTC (peer-to-peer, with signaling via protocol)
- **Instant Finality**: Yellow Network integration (state channels / offchain → onchain settlement for message proofs / micro-payments)
- **Identity**: Wallet-based (Ethereum / compatible)
