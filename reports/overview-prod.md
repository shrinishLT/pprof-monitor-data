# Overview: prod
*Last updated: 2026-06-10 11:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T11:45 (2823 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,276 | avg: 14,069 | max: 84,644 | trend: INCREASING (+4.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 294.8MB | avg: 226.5MB | max: 3154.1MB | trend: stable (+0.12MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,276 | 14,337 | -61 | 14,069 | 84,644 | INCREASING (+4.35/hr) |
| Heap InUse | 294.8MB | 187.7MB | +107.1MB | 226.5MB | 3154.1MB | stable (+0.12MB/hr) |
| Heap Sys | 3318.8MB | 3318.6MB | +0.2MB | 2555.6MB | 6883.9MB | |
| Heap Objects | 1,598,110 | 441,441 | +1156669 | 984,209 | 17,165,538 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 142 | 17,700 | 332.4MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 2.74MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewReaderSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 133.0GB |
| 2 | `segmentio/kafka-go.makePartitions` | 129.22GB |
| 3 | `jackskj/carta.getUniqueId` | 118.37GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 110.94GB |
| 5 | `reflect.unsafe_New` | 104.99GB |
| 6 | `fmt.Sprintf` | 88.17GB |
| 7 | `fmt.(*buffer).writeString` | 84.2GB |
| 8 | `carta/value.NewCell` | 75.1GB |
| 9 | `reflect.unsafe_NewArray` | 66.05GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 55.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.38GB | 6.38GB | 6.24GB | 0B |
| `evaluation.mergeMetadata` | 3.35GB | 3.34GB | 3.28GB | 0B |
| `local.(*Client).EvaluateV2` | 9.74GB | 9.74GB | 9.52GB | 0B |
| `local.topologicalSort` | 1.36GB | 1.36GB | 1.32GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.32GB | 9.32GB | 9.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.31GB | 1.31GB | 1.29GB | 0B |
| `localEvaluation.getMapOfValue` | 9.32GB | 9.32GB | 9.10GB | 0B |
| `utils.ParseFeatureFlag` | 9.34GB | 9.33GB | 9.12GB | 0B |

**Total FF alloc (current snapshot):** 50.13GB  |  **24h avg:** 48.98GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2823 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2823 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2474/2823 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2823 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.55MB | 2474/2823 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2823 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.97MB | 1890/2823 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2823 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2823 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2823 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2823 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2823 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2823 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2823 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.89GB | 1340/2823 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2823 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.86GB | 2197/2823 | `████░░░░░░░░░░░ 31%` |
| 8 | `reflect.growslice` | 37.48GB | 2035/2823 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 32.59GB | 2051/2823 | `███░░░░░░░░░░░░ 26%` |
| 10 | `reflect.unsafe_New` | 32.17GB | 1815/2823 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
