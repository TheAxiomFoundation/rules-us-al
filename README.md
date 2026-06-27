# rulespec-us-al

This repository is archived. Its canonical content now lives in
[`TheAxiomFoundation/rulespec-us`](https://github.com/TheAxiomFoundation/rulespec-us)
under `us-al/`; keep all future RuleSpec work there.

Alabama RuleSpec source registry and policy metadata.

## Contents

- `sources/`: source slices, target manifests, and sidecar metadata when available.
- `statutes/`, `regulations/`, or `policies/`: RuleSpec YAML when encoded rules are added.
- `.github/workflows/`: wrapper around the shared RuleSpec validation workflow.

## Conventions

Use RuleSpec YAML under `statutes/`, `regulations/`, or `policies/` for encoded rules. Keep source text with matching `.meta.yaml` files that record provenance and relations. Large XML or source payloads belong in object storage, with only registry or manifest metadata in Git.

In the canonical monorepo, Alabama-administered materials live under `us-al/`; shared federal materials live at the country root.
