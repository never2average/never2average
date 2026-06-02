# Approach

Mynt is the thing that should make products like Agent Bank buildable by vibe coding.

Agent Bank is one of my favorite financial product areas, but it should not require all of my personal context to reproduce. The problem is that too much founder expertise is still locked in my head. Existing tools can help build the app around a financial product, but they do not safely reproduce the financial-product judgment itself.

That is what Mynt is for.

The user should be able to describe the financial product they want, and Mynt should generate the product around it: primitive graph, product spec, underwriting logic, pricing logic, risk assumptions, simulations, UI, backend, smart contracts, tests, monitoring, launch plan, and governance.

It has to work for more than credit. Credit is only one product class. There are insurance products, payment products, exchange products, rate products, yield products, and hybrids between them. A product that offers credit advances on insurance reimbursements is already a credit-insurance hybrid. That should not require a separate bespoke framework.

The core idea is one universal financial primitive graph. Actors should exist agnostic to product class. Value flows, rights, claims, triggers, controls, evidence, pricing, enforcement, lifecycle, interfaces, and evals should compose into subgraphs. Credit, insurance, payments, and exchanges should be product-specific compositions, not separate worlds.

Mynt should support both on-chain and off-chain products. These are vibe-coded products, but a lot of their funding and governance logic will naturally be on-chain. The generated product still needs the whole production surface: deployed code, tests, monitoring, governance, capital logic, security, and compliance sensitivity.

Nothing has been built yet. The real work is deciding the primitives.
