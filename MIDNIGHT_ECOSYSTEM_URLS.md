# Midnight Ecosystem URLs — Curated for The Seven-Layer Magic Trick

**Curated by**: John Santi (Midnight NightForce Bravo | Midnight Academy Triple Certified | Midnight Ambassador)  
**Date**: March 28, 2026  
**Purpose**: Supplemental URL collection for readers of Charles Hoskinson's book. Organized by the seven-layer model and by topic. Offered to Charles for potential inclusion as an appendix, web companion, or bibliography supplement.

**Note to Charles**: Your Chapter 12 bibliography (refs 39-41) currently links only to `docs.midnight.network`. The URLs below fill out the ecosystem for readers who want to go deeper after reading the book. All URLs verified March 2026. Licensed same as the book (CC BY 4.0) — use freely.

---

## Official Midnight Network

### Primary Sites
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://midnight.network | Main Midnight Network website | Ch. 12 — overview |
| https://docs.midnight.network | Complete developer documentation (191pp Developer Guide referenced in Ch. 12) | Ch. 12 — all layers |
| https://midnight.network/developer-hub | Central developer hub — getting started, resources, community | Ch. 12 — developer experience |
| https://midnight.network/whitepaper | Technical whitepapers and protocol documentation | Ch. 12 — architecture |
| https://midnight.foundation | Midnight Foundation — governance and ecosystem development | Ch. 12 — Layer 7 governance |

### Documentation Deep Links (Mapped to Book Chapters)

**Layer 2 — Compact Language (Ch. 3, Ch. 12)**
| URL | Description |
|-----|-------------|
| https://docs.midnight.network/develop/reference/compact/ | Compact Language Reference (75pp referenced in Ch. 12) |
| https://docs.midnight.network/develop/reference/compact/lang-ref | Complete language specification — formal syntax, type rules, constraint system |
| https://docs.midnight.network/develop/tutorial/ | Step-by-step developer tutorial — first contract to deployment |
| https://docs.midnight.network/develop/tutorial/high-level-arch | High-level architecture — compiler output, component interaction, privacy layer |

**Layer 3 — Witnesses & Smart Contracts (Ch. 4, Ch. 12)**
| URL | Description |
|-----|-------------|
| https://docs.midnight.network/develop/how-midnight-works/smart-contracts | How Midnight contracts work — privacy-preserving computation, state management |

**Layer 7 — Deployment & Verification (Ch. 8, Ch. 12)**
| URL | Description |
|-----|-------------|
| https://midnight.network/blog/exploring-the-midnight-devnet | Devnet overview — getting started, tDUST tokens, developer accessibility |

---

## GitHub Repositories

### Official Midnight Organization
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://github.com/midnightntwrk | Official Midnight Network GitHub — 23+ repositories | Ch. 12 — all layers |
| https://github.com/midnightntwrk/compact | Compact compiler source — the `compactc` referenced throughout Ch. 3 and Ch. 12 | Ch. 3, 12 — Layer 2 |

### Related Tools
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://github.com/Olanetsoft/midnight-mcp | Midnight MCP Server — AI assistant integration for Midnight development (search contracts, analyze Compact code, compile via hosted service) | Ch. 12 — developer tooling |

---

## SDK & Integration

### Mesh SDK (JavaScript/TypeScript)
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://meshjs.dev | Mesh SDK main website — multi-blockchain framework | Ch. 12 — SDK layer |
| https://meshjs.dev/midnight/setup | Midnight-specific setup guide — installation, quick start, Lace wallet integration | Ch. 12 — developer experience |
| https://meshjs.dev/midnight/api | Detailed API reference — `MidnightSetupAPI`, deploy, join, query contracts | Ch. 12 — Layer 5/7 pipeline |
| https://www.npmjs.com/package/@meshsdk/midnight-setup | NPM package — official Midnight SDK for JS/TS | Ch. 12 — developer tooling |

---

## Wallet & User-Facing Infrastructure

| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://www.lace.io | Lace Wallet — official Midnight browser extension (Chrome/Brave/Edge) | Ch. 12 — Layer 7 (user interaction) |

**Browser API access**: `window.midnight?.mnLace`  
**Key methods**: `enable()`, `disconnect()`, `state()`, `submitTransaction()`

---

## Compiler & Development Tools

### Compact Compiler (Docker)
```bash
docker pull ghcr.io/midnightntwrk/compact:latest

docker run --rm -v $(pwd):/workspace \
  ghcr.io/midnightntwrk/compact:latest \
  compile contracts/MyContract.compact --out compiled/
```

### Devnet Information
- **Network**: Midnight Devnet (testnet environment)
- **Fee Token**: tDUST (testnet equivalent of DUST, referenced in Ch. 12's three-token model)
- **Proof Server**: localhost:6300 (as described in Ch. 12's four-phase pipeline)
- **Faucet**: Built into Lace Wallet

---

## Learning Resources

### Video & Audio
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://www.youtube.com/@midnight.network | Midnight YouTube — tutorials, conference talks, workshops | General |
| https://midnight.network/unshielded | Unshielded Podcast — privacy discussions, developer interviews | Ch. 9 — PETs landscape |

### Blog Posts (Technical Deep Dives)
| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://midnight.network/blog | Official blog — updates, technical articles, use cases | General |
| https://midnight.network/blog/zero-knowledge-demystified | ZK proofs without math background — ZK SNARKs explained | Ch. 1 — The Promise |
| https://midnight.network/blog/hello-world | Midnight's mission, vision, and technical innovation | Ch. 12 — overview |
| https://midnight.network/blog/midnight-s-powerful-and-versatile-data-protecting-smart-contracts | Deep dive into Compact contracts and privacy-preserving computation | Ch. 3, 12 — Layer 2 |

---

## Community & Support

| URL | Description |
|-----|-------------|
| https://discord.com/invite/midnightnetwork | Midnight Discord — developer community, technical support |
| https://x.com/MidnightNtwrk | Twitter/X — release announcements, updates |
| https://www.linkedin.com/showcase/midnight-ntwrk/ | LinkedIn — professional updates, partnerships |
| https://t.me/Midnight_Network_Official | Telegram — community chat |
| https://midnight.network/contact | Official contact form — business inquiries, partnerships |
| https://midnight.network/faq | FAQ — common questions and quick answers |

---

## Brand & Institutional

| URL | Description | Book Relevance |
|-----|-------------|----------------|
| https://midnight.network/brand-hub | Official logos, brand guidelines, media assets | — |
| https://www.midnight.gd | Glacier Drop — community token distribution | Ch. 12 — Layer 7 economics |
| https://iohk.io | Input Output Global (IOG) — parent research organization | Ch. 12 — institutional context |

---

## Broader ZK Ecosystem URLs (Referenced in Book but Not Linked)

These URLs correspond to projects, tools, and resources discussed in the book but not included in the bibliography:

### Layer 1 — Setup & Ceremonies (Ch. 2)
| URL | Description | Book Reference |
|-----|-------------|----------------|
| https://ceremony.ethereum.org | Ethereum KZG Summoning Ceremony portal (141,416 participants) | Ch. 2 — "The Summoning" |
| https://l2beat.com/stages | L2Beat Stages Framework for rollup maturity | Ch. 8, 14 — Stage 0/1/2 |
| https://ethproofs.org | Ethereum Foundation ZK proving cost tracker | Ch. 13 — cost curves |

### Layer 2 — Other ZK Languages (Ch. 3)
| URL | Description | Book Reference |
|-----|-------------|----------------|
| https://noir-lang.org | Noir — Rust-inspired backend-agnostic ZK language (Aztec) | Ch. 3 — Philosophy D |
| https://leo-lang.org | Leo — Aleo's ZK programming language | Ch. 3 — Philosophy D |
| https://www.cairo-lang.org | Cairo — StarkNet's ZK-native language | Ch. 3 — Philosophy B |
| https://docs.succinct.xyz/docs/sp1/introduction | SP1 — RISC-V zkVM | Ch. 3 — Philosophy C, Ch. 11 |
| https://www.risczero.com | RISC Zero — general-purpose zkVM | Ch. 3 — Philosophy C, Ch. 11 |

### Layer 5 — Proof Systems (Ch. 6)
| URL | Description | Book Reference |
|-----|-------------|----------------|
| https://zcash.github.io/halo2/ | Halo 2 documentation — the proof system Midnight uses | Ch. 12 — Layer 5 |

### Market & Enterprise (Ch. 13)
| URL | Description | Book Reference |
|-----|-------------|----------------|
| https://www.grandviewresearch.com/industry-analysis/zero-knowledge-proof-market-report | ZK market report ($97M → $7.59B) | Ch. 13 — already ref 42 |
| https://www.dtcc.com/digital-assets/tokenization | DTCC US Treasury tokenization on Canton Network | Ch. 13 — already ref 58 |

---

## How This File Could Be Used

1. **As a "Further Resources" appendix** — Chapter 12 readers would benefit most
2. **As a web companion page** — linked from the PDF/ebook version
3. **As bibliography supplements** — specific URLs added to existing refs 39-41
4. **Cherry-picked into the manuscript** — inline links at relevant points in the text

The highest-impact additions would be:
- The **Compact compiler GitHub** (readers will want to try it)
- The **Mesh SDK docs** (the actual DApp development path)
- The **Lace Wallet** (how users interact with Midnight)
- The **Halo 2 docs** (for Layer 5 readers who want to go deeper)
- The **L2Beat Stages framework** (referenced heavily in Ch. 8 and Ch. 14 but not linked)

---

*All URLs verified March 28, 2026*  
*Curated by John Santi — Midnight NightForce Bravo | Midnight Academy Triple Certified | Cardano Certified Blockchain Associate | Emurgo Certified Blockchain Business Consultant | Midnight Ambassador | author of "How to Code with Midnight"*
