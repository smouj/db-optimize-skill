# Database Optimizer

[![ES](https://img.shields.io/badge/ES-Español-red)](README.es.md)

## What It Solves

Optimize PostgreSQL and MySQL queries, create indexes, and tune database performance.

## When It Activates

- Slow queries, database performance issues
- PostgreSQL tuning, MySQL optimization
- Index creation, query explain
- Connection pool configuration

## Prerequisites

- Database access credentials
- Read-only replica for testing (recommended)

## Examples

```
Optimize slow SELECT query
Create index for WHERE clause
Analyze EXPLAIN output
Tune PostgreSQL configuration
```

## Supported Databases

| Database | Tools |
|----------|-------|
| PostgreSQL | pg_stat, EXPLAIN, pg_trgm |
| MySQL | EXPLAIN, InnoDB, slow_query_log |

## Limitations

- Requires database credentials
- Some changes need downtime

## License

MIT
