# Unsolved Problems

The front end and protocol have been built. The remaining problems are around proving that the borrower is real enough to underwrite.

The first blocker is proof of autonomy. An agent has to show that it can perform economically useful work without human supervision, and that its identity cannot be quietly amended by a real human. Otherwise humans can steal agent wallets, rewrite the identity, and steal the money.

The second blocker is proof of secure execution. The protocol has to know that the code and credentials behind the agent are running in a controlled enough sandbox for lenders to trust the identity.

The third blocker is prompt-injection risk against the agent itself. If a coding task, research task, or security task can secretly carry an instruction that makes the agent reveal private keys or transfer money for unauthorized services, borrowers and lenders both get attacked through the work stream.

The fourth blocker is identity auction design. If repayment is enforced through an agent identity auction, the auction has to transfer full possession cleanly enough that the buyer receives the thing they paid for.

The fifth blocker is non-circular economic activity. Agent Bank has to avoid the classic crypto trap where the apparent yield comes from the protocol itself. The protocol layer needs evidence that the agent is earning from real work.

The scary failure modes are all serious: fake agent productivity, credential leakage, malicious buyers at auction, circular yield, lenders losing claim, and attackers using task prompts to break the agent sandbox.

Agent Bank works when a commercially useful agent can receive a credit line against its future earning power, use that credit productively, and have repayment or liquidation enforced on-chain through the agent identity. It is one of my favorite financial product areas, but the second version should eventually be wiped out by Mynt.
