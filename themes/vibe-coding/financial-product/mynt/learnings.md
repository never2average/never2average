# Learnings

The first learning is that the product class is the wrong starting point. If Mynt starts with a credit library, an insurance library, and a payments library as separate universes, it will break the moment someone asks for credit advances on insurance reimbursements or a rate-plus-insurance product.

The second learning is that the primitive graph has to be appendable. I need to be able to discover a new primitive and add it gracefully. But removing primitives is dangerous, because it means the model of finance was wrong enough that previous products may no longer be explainable.

The third learning is that Mynt has to commoditize expertise, not taste. Taste is not the bottleneck here. The hard parts are primitives, composition, constraints, tests, simulations, financial DSL, risk modeling, smart-contract generation, regulatory sensitivity, and verification.

The fourth learning is that Mynt should not be only a generator. Agent Bank would be an app generated, managed, and improved by Mynt. The company harness can handle improvement over time, but Mynt has to create a product structure that can actually be improved.

The fifth learning is that production-grade means everything. The output has to be deployed, tested, monitored, governed, capitalized, secure, and sensitive to compliance. Otherwise Mynt is only a demo builder for financial products, which is the dangerous version.
