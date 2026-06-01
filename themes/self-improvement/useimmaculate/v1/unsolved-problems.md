# Unsolved Problems

The scar from v1 is that taste mattered even more than expected. The system did not only need better prompts or more context. It needed a way to learn which trajectories were worth spending on, where the high-confidence checkpoints were, and when the model had started lying to itself about the path it was on.

Open problems:

- How to make the DSL compact enough to save tokens but rich enough to carry real product taste.
- How to detect when the model is no longer faithful to the perspective it started from.
- How to move from one-off generated success to repeatable linear progress.
- How to give less experienced developers leverage on domain-heavy systems like search without pretending the domain is easy.
- How to turn strong developer enthusiasm into a product loop that works every day, not just in impressive demos.

This is what created v2: the need for an instructor loop that can optimize code generation around high-confidence trajectories and checkpoints. v1 proved the harness could ship a real search engine. v2 has to make that kind of judgment repeatable.
