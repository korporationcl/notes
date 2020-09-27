# Simple Notification Service (SNS)

- Instant, push-based delivery system (no polling like SQS)
- Simple API and integration with applications
- Flexible message delivery over multiple transport protocols
- Cheap, pay as you go with no upfronts.
- You can manage it through the Web Console
- SNS vs SQS:
  - both messaging systems
  - SNS is push, SQS is pull based (polling)
- **You can recycle previous SNS topic name after 30-60 seconds of being deleted.**
- **After a message has been published to the topic it can't be recalled.**