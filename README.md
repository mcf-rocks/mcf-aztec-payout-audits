# Aztec Payout Audits - Provider 48

**Operator:** MCF
**Provider ID:** 48  
**Distribution Wallet:** `0x0800fA8cd092b4AbEaC368c8907814B9Adb68Aff`

This repository contains public audit records for staking payouts on the Aztec Network.

## Purpose
This repo allows delegators to independently verify reward distributions and commission calculations.

## Structure
- `runs/` — Contains audit files generated after each settlement
  - `epoch-*.json` → Full audit record + transaction calldata
  - `epoch-*.safe.json` → Safe Transaction Builder import format

## Verification
Delegators can re-run the payout tool using the same config and epoch range to verify results.
