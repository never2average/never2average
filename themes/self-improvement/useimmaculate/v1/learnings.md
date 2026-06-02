# Learnings

The biggest underestimation was how hard linear progress would be. It was not enough to ask a stronger model to code. The whole system needed a DSL that made learning token-efficient, and that DSL was much harder to get right than expected.

The early runs with weaker models did not really work. The product was too far outside the memory of most models, and forcing agents to code it consumed most of the time. It only started to feel real with the newest pro models, high-reasoning settings, and enough budget for the model to hold the shape of the product while making changes.

That made the core lesson sharper: more tokens are intelligence, but tokens alone are not taste. Reasoning models work because they spend more compute, but the harness has to police whether the model is staying faithful to its original perspective. A model can claim it is following the plan while quietly drifting into a different one.

The proudest signal was not a benchmark. It was serious developers saying they would use the product daily if it launched. These were people who do not treat technical competence lightly, and their reaction made the work feel worth the pain.
