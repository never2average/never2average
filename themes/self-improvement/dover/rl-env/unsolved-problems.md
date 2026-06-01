# Unsolved Problems

The hardest unresolved problem is improving the security behavior of the coding model itself. Dover should not only catch bugs after generation. The RL environment has to make the open coding model less likely to create insecure code in the first place.

That matters because open models are still weak at cybersecurity. Public benchmarks show the gap. Microsoft's DefenderBench includes vulnerability detection and fixing tasks. Its best open-weight Llama result still trails the strongest proprietary model it tested. CyberSOCEval says the same thing from the defender side. Current LLMs are far from saturating malware analysis and threat-intelligence reasoning, and test-time reasoning has not transferred to cybersecurity the way it has to coding and math.

Sources:

- [DefenderBench](https://github.com/microsoft/DefenderBench)
- [CyberSOCEval](https://arxiv.org/abs/2509.20166)

The open problem is not a custom recording format. It is whether the RL environment can turn red-team pressure into better generation behavior. If the agent keeps getting stuck in loops, or only learns to patch after the fact, the model has not really learned security.
