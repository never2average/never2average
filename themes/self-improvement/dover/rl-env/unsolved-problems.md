# Unsolved Problems

The hardest unresolved problem is improving the security behavior of the coding model itself. Dover should not only catch bugs after generation. The RL environment has to make the open coding model less likely to create insecure code in the first place.

That matters because open models are still weak at cybersecurity. Public benchmarks show the gap. Microsoft's DefenderBench includes vulnerability detection and fixing tasks. Its best open-weight Llama result still trails the strongest proprietary model it tested. CyberSOCEval says the same thing from the defender side. Current LLMs are far from saturating malware analysis and threat-intelligence reasoning, and test-time reasoning has not transferred to cybersecurity the way it has to coding and math.

Sources:

- [DefenderBench](https://github.com/microsoft/DefenderBench)
- [CyberSOCEval](https://arxiv.org/abs/2509.20166)

The second problem is reward hacking versus real learning. The model can learn to satisfy the environment, silence the red team, or patch after the fact without actually becoming better at secure generation. That would look like progress inside the loop and still fail the product.

The third problem is forgetfulness from the model point of view. Even if one run teaches the right security lesson, the model has to carry that lesson into future coding behavior. If the learning does not survive across tasks, Dover is only running a better local repair loop, not training a more secure coding model.

The open problem is not a custom recording format. It is whether the RL environment can turn red-team pressure into durable security behavior. If the agent keeps getting stuck in loops, reward-hacks the task, or forgets the lesson on the next app, the model has not really learned security.
