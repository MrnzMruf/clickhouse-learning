# clickhouse-learning
My ClickHouse journey – queries, experiments &amp; real projects

----------------------------------------

# ClickHouse Production Playground

Goal: Master real-world ClickHouse deployment, configuration and operations  
Every day I implement and test one production-grade feature from scratch.

| Day | Topic                                           | Status | Date       | Notes |
|-----|--------------------------------------------------|--------|------------|-------|
| 1   | Single-node ClickHouse with Docker + persistent volumes | ☐ | -          | `docker-compose.yml` + healthcheck |
| 2   | Optimize config.xml (memory, merges, background pool) | ☐ | -          | Document each important parameter |
| 3   | users.xml + secure user with sha256 password     | ☐ | -          | IP restrictions + DB quotas |
| 4   | Enable query_log, text_log + rotation            | ☐ | -          | For debugging and auditing |
| 5   | 3-node ZooKeeper cluster with Docker             | ☐ | -          | Ready for replication |
| 6   | Replication + Sharding (2 shards × 2 replicas)   | ☐ | -          | `metrika.xml` + `macros.xml` |
| 7   | Materialized Views on real dataset               | ☐ | -          | Compare performance vs normal table |
| 8   | Load 100M+ rows NYC Taxi dataset                | ☐ | -          | Test MergeTree engine |
| 9   | TLS/SSL + HTTPS server configuration            | ☐ | -          | Self-signed + Let's Encrypt |
| 10  | Monitoring with Grafana + clickhouse-grafana plugin | ☐ | -       | Full dashboard export |
| 11  | Backup & restore using clickhouse-backup        | ☐ | -          | Real restore test |
| 12  | ClickHouse Keeper (built-in ZooKeeper replacement) | ☐ | -       | Zero external dependency |
| 13  | Table functions: s3(), url(), hdfs()             | ☐ | -          | Direct load from object storage |
| 14  | Projections for heavy aggregations               | ☐ | -          | Compare with Materialized Views |
| 15  | Final project: Real-time analytics cluster + full documentation | ☐ | - | Ready for resume & interviews |

When finished → box becomes ✅ and gets pushed  
Target: End of year have a repo that gets you hired instantly

