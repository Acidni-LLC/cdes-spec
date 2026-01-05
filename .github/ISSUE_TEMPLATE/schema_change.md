---
name: Schema Change Request
about: Propose a change to CDES JSON schemas
title: '[SCHEMA] '
labels: schema
assignees: ''
---

## Change Type

- [ ] 🐛 Bug fix (correction to existing schema)
- [ ] ✨ New optional field (non-breaking)
- [ ] 💥 Breaking change (new required field, type change, removal)
- [ ] 📚 Documentation improvement

## Affected Schema(s)
<!-- e.g., schemas/v1/strain.json, schemas/v1/coa.json -->

## Problem Statement
<!-- What problem does this solve? -->

## Proposed Change

```json
{
  "proposedField": {
    "type": "string",
    "description": "What this field represents"
  }
}
```

## Use Cases

1.
2.

## Breaking Change Impact
<!-- If breaking: who is affected, what's the migration path? -->

## Industry Benefit
<!-- Who benefits: dispensaries, labs, regulators, etc. -->

## Checklist

- [ ] I've searched existing issues for duplicates
- [ ] I've reviewed the schema versioning policy
- [ ] This change is backward compatible (or I've marked as breaking)
