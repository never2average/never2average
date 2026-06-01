# Unsolved Problems

The hardest unresolved piece is the instructor loop. Everything else in v2 depends on whether the system can judge when a code-generation request is worth making. If that gate is wrong, the rest of the architecture just spends compute more elaborately.

Open problems:

- How to grade a code-generation request before paying the full cost of executing it.
- How to keep parallel trajectories diverse without letting them become ungrounded branches.
- How to define a high-confidence checkpoint from generated output, performance movement, and failed future iterations.
- How to detect when the agent is trapped in a local loop and should branch, rewind, or stop.
- How to use sandboxes and delegated coding agents without losing the main model's taste and context.

The bar for v2 is concrete: on the same servers that v1 was able to deploy in production, v2 should get a 20 percent cost reduction. If it cannot make the already-working search systems cheaper without losing quality, then the instructor loop is not real yet.
