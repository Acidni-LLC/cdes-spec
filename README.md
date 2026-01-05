# CDES Specifications

> **Cannabis Data Exchange Standard - Official Specifications**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Schema Version](https://img.shields.io/badge/Schema-v1.0.0-blue.svg)](https://schemas.cannabis-data-standard.org/v1/)

## What is CDES?

The **Cannabis Data Exchange Standard (CDES)** is an open specification for representing cannabis product data, enabling interoperability between dispensaries, labs, regulators, and technology platforms.

## Quick Start

### Python
```bash
pip install cdes-validator
```

```python
from cdes import validate_strain
result = validate_strain({"name": "Gelato", "type": "hybrid"})
print(f"Valid: {result.valid}")
```

## Schemas

| Schema | Description | Status |
|--------|-------------|--------|
| [strain.json](./schemas/v1/strain.json) | Strain definitions | Stable |
| [coa.json](./schemas/v1/coa.json) | Certificate of Analysis | Stable |
| [terpene-profile.json](./schemas/v1/terpene-profile.json) | Terpene measurements | Stable |
| [cannabinoid-profile.json](./schemas/v1/cannabinoid-profile.json) | Cannabinoid measurements | Stable |
| [terpene.json](./schemas/v1/terpene.json) | Terpene definitions | Stable |

## Reference Data

| Dataset | Description |
|---------|-------------|
| [Terpene Library](../cdes-reference-data/terpenes/) | 24 approved terpenes with CAS numbers |
| [Cannabinoid Library](../cdes-reference-data/cannabinoids/) | All cannabinoids |

## License

- **Specifications**: CC BY 4.0
- **Code Examples**: Apache 2.0
