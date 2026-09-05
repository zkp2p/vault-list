# Agent instructions

This repository owns the vault metadata list and its JSON schema. Read
`README.md`, `vault-list.json`, and `schema/vault-list.schema.json` before editing.

- Preserve the schema, unique vault identifiers, chain/address relationships,
  and the documented listing policy. A metadata entry does not prove a vault's
  current onchain state, safety, or performance.
- Verify any added or changed vault against current chain evidence. Do not
  invent rates, fees, payment methods, volume, or marketing claims.
- Use the committed npm lockfile and run `npm run validate` for list/schema
  changes. Include the relevant logo assets when adding a listing.
- Registry changes do not authorize contract calls, funding, or deployment.
  Keep credentials and private customer information out of metadata.
- Make a focused branch and PR. Documentation-only edits need reference checks
  and `git diff --check`; no chain transaction is required for validation.
