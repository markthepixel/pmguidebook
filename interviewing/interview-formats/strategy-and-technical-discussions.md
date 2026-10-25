# Strategy and Technical Discussions

Strategy questions explore how you connect a product decision to customers, the business, and the competitive environment. Technical discussions explore how you reason about feasibility and work with engineering constraints. These discussions may be separate or combined, and the depth expected depends on the role. Clarify the goal, explain your assumptions, and compare alternatives before recommending a direction. A general PM discussion may focus on tradeoffs, while a technical PM role may require a deeper understanding of systems and data. Confirm the expectations rather than assuming that every interview requires coding or detailed system design.

## Example

Imagine an interviewer asks whether a scheduling software company should add payments. You first clarify which customers the company wants to serve and what business goal the investment should support. For the discussion, suppose small service businesses want to collect deposits when appointments are booked, and the company is considering whether this could support a paid plan. You would investigate customer demand and willingness to pay, the alternatives customers already use, and the cost of operating the service before recommending a broad payments offering.

You compare building a full payment system with integrating an existing provider for a limited deposit feature. An integration could limit the initial scope, but it would still involve fees, provider dependencies, and responsibility for helping customers when payments fail. You suggest exploring a provider integration first, subject to engineering, security, and compliance review. You explain that this choice is based on the assumed need to test demand without committing to the broader work of operating payment infrastructure.

The interviewer then asks what happens if a deposit succeeds but the appointment isn't saved. You explain that the team needs a way to connect the payment and booking records, recognize incomplete transactions, and resolve them without charging the customer twice. You would work with engineers to discuss transaction states, retries, and reconciliation, rather than claim that a single API call removes the problem. If the business requires an experience the provider cannot support, you would revisit the scope or the provider choice. The approach in [Working with Engineers](../../process-skills/development/working-with-engineers.md) applies to this discussion as well as to the actual work.

## Pain Points

A strategy answer can sound confident while leaving demand, economics, or the company's ability to deliver unexplored. A technical answer can have the same weakness when it lists technologies without connecting them to the user problem. Avoid bluffing about systems you don't understand. Explain what you know, ask a focused question, and describe how you would work through the uncertainty with an engineer. The value of a build-versus-buy choice depends on the requirements and constraints, so don't present either approach as universally better.

## Practical Exercise

Choose a product expansion and compare building a small version with using an external service. Write a short recommendation based on the customer need and business goal. What assumption would most change your choice? [Business Model Fit](../../knowledge-skills/business-understanding/business-model-fit.md) can help you examine the business side.

## Related Research Topics

* Product Strategy Interviews \[ [Google](https://www.google.com/search?q=Product%20Strategy%20Interviews%20in%20product%20management) | [Perplexity](https://www.perplexity.ai/?q=Product%20Strategy%20Interviews%20in%20product%20management) ]
* Technical Product Interviews \[ [Google](https://www.google.com/search?q=Technical%20Product%20Interviews%20in%20product%20management) | [Perplexity](https://www.perplexity.ai/?q=Technical%20Product%20Interviews%20in%20product%20management) ]
* Build Versus Buy Decisions \[ [Google](https://www.google.com/search?q=Build%20Versus%20Buy%20Decisions%20in%20product%20management) | [Perplexity](https://www.perplexity.ai/?q=Build%20Versus%20Buy%20Decisions%20in%20product%20management) ]
