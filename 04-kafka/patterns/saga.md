# Saga pattern

Tags: #kafka #saga #microservices #consistency

## Context
When a business transaction spans multiple services (Order → Payment → Inventory → Shipping), you need a strategy to keep data consistent without a global DB transaction.

## Two styles
- **Choreography**: services publish/consume events; no central controller.
- **Orchestration**: a saga orchestrator commands participants and tracks state.

## Key requirements
- Idempotent handlers (handle duplicate messages).
- Clear compensation actions (undo) for each step.
- Correlation ID for tracing.
- Retry + DLQ/DLT for poison messages.

## Minimal state machine
- CREATED → PAID → RESERVED → SHIPPED → COMPLETED
- Compensation paths:
  - Payment failed: CANCEL order
  - Inventory failed after payment: REFUND + CANCEL
  - Shipping failed after reserve: RELEASE inventory + REFUND

## Checklist
- [ ] Event schema versioning
- [ ] Exactly-once expectations clarified (usually “effectively once”)
- [ ] Outbox/inbox pattern considered
- [ ] Monitoring (lag, DLT rate, error rate)

## References
- Prefer official Kafka + Spring Kafka docs for operational details.
