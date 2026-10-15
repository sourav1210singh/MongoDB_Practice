# MongoDB Practice

Notebooks from working through MongoDB, covering the parts that actually come up in production
rather than just basic CRUD.

## Contents

| Notebook | Covers |
|---|---|
| `Querries in MongoDB.ipynb` | Query operators, filtering, projection |
| `Querying in MongoDB.ipynb` | Further query patterns |
| `Indexing in MongoDB.ipynb` | Index types, compound indexes, and why query shape decides index design |
| `Building Pipelines in MongoDB.ipynb` | Aggregation pipelines — `$match`, `$group`, `$project`, `$lookup` |

## Why indexing and pipelines

These two are where MongoDB performance is won or lost. A query without a supporting index does
a collection scan, and an aggregation that filters late does far more work than one that
filters first. Both notebooks are about that difference.

## Related

Certified in *Fundamentals of MongoDB* — Analytics Vidhya, April 2025.
