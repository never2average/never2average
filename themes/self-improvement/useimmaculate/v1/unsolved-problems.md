# Unsolved Problems

The biggest unsolved problem in v1 was DSL optimization. The harness needed a language compact enough to save tokens, but expressive enough to carry the real shape of the product. Too little structure and the model drifted. Too much structure and the DSL became another thing that consumed the budget it was supposed to save.

The second unsolved problem was verification time. Verification scales with the test time of the computer. If an experiment took 20 hours to generate, it was not trivial to verify it honestly in two or three hours. That made the feedback loop much slower than the generation loop.

Those two problems shaped everything after v1:

- How do you optimize the DSL without losing the product taste it was meant to preserve?
- How do you verify long-running generated experiments without waiting almost as long as the experiment itself?

v1 proved that the harness could ship a real search engine. It also proved that generation was only half the problem. The harder part was making the language and verification loop efficient enough for progress to compound.
