# Approach

Immaculate v2 starts from the scar tissue of v1. v1 proved that the harness could generate a search engine worth deploying, but it also exposed the two places where the system bled tokens: weak sandbox/delegation structure, and local loops where the agent kept working without making real progress.

The new approach is to stop treating one agent trajectory as the sacred path. v2 should keep parallel trajectories alive, compare them against grounded outputs, and only spend expensive code-generation calls when the system has enough confidence that the next move is worth the compute.

The instructor loop is the center of the design. Its job is to grade the main model's request to call the code-generation tool. Code generation is expensive, and a bad call wastes both frontier-model reasoning and downstream coding-agent compute. The instructor has to decide whether the request is grounded enough, testable enough, and close enough to a high-confidence trajectory point to justify the spend.

Nothing in v2 has been built yet. It is still the design frontier that v1 forced into view: a system where sandboxes, delegation, parallel search, and gated code generation work together so the model does not simply think harder in the wrong direction.
