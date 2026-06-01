# Approach

Thin Wedge came from having already built an AI-native product once. I had seen how much time gets wasted building a SaaS product for a non-technical audience first, then slowly bolting an AI agent onto it later. That felt backwards for the kind of finance problem I actually had.

My main spend was no longer payroll. It was tokens. A conventional financial controller does not know how to budget token spend, attribute it, limit it, or forecast it against product goals. If spending 100 million tokens gives a real chance of cutting inference cost for the next two quarters to a third of its current value, that might be the right financial decision. If it does not, it is waste. I needed a finance layer that understood that kind of tradeoff.

The first version had to be local. No one was going to trust a new product to run their financial life in the cloud on day one. A CLI was the easiest honest surface. A desktop app is heavier. It takes longer to install. It has more screens. A CLI can be set up on a Google Meet call with one login command. Then you ask what you need, and you get what you asked for.

Thin Wedge is the financial planner I wanted as a technical product builder. It is FP&A for token spend, pricing experiments, parallel strategies, and the weird financial choices an AI-native company has to make before a normal finance team even has language for them.
