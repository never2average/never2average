# Approach

Immaculate v1 came from a very specific frustration: there were problems frontier models could reason through, but ordinary vibe-coding harnesses could not build. Search was the clearest example. From the outside, a search product looks almost insultingly simple: a text box, a query, a result. But the real product is hidden in ranking, retrieval, query understanding, latency, evals, corpus shape, and dozens of tiny judgment calls that are easy to derive from first principles and brutally hard to copy from screenshots.

That made search work a bottleneck. Tasks that the models could not solve through a normal harness were also tasks younger developers on the team could not just pick up. Search-related issues stopped being ordinary tickets and effectively became domain-expert work. Two or three people had to live inside the problem, almost around the clock, just to keep improving the engine and the systems around it.

Immaculate v1 was the attempt to change that. The product had to give an agent enough live product description, constraints, and taste to make progress on components that could not be copied. It was not trying to generate another CRUD app. It was trying to help with the kind of work where the answer has to be reasoned into existence.

The first proof came when a generated output became a deployed search engine. That was the moment v1 stopped being a toy. It showed that the harness could produce something real enough to work on, ship, and judge against the same standard as hand-built search work.
