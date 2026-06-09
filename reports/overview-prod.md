# Overview: prod
*Last updated: 2026-06-10 05:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T05:05 (2743 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,418 | avg: 13,950 | max: 84,644 | trend: INCREASING (+4.20/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▃▁▁▂▁▁▁▂▂▁▂▁▁▃▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▇▅▂▁▁▄▃▃▄▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 229.8MB | avg: 223.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▂▂▂▁▁▁▄▂▁▃▂▁▁▃▃▁▂▂▁▄▃▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▅█▆▅▃▁▁▄▃▃▄▄▃▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,418 | 15,038 | -620 | 13,950 | 84,644 | INCREASING (+4.20/hr) |
| Heap InUse | 229.8MB | 251.1MB | -21.3MB | 223.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3320.7MB | 3321.2MB | -0.5MB | 2533.3MB | 6883.9MB | |
| Heap Objects | 938,861 | 841,664 | +97197 | 974,392 | 17,165,538 | |

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
| 2026-06-10 | 62 | 17,157 | 328.0MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.06MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 120.08GB |
| 2 | `reflect.growslice` | 109.37GB |
| 3 | `jackskj/carta.getUniqueId` | 98.18GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 91.75GB |
| 5 | `reflect.unsafe_New` | 87.0GB |
| 6 | `fmt.Sprintf` | 80.54GB |
| 7 | `fmt.(*buffer).writeString` | 69.93GB |
| 8 | `carta/value.NewCell` | 62.11GB |
| 9 | `reflect.unsafe_NewArray` | 61.32GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 49.39GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.95GB | 5.95GB | 5.84GB | 0B |
| `evaluation.mergeMetadata` | 3.14GB | 3.13GB | 3.08GB | 0B |
| `local.(*Client).EvaluateV2` | 9.08GB | 9.07GB | 8.92GB | 0B |
| `local.topologicalSort` | 1.27GB | 1.27GB | 1.24GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.65GB | 8.65GB | 8.49GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.26GB | 1.26GB | 1.25GB | 0B |
| `localEvaluation.getMapOfValue` | 8.65GB | 8.65GB | 8.49GB | 0B |
| `utils.ParseFeatureFlag` | 8.67GB | 8.66GB | 8.50GB | 0B |

**Total FF alloc (current snapshot):** 46.67GB  |  **24h avg:** 45.81GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 75.8MB | 45/2743 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 57.47MB | 75/2743 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2394/2743 | `███████░░░░░░░░ 48%` |
| 4 | `database/sql.convertAssignRows` | 29.42MB | 96/2743 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 27.82MB | 2394/2743 | `█████░░░░░░░░░░ 36%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2743 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 15.56MB | 1826/2743 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2743 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2743 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2743 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2743 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2743 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2743 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2743 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 44.51GB | 1260/2743 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2743 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 35.61GB | 2117/2743 | `████░░░░░░░░░░░ 28%` |
| 8 | `reflect.growslice` | 34.02GB | 1955/2743 | `████░░░░░░░░░░░ 27%` |
| 9 | `jackskj/carta.getUniqueId` | 29.52GB | 1971/2743 | `███░░░░░░░░░░░░ 23%` |
| 10 | `reflect.unsafe_New` | 29.22GB | 1735/2743 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
