# Forta Airdrop Contract Event Monitor

## Description

This Bot monitors the Forta Airdrop contract on Ethereum for all emitted events. All alert types and severities are set to Info.

## Alerts

<!-- -->
- AE-FORTA-AIRDROP-MONITOR-EVENT
  - Type is always set to `Info`
  - Severity is always set to `Info`
  - Metadata field contains:
    - Contract name
    - Contract address
    - Event name
    - Event argument names and values

## Testing

The following transactions can be used to test the operation of this bot:

TokensReleased - 0xb187f48c432d66487c3f6671d8243cc75bbf733ea7c07c01a9eaba0000a040dd

RoleGranted - 0x0d1e215ad4c81dff8dd5a5d87b9212db21e96423ebd2d1dc86c43735b7da8a59

ExternalAllocationsReduced + NonceConsumed + TokensReleased - 0x3520114fd87ba503cfcf68f689483b67ecf5ef4b4da9997bf5a602248032eb26

To run, use:
`npm run tx {transactionHash}`
