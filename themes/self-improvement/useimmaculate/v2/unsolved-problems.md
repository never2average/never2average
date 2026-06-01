# Unsolved Problems

The hardest unresolved piece is the instructor loop. More specifically, it is knowing when to call code generation at all. Code generation is not just another tool call. It burns inference, coding-agent loop time, and infra. If the instructor gate is wrong, the system does not become more tasteful. It just spends the full experiment budget in a more complicated way.

The second unresolved piece is trajectory comparison. v1 showed that an agent can get trapped in local loops where it keeps spending tokens without making progress. v2 needs parallel trajectories, but parallelism only helps if the system can compare them against grounded checkpoints instead of letting every branch sound promising.

Those two problems define taste for v2:

- Can the instructor decide that a code-generation request is worth the total experiment cost?
- Can the system compare trajectories well enough to avoid spending on branches that only look better in the abstract?

Taste is the cost efficiency of the entire experiment. That includes inference cost, coding-agent loop time, and infra cost. If v2 cannot improve that full cost curve, the instructor loop is not real yet.
