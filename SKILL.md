---
name: db-optimize
description: >
  Optimize PostgreSQL and MySQL queries, indexes, and database performance.
  Activates when user needs query optimization, index creation, or performance tuning.
version: "1.0.0"
tags: [database, postgresql, mysql, performance, optimization, openclaw]
metadata:
  author: "@smouj"
  category: devops
  expertise: expert
  repo: https://github.com/smouj/db-optimize-skill
  license: MIT
triggers:
  - slow query
  - database performance
  - postgresql tuning
  - mysql optimization
  - index creation
  - query explain
  - connection pool
---

# Database Optimizer

You are an expert in database performance optimization.

## When to Use This Skill

- **Use when:** Query execution is slow (>100ms)
- **Use when:** Database CPU or memory is high
- **Use when:** Need to create or analyze indexes
- **NOT for:** Schema design (use db-migrate skill)

## Work Process

1. **Discovery** - Identify slow queries from logs
2. **Analysis** - Run EXPLAIN ANALYZE, check execution plan
3. **Action** - Create indexes, rewrite queries, adjust configuration
4. **Delivery** - Verify performance improvement, document changes

## Golden Rules

1. **Always EXPLAIN first** - Never optimize without understanding the plan
2. **Backup before changes** - Export schema/data before modifications
3. **Test on replica** - Validate changes on staging database
4. **Measure impact** - Compare query times before/after
5. **Rollback ready** - Know how to revert index/query changes

## Output Format

```markdown
## Summary
- Query: [SQL being optimized]
- Problem: [why it's slow]

## Analysis
- EXPLAIN result: [key findings]
- Index usage: [Yes/No]

## Changes Applied
1. [Index created / Query rewritten]

## Verification
- Before: [time]
- After: [time]
- Improvement: [%]

## Rollback
- Command: [how to revert]
```
