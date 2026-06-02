# Approach

Dover's RL environment came from a second realization: the harness should not only catch security bugs after code is written. If the stack is already driven by open code and open-source models, then the coding model itself should get better at generating secure code.

Self-hosted open models already give one kind of security perimeter. They reduce the amount of sensitive code and operational context flowing through hosted frontier APIs. But that does not mean they are good security engineers. In practice, open-source coding models are still weak at detecting security bugs, and can lag far behind older proprietary frontier models when the task requires real cybersecurity judgment.

The RL environment is the attempt to close that gap from inside the system. The agent should learn by acting inside cloned applications: inspect the app, generate or modify code, watch a red-team loop attack it, repair what failed, and repeat until secure generation becomes a trained instinct rather than a post-hoc scan.

The goal is not a benchmark trophy. The goal is to make the open coding model safer on the kind of application work Dover already sees, so every future generated patch starts from a better security prior.
