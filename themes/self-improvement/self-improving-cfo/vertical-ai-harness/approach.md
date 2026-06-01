# Approach

The full-stack Thin Wedge implementation came after the CLI started showing where a terminal bends. The CLI was the right first surface. It was local, fast to set up, and believable. But some parts of the finance operator problem needed a familiar interface.

Permissions were the first pressure point. A solo operator cannot keep remembering what permissions they gave an agent from memory or from a long chat history. A finance agent touches databases, payments, approvals, token spend, infra, and sometimes work for the rest of the team. That needs a visible source of truth.

Generative UI was the second pressure point. I did not want a fixed dashboard for everything. I wanted the product to show projections, spend, simulations, monitoring, and forecasts in the shape the work needed. A CLI can answer a question. It is not always the easiest place to navigate a financial operating picture.

Scheduled forecasts were the third pressure point. Cash flow changes. Plans change. Forecasts should run on a cadence instead of waiting for me to remember to ask.

That is why Thin Wedge needed a full-stack version. The agent is still horizontal in capability, but the interface is vertical around the finance work. Most of the web app has been built and is actively being integrated with the API.
