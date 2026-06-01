# Approach

The vertical AI web app came after Thin Wedge started showing where a CLI bends. The CLI was the right first surface. It was local, fast to set up, and believable. But some parts of the finance operator problem became hard to manage from a terminal alone.

Security permissions were the first pressure point. A finance agent touches sensitive business context, tokens, infra, cloud spend, and sometimes execution workflows. That needs a clearer permission surface than a local command loop can comfortably show.

Visualizations were the second pressure point. Token budgets, forecasts, pricing experiments, and attribution are easier to reason about when the user can see them. A CLI can answer a question. It is not the best place to live with a financial operating picture.

Scheduled tasks were the third pressure point. A CFO layer cannot only respond when someone types a prompt. Some work has to recur: budget checks, spend reviews, forecasts, and reminders around the operating plan.

That is why the next version became a web app. The system is still horizontal in capability, but the app is vertical in how it packages the work for a technical product operator. It is partially built now.
