## Definition
The way KERI addresses the [security-cost-performance architecture trade-off](security-cost-performance-architecture-trade-off) is via [delegation](delegation) of identifier prefixes. Delegation includes a delegator and a delegate. For this reason we may call this a cooperative delegation. This is a somewhat **novel form of delegation**. 

## More

A major advantage of cooperative delegation is the delegator’s key management protects the delegate’s via recovery by the delegator. With cooperative delegation, any exploiter that compromises only the delegate’s authoritative keys may not capture control authority of the delegate. Any exploit of the delegate only is recoverable by the delegator. 

Source [Universal Identifier Theory](https://github.com/SmithSamuelM/Papers/blob/master/whitepapers/IdentifierTheory_web.pdf) by Samuel Smith