# Transaction Flow

## Normal Flow
1. User initiates a transfer
2. Transaction is recorded locally
3. UI reflects a pending state
4. Background sync attempts server confirmation
5. Status updates to success or failure

## Failure Scenarios
- Network unavailable after request
- Delayed server response
- Duplicate retry attempts

## Handling Strategy
- Pending states prevent duplicate actions
- Background reconciliation resolves final state
- Clear UI feedback reduces user uncertainty
