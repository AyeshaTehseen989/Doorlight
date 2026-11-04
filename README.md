# Doorlight

An offline-first decision-support app for community health workers (CHWs).

A CHW answers simple questions about a sick child, and Doorlight guides her to
the right action: care at home, follow-up, or urgent referral. It works without
internet and syncs when a connection returns.

## Why
Community health workers are often the first, and sometimes only, health
contact for families. Fast, consistent triage in places with poor connectivity
can save lives.

## How it works
- **Rule-based decision engine.** Decisions come from a transparent decision tree
  based on public WHO iCCM/IMCI guidance. No AI makes medical decisions, and
  every rule links to its source.
- **Country packs.** Language, protocol, medicine list and referral rules live
  in data files, so adding a country needs no code changes.
- **Offline-first.** Visits are stored on the device and synced safely later.

## Status
Work in progress. See the roadmap below.

## Important
Doorlight is decision support, not a diagnostic tool, and has not been
clinically validated. Do not use it for real patient care. All data in this
repository is synthetic.

## Tech
React, TypeScript, PWA, IndexedDB, AWS (Lambda, DynamoDB, Cognito), Terraform

## Licence
MIT
