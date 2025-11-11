---
layout: page
title: DSC 180A Methodology 4
---

**Name:** Jonathan Gu  
**Email:** jogu@ucsd.edu

**Section:** B10  
**Mentor:** Rajesh Gupta

**What is the most interesting topic covered in your domain this quarter?**  
Ethereum-based document verification: anchoring SHA-256 fingerprints on a public chain and proving authenticity by re-hashing files client-side stood out because it blends cryptography, smart contracts, and wallet UX into a tangible, user-facing workflow.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
Expand the dApp into a full registrar workflow: add role-based access (faculty vs. students), integrate ENS/metadata for document URIs, and explore layer-2 rollups (e.g., Optimism) to benchmark gas savings versus Sepolia while keeping the same hashing/verification flow.

**What is a potential change you would make to the approach taken in your current Quarter 1 Project?**  
Reinstate a lightweight access-control layer (perhaps using allowlists stored on-chain or via a backend signature) so only approved university accounts can register, while still letting anyone verify; this balances openness for testing with realistic issuance constraints.

**What other techniques would you be interested in using in your project?**  
Incorporate zero-knowledge proofs or Merkle trees for batch attestations, use decentralized storage (IPFS/Filecoin) for optional document metadata, and add automated CI tests that run Hardhat + front-end integration checks to catch regressions before redeploying.
