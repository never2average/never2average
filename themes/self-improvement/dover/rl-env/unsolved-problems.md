# Unsolved Problems

The hardest unresolved problem is how to train security judgment without teaching the model the wrong shortcuts. If the environment is weak, the model will learn to satisfy the environment instead of becoming safer in real applications.

Open problems:

- How to reward secure code generation, not just successful post-hoc patching.
- How to make the red-team loop strong enough that the coding model cannot fool it with shallow fixes.
- How to choose app scenarios that represent real generated software rather than toy CTF examples.
- How to transfer learning from sandboxed clones back into the open coding model's normal generation behavior.
- How to measure whether the trained model is actually better at detecting security bugs than the open model baseline.

The RL environment works when an open model that used to miss basic security bugs starts generating code with a stronger security prior before Dover has to catch the mistake downstream.
