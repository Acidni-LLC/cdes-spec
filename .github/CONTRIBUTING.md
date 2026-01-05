# Contributing to CDES Specifications

Thank you for your interest in contributing to the Cannabis Data Exchange Standard!

## Overview

This repository contains the official CDES JSON Schemas and API specifications. Contributions help improve interoperability across the cannabis industry.

## Types of Contributions

### 1. Schema Improvements

- Fix errors in existing schemas
- Add optional fields (non-breaking)
- Improve documentation and descriptions

### 2. Breaking Changes

Breaking changes (new required fields, type changes, field removal) require:

1. Open an RFC issue first
2. Working group discussion
3. New major version (`v2/`, `v3/`)

### 3. Documentation

- Improve inline schema descriptions
- Add usage examples
- Fix typos

## How to Contribute

### Step 1: Open an Issue

Before making changes, open an issue to discuss:

- What problem you're solving
- Your proposed solution
- Impact on existing implementations

### Step 2: Fork and Branch

```bash
git clone https://github.com/YOUR-USERNAME/cdes-spec.git
cd cdes-spec
git checkout -b feature/your-feature-name
```

### Step 3: Make Changes

- Follow JSON Schema Draft 2020-12
- Include `$schema`, `$id`, `title`, `description`
- Add descriptions to all properties
- Test your changes locally

### Step 4: Validate

```bash
npm install
npm run validate
```

### Step 5: Submit PR

- Use a clear title: `feat(schema): add batch tracking fields`
- Reference the related issue
- Complete the PR template

## Schema Guidelines

### Required Metadata

```json
{
  "$schema": "https://json-schema.org/draft/2020-12/schema",
  "$id": "https://schemas.cannabis-data-standard.org/v1/example.json",
  "title": "CDES Example Schema",
  "description": "Clear description of what this schema represents"
}
```

### Property Naming

- Use **camelCase** for properties
- Use descriptive names (`totalThcPercentage` not `thc`)
- Include units in names when appropriate (`weightGrams`)

### Versioning

- `/v1/` - Current stable schemas
- `/v2/` - Breaking changes only
- Minor additions go to current version

## Code of Conduct

- Be respectful and constructive
- Focus on technical merit
- Welcome new contributors

## Questions?

- Open a [Discussion](https://github.com/cannabis-data-standard/cdes-spec/discussions)
- Review existing schemas for patterns
- Check the [CDES website](https://cdes.acidni.net) for documentation

---

**License**: Contributions are licensed under CC BY 4.0
