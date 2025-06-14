---
title: SPARQL Caching
---

# ⚡ Accelerate SPARQL with Declarative Caching

Take control of query performance with built-in, declarative caching using `SERVICE <cache:>` blocks.
Bring speed where it matters - without changing your data or logic.

```json
{
  "test": "foo"
}
```

```sql
SELECT * {
  SERVICE <cache:> {
    ...
  }
}
```
