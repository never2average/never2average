# Learnings

The biggest learning from v1 was that more intelligence does not remove the need for structure. Better models made the product possible, but they also made wasted loops more expensive. If the agent gets stuck in a local loop, it can spend a huge amount of reasoning and code-generation budget while producing only abstract-seeming improvements.

The second learning was that sandboxes and delegation are not implementation details. They shape whether coding agents can safely explore, compare, and recover. Without a good sandbox and delegation model, the main agent either becomes too cautious or burns compute trying to control every detail itself.

The third learning was that high-confidence checkpoints matter more than vague progress. A checkpoint is valuable when future iterations from it have meaningfully worsened performance, or when the supposed improvement becomes abstract and unclear. That is the point where the system knows the generated output is worth grounding around.

The instructor loop exists because of that lesson. Instead of trusting abstract improvement across all checkpoints, v2 should distill the data around high-confidence trajectory points and ask: if we move from here, are we likely to uncover a real new learning, or are we just about to spend tokens making the system sound smarter?
