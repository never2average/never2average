# Unsolved Problems

Nothing has been built yet.

The first blocker is deciding the universal financial primitives. Credit has obvious primitives like borrower, lender, repayment, liquidation, and risk. But Mynt cannot stop there. It also needs to represent insurance, payments, exchanges, rates, yield, and hybrids between them.

The second blocker is composition. A universal primitive graph is only useful if it can compose clean subgraphs. A credit product, an insurance product, an exchange, and a credit advance on insurance reimbursements should all be expressible without inventing a new system each time.

The third blocker is constraints. Financial products are not ordinary apps. A plausible product can still be unsafe if the incentives, liquidation path, payout logic, reserves, risk limits, or monitoring are wrong.

The fourth blocker is verification. Mynt has to test, simulate, and evaluate the generated product before it touches money. It also has to keep the assumptions visible so the user can understand what they are launching.

The fifth blocker is mapping the primitive graph to code. Mynt needs to generate the UI, backend, smart contracts, workflows, monitoring, tests, and governance layer from the same product structure.

The scary failure modes are obvious and serious: plausible but broken financial products, hidden risk assumptions, bad incentives, unsafe contract logic, fake yield, mispriced risk, and commoditized financial expertise without the judgment that made the product safe.

Mynt works when a new financial product can be launched from intent. The first target after Agent Bank should be a product that offers credit advances on insurance reimbursements. Longer term, Agent Bank should be fully replicable by Mynt.
