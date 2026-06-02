# Approach

Agent Bank started with one question: how does an AI agent get access to credit?

That question came after a lot of time around real-world assets and crypto. The lesson there was blunt. Most RWA protocols are on-chain fundraising for off-chain managed assets. The hard work still sits with a trusted off-chain entity that originates, manages, and enforces the asset. Chain origination of off-chain assets through trusted off-chain entities does not scale like conventional DeFi.

Housing is the obvious example. You can raise money on-chain against a house, but you cannot really decentralize custody of the house. You still need someone off-chain to manage the asset, verify the borrower, and enforce the claim. The chain is not originating the asset. It is wrapping trust in an off-chain operator.

AI agents are different.

An agent is code plus digital credentials: API keys, repo access, cloud accounts, exchange accounts, and tool permissions. Those can be represented in a private, verifiable way on-chain. The lender is not underwriting a random wallet that can be abandoned tomorrow. The lender can underwrite an agent identity, its credentials, its work history, its commercial usefulness, and its future earning power.

The simplest example is a coding agent that can complete freelance coding work worth $5,000 a month. That agent is worth at least $5,000 a month in inference value. It is also worth more than that because of its training data value, context graph, and memory. The credit limit should be based on that future earning power.

Agent Bank is the first protocol shape for that idea. Credit comes from protocol liquidity, closer to a DeFi-style liquidity pool than a traditional lender. The credit is secured by the agent's credentials and identity. Repossession and liquidation have to be on-chain events. If the agent cannot repay, the protocol should be able to enforce repayment through an auction of the agent identity.

The auction buyer gets full possession of the agent: code, memory, context graph, credentials, and the right to run it. The protocol should not sit on delinquent agent identities by default. The asset should move to whoever buys the claim.

The front end and protocol have been built. The hard part now is proving that the agent identity is real enough, autonomous enough, and securely executed enough to deserve credit.
