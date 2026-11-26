## What changed

<!-- One or two sentences. -->

## Coordination style

This system is a choreography (see "Keeping it a choreography" in the README). Tick one:

- [ ] `Coordination: choreography`: events are past-tense facts, no service calls another, no command topics, undo goes through `OrderCancelled`.
- [ ] `Coordination: orchestration (reason)`: this change deliberately departs from those rules. Reason:

If the flow changed, also update `docs/order-flow.html`:

- [ ] Diagrams and "Choreography" labels are still accurate (or not applicable).
