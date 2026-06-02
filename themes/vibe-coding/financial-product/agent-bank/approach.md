# Approach

Agent Bank is the v1 financial-product experiment: a chat-first way to turn a user's stated financial outcome into the first version of the logic behind it. The point is not to wrap a bank UI in an agent. The point is to let language create the structure that a financial product normally forces through forms, menus, and manual configuration.

The Agent Bank loop should stay narrow:

- Capture the user's desired outcome in plain language.
- Translate that into candidate financial logic, assumptions, and constraints.
- Show the reasoning clearly enough that a human can review it before anything touches real money.
- Preserve the output as an artifact that can become product state later.

Agent Bank is where the risky idea gets its simplest proof: can an agent assemble useful financial logic from intent without hiding the assumptions that make the logic dangerous?
