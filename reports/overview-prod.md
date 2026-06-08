# Overview: prod
*Last updated: 2026-06-09 04:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T04:15 (2445 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,174 | avg: 13,639 | max: 84,644 | trend: INCREASING (+4.21/hr))
```
▃▂▁▂▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▂▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▁▁▁▁▅▂▁▁▁
```

**Heap InUse** (current: 227.1MB | avg: 212.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▅▃▂▄▃▃▂▂▂▃▂▁▂▂▂▂▂▃▃▅▄▁▂▃▂▃▁▃▂▂▂▂▂▃▂▁▁▁▂▃▂▃▁▂▃▂▂▁▂▁▁▃▃▂▂▂▂▂▃▁▃▃▃▂▃▁▅▆▃▃▄▃▃▂▂▂▁▃▁█▆▃▁▂▁▂▁▂▁▂▂▆▅▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,174 | 14,194 | -20 | 13,639 | 84,644 | INCREASING (+4.21/hr) |
| Heap InUse | 227.1MB | 230.6MB | -3.5MB | 212.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3327.7MB | 3327.5MB | +0.2MB | 2436.7MB | 6883.9MB | |
| Heap Objects | 868,653 | 1,106,727 | -238074 | 935,747 | 17,165,538 | |

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
| 2026-06-09 | 52 | 15,364 | 283.9MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bytes.growSlice` | 2.88MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 86.13GB |
| 2 | `reflect.growslice` | 74.32GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.22GB |
| 4 | `jackskj/carta.getUniqueId` | 66.61GB |
| 5 | `reflect.unsafe_New` | 59.01GB |
| 6 | `fmt.Sprintf` | 54.34GB |
| 7 | `fmt.(*buffer).writeString` | 47.48GB |
| 8 | `reflect.unsafe_NewArray` | 44.04GB |
| 9 | `carta/value.NewCell` | 42.1GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 37.4GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.76GB | 3.76GB | 3.62GB | 0B |
| `evaluation.mergeMetadata` | 1.96GB | 1.96GB | 1.88GB | 0B |
| `local.(*Client).EvaluateV2` | 5.70GB | 5.70GB | 5.50GB | 0B |
| `local.topologicalSort` | 801.02MB | 800.52MB | 774.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.49GB | 5.48GB | 5.27GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 760.18MB | 760.18MB | 750.71MB | 0B |
| `localEvaluation.getMapOfValue` | 5.49GB | 5.48GB | 5.27GB | 0B |
| `utils.ParseFeatureFlag` | 5.50GB | 5.49GB | 5.28GB | 0B |

**Total FF alloc (current snapshot):** 29.41GB  |  **24h avg:** 28.33GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2445 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2445 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2096/2445 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2445 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 24.6MB | 2096/2445 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2445 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 15.13MB | 1566/2445 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2445 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2445 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.59MB | 65/2445 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2445 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2445 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2445 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2445 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2445 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 31.51GB | 962/2445 | `███░░░░░░░░░░░░ 25%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2445 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2445 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 24.55GB | 1819/2445 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `reflect.growslice` | 22.26GB | 1657/2445 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
