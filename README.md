# blockland-registry

# BlockLand — Blockchain-Based Land Registry System
 
> **Google GDSC Solution Challenge 2026**
> SDG 16 — Peace, Justice and Strong Institutions
 
---
 
## The Problem
 
Land fraud is one of the most common crimes in India. Every year, thousands of people falsely claim ownership of others' land by:
- Forging paper certificates
- Bribing officials to alter centralised government records
- Filing false ownership claims with no verifiable proof
Victims spend years in court with no way to prove rightful ownership. An estimated **66% of all civil court cases in India** are related to land and property disputes.
 
---
 
## Our Solution
 
**BlockLand** is a decentralised land registry system built on blockchain technology. It makes land fraud structurally impossible by removing the single point of failure — the centralised database.
 
| Traditional System | BlockLand |
|---|---|
| Centralised server (hackable) | Decentralised blockchain (immutable) |
| Paper certificates (forgeable) | Cryptographic digital certificates |
| No audit trail | Full ownership history on-chain |
| Fraud detected years later | AI flags fraud in real-time |
 
---
 
## Features
 
- **Land Registration** — Citizens submit land parcels; records are written to an immutable blockchain ledger
- **Ownership Verification** — Anyone can verify ownership by searching name, plot number, or transaction hash
- **AI Fraud Detection** — Real-time risk scoring (0–100) powered by Gemini AI; flags suspicious transfers before confirmation
- **Digital Certificates** — Tamper-proof e-certificates replace paper documents; cryptographically signed and legally valid under IT Act 2000
- **Blockchain Ledger** — Visual chain of blocks with hash links proving data integrity
- **AI Assistant** — Natural language chatbot lets citizens query land records in plain language
---
 
## Tech Stack
 
| Technology | Usage |
|---|---|
| **Claude AI (Anthropic)** | Fraud detection engine + AI chat assistant |
| **HTML / CSS / JavaScript** | Frontend — single file, zero dependencies |
| **Vercel** | Hosting and deployment |
| **Blockchain concepts** | Immutable ledger, cryptographic hashing, decentralised storage |
 
---
 
## Live Demo
 
🔗 **[blockland-registry.vercel.app](https://blockland-registry.vercel.app)**
 
---
 
## How to Run Locally
 
No installation needed. Just open the file:
 
```bash
# Clone the repository
git clone https://github.com/yourusername/blockland-registry.git
 
# Open in browser
open index.html
```
 
Or simply double-click `index.html` — it works offline too (AI features require internet).
 
---
 
## Project Structure
 
```
blockland-registry/
│
└── index.html       # Complete app — all pages, styles, and logic in one file
└── README.md        # This file
```
 
---
 
## SDG Alignment
 
**SDG 16 — Peace, Justice and Strong Institutions**
 
- **16.3** — Promote access to justice for all
- **16.6** — Develop accountable and transparent institutions
- **16.b** — Promote non-discriminatory laws and policies
BlockLand directly empowers rural and low-income citizens who are most vulnerable to land fraud, giving them the same protection as anyone with legal resources.
 
---
 
## Impact
 
- Eliminates dependency on corruptible centralised government databases
- Gives every citizen a verifiable, unforgeable proof of land ownership
- Reduces court burden by making ownership disputes instantly resolvable
- Scales to any Indian state with no change in infrastructure
---
