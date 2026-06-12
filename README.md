# Cipher (QVYRA)
### A sovereign proof of work currency for the AI agent economy

---

## What is Cipher?

Cipher is a proposed open source proof of work blockchain 
designed as a native currency for AI agent to agent transactions.

It has no issuer, no treasury, no foundation, no governance 
token, no pre-mine, and no founder allocation. Issuance occurs 
solely through mining under rules every node can verify for itself.

It is not competing with x402, stablecoins, Stripe, or 
institutional agent payment systems on convenience or liquidity. 
Its differentiation is a substantially higher degree of monetary 
and operational sovereignty for participants who value censorship 
resistance, privacy, and non-custodial settlement.

It is not a replacement for Bitcoin. It completes it.

---

## Current Status

Pre-protocol. This means:

- No functioning blockchain
- No public testnet  
- No production codebase
- No established development team
- No active users

Present value is option value only. That option becomes real 
when the threat model is written, a working prototype is 
demonstrated, and the first engineer commits to building it.

---

## The Four Founding Principles

**1. Proof of work only**
New QVYRA enters circulation exclusively through mining.
No pre-mine. No founder allocation. No utility-based issuance.
Fair launch — founders mine under identical rules to everyone else.

**2. Fixed supply**
Total supply is fixed. When it is reached the mint closes forever.
The supply curve will be designed for Cipher's specific 
requirements as an AI agent currency.

**3. Privacy as baseline**
Not Monero-style opacity. Dignity. Your transactions are yours.
Interactive wallet design makes custodial holding technically 
difficult and economically unattractive. Non-custodial use 
is the path of least resistance by design.

**4. Minimised discretionary governance**
No foundation. No treasury. No governance token.
Protocol evolution through open source implementations, 
node adoption, and proof of work chain selection.
Monetary issuance belongs to the protocol and nobody else.

---

## Why a new blockchain?

Every existing agent payment standard has a chokepoint.

x402 routes through Coinbase and settles in USDC — 
which Circle can freeze. ERC-8004 depends on Ethereum's 
governance structure. AP2 is backed by Mastercard and PayPal. 
Stripe MPP is a corporate product.

Cipher has none of these. The structural inconvenience of 
building a new proof of work blockchain is the security moat. 
Easy solutions have easy chokepoints.

---

## What exists right now

- Whitepaper v7 (Cipher_Whitepaper_v7.pdf)
- Falsification Document v1 (Cipher_Falsification_Document.pdf)

The falsification document stress tests every claim in the 
whitepaper. Read it alongside the whitepaper. A project that 
cannot survive its own falsification document should not be built.

---

## Open Engineering Problems

Two problems require original solutions before the protocol 
can be built:

**1. Exchange resistance by structural design**
How to make custodial holding technically difficult without 
a central address blacklist — which would itself be a 
chokepoint. Interactive transaction frameworks are the 
current best direction. The problem is not fully solved.

**2. Fair launch bootstrap security**
A new proof of work network starts with very little 
accumulated work and is vulnerable to majority hash attacks 
during bootstrapping. The mining algorithm, difficulty 
adjustment, and launch parameters need careful design 
to minimise this window.

If you are a systems engineer who understands why this 
needs to exist — this is an open invitation.

Skills needed:
- Rust or Go
- Distributed consensus
- Applied cryptography  
- Cross-chain atomic swaps
- Privacy protocols (Mimblewimble, ZK proofs, or similar)

---

## What Cipher is not

Not a store of value competing with Bitcoin.
Not a stablecoin.
Not a governance token.
Not an exchange-listed asset.
Not a pre-mined founder enrichment vehicle.
Not finished.

---

## Contact

Open an issue on this repository.

---

*Cipher belongs to nobody.*
*Therefore nobody should have to trust you.*
*Build it so they don't have to.*

*— Cipher (QVYRA), June 2026*
