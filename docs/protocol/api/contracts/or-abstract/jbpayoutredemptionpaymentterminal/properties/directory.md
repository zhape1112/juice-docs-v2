# directory

Contract:[`JBPayoutRedemptionPaymentTerminal`](/protocol/api/contracts/or-abstract/jbpayoutredemptionpaymentterminal/README.md)​‌

Interface: [`IJBPayoutRedemptionPaymentTerminal`](/protocol/api/interfaces/ijbpayoutredemptionpaymentterminal.md)

**The directory of terminals and controllers for projects.**

# Definition

```solidity
/** 
  @notice
  The directory of terminals and controllers for projects.
*/
IJBDirectory public immutable override directory;
```

* The value cannot be changed.
* The resulting view function can be accessed externally by anyone.
* The resulting function overrides a function definition from the [`IJBPayoutRedemptionPaymentTerminal`](/protocol/api/interfaces/ijbpayoutredemptionpaymentterminal.md) interface.