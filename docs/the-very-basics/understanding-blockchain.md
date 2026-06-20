---
sidebar_label: Understanding Blockchain
---

# Understanding Blockchain

Imagine a shared google doc that thousands of people have access to. Whenever someone makes an update, everyone’s doc updates at the exact same time. If someone tries to cheat and change a past record, the team rejects it because it doesn't match their docs and record.

**That is a blockchain.**

Instead of a doc, it’s a digital record book (**ledger**) maintained by thousands of independent computers (**nodes**). It tracks ownership of money, data, or digital items securely without needing a central authority defies the working principle of a bank.

## Key Terms

- **Block:** A bundle of recent transactions, like a single page in the record book.
- **Chain:** Blocks are permanently linked together in a chronological order. Changing a past block breaks the chain, making any sort of tampering obvious to everyone.
- **Decentralization:** No central authority controls the data, the entire network maintains it collectively.

## How It Works

<svg width="100%" viewBox="0 0 980 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Blockchain transaction flow diagram">
    <defs>
        <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
            <path d="M0,0 L0,6 L9,3 z" fill="#2a7de1" />
        </marker>
    </defs>
    <rect x="20" y="78" width="168" height="82" rx="16" fill="#eef6ff" stroke="#2a7de1" stroke-width="2" />
    <rect x="216" y="78" width="176" height="82" rx="16" fill="#eef6ff" stroke="#2a7de1" stroke-width="2" />
    <rect x="420" y="78" width="176" height="82" rx="16" fill="#eef6ff" stroke="#2a7de1" stroke-width="2" />
    <rect x="624" y="78" width="176" height="82" rx="16" fill="#eef6ff" stroke="#2a7de1" stroke-width="2" />
    <rect x="828" y="78" width="132" height="82" rx="16" fill="#eef6ff" stroke="#2a7de1" stroke-width="2" />
    <line x1="188" y1="119" x2="216" y2="119" stroke="#2a7de1" stroke-width="3" marker-end="url(#arrow)" />
    <line x1="392" y1="119" x2="420" y2="119" stroke="#2a7de1" stroke-width="3" marker-end="url(#arrow)" />
    <line x1="596" y1="119" x2="624" y2="119" stroke="#2a7de1" stroke-width="3" marker-end="url(#arrow)" />
    <line x1="800" y1="119" x2="828" y2="119" stroke="#2a7de1" stroke-width="3" marker-end="url(#arrow)" />
    <text x="104" y="107" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">1. You initiate</text>
    <text x="104" y="130" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">a transaction</text>
    <text x="304" y="107" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">2. Computers verify</text>
    <text x="304" y="130" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">you have the funds</text>
    <text x="508" y="107" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">3. It gets bundled</text>
    <text x="508" y="130" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">into a block</text>
    <text x="712" y="107" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">4. The block is</text>
    <text x="712" y="130" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">locked onto the chain</text>
    <text x="894" y="107" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">5. Everyone's</text>
    <text x="894" y="130" text-anchor="middle" fill="#17324d" font-size="18" font-family="Arial, sans-serif" font-weight="700">record updates</text>
</svg>

## What Makes It Unique?

- **No Single Point of Failure:** If one computer goes offline, the system still runs perfectly because thousands of others have a copy.
- **Permanent Record (Immutability):** Once data is locked onto the chain, it cannot be secretly edited, deleted, or censored by anyone, if it does the entire network will get to know.
- **Built-in Trust:** You don't need to know or trust the person you are transacting with, because the math and the network automatically makes the rules.

## Popular Networks

- **Bitcoin:** Secure digital money.
- **Ethereum:** The main network for programmable code and [smart contracts](understanding-smart-contracts).
- **Layer 2s (Arbitrum, Polygon):** Express lanes built on top of ethereum in case where Ethereum gets packed and expensive.
- **Solana:** Built for high-speed, low-cost applications.

Your [wallet](understanding-wallets) connects you to this network, securely holding your [tokens](understanding-tokens) and keeping track of your records.