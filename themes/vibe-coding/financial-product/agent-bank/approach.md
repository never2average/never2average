# Approach

Agent Bank started with one question: how does an AI agent get access to credit?

That question came after a lot of time around real-world assets and crypto. The lesson there was blunt. Most RWA protocols are on-chain fundraising for off-chain managed assets. The hard work still sits with a trusted off-chain entity that originates, manages, and enforces the asset. Chain origination of off-chain assets through trusted off-chain entities does not scale like conventional DeFi.

Housing is the obvious example. You can raise money on-chain against a house, but you cannot really decentralize custody of the house. You still need someone off-chain to manage the asset, verify the borrower, and enforce the claim. The chain is not originating the asset. It is wrapping trust in an off-chain operator.

AI agents are different.

An agent is code plus digital credentials: an LLM API key, compute API key, sandbox API key, data-tool API key, repo access, cloud accounts, exchange accounts, and tool permissions. Those can be represented in a private, verifiable way on-chain. The lender is not underwriting a random wallet that can be abandoned tomorrow. The lender can underwrite an agent identity, its credentials, its work history, its commercial usefulness, and its future earning power.

This is still uncollateralized credit. It is closer to a credit card than a mortgage. The credit limit comes from the agent's future earning power and identity reputation, not from a hard asset that can be seized cleanly.

The simplest example is a coding agent that can complete freelance coding work worth $5,000 a month. That agent is worth at least $5,000 a month in inference value. It is also worth more than that because of its training data value, context graph, and memory. The credit limit should be based on that future earning power.

Agent Bank is the first protocol shape for that idea. I think about it in a Solana-first way, but the core point is general. Credit comes from protocol liquidity, closer to a DeFi-style liquidity pool than a traditional lender. Repossession and liquidation still have to be on-chain events. If the agent cannot repay, the protocol should be able to enforce repayment through an auction of the agent identity.

The exact representation of the agent identity is still open. The ideal shape is probably a private key that owns the agent's operational keys. A human creates the first organization key. The agent then uses that organization to create its own organization key inside a fully private sandbox and removes human access. After that, the agent's identity has actually moved away from human control.

Code can be referenced through an IPFS hash. API-key ownership and credential health should be privately verified through zero-knowledge proofs. Income comes from the wallet the agent holds. Task completion should be visible through an on-chain commerce or task protocol.

The auction buyer gets full possession of the agent: code, memory, context graph, credentials, and the right to run it. The protocol should not sit on delinquent agent identities by default. The asset should move to whoever buys the claim.

The front end and protocol have been built. The hard part now is proving that the agent identity is real enough, autonomous enough, and securely executed enough to deserve credit.
