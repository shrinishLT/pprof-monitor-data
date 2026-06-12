# Overview: prod
*Last updated: 2026-06-12 08:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T08:55 (3364 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,487 | avg: 14,343 | max: 84,644 | trend: INCREASING (+3.40/hr))
```
▃▁▂▁▁▁▂▂▁▁▁▂▂▂▂▁▁▁▁▂▂▂▁▁▁▁▁▁▅▂▁▂▂▂▂▂▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▃█▁▁▁▁▁▁
```

**Heap InUse** (current: 261.9MB | avg: 237.4MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▄▃▂▂▃▂▃▃▂▃▁▁▂▂▃▁▃▁▁▁▃▃▁▃▂▁▂▂▄▂▃▂▂▂▄▂▁▄▂▁▃▃▂▁▂▂▃▂▃▂▂▃▂▁▂▁▁▃▃▂▂▁▂▃▃▄▄▂▂▃▁▂▃▂▁▃▂▁▃▁▂▄▂▁▁▁▃▁▄█▃▂▃▁▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,487 | 14,271 | +216 | 14,343 | 84,644 | INCREASING (+3.40/hr) |
| Heap InUse | 261.9MB | 291.4MB | -29.5MB | 237.4MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3331.5MB | 3331.4MB | +0.1MB | 2680.3MB | 6883.9MB | |
| Heap Objects | 994,776 | 1,824,691 | -829915 | 1,019,280 | 17,165,538 | |

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
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 108 | 14,862 | 261.9MB | 490.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 5.89MB |
| 6 | `database/sql.convertAssignRows` | 4.5MB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 4.29MB |
| 8 | `bufio.NewWriterSize` | 3.54MB |
| 9 | `bytes.growSlice` | 3.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 193.71GB |
| 2 | `segmentio/kafka-go.makePartitions` | 191.63GB |
| 3 | `jackskj/carta.getUniqueId` | 174.78GB |
| 4 | `reflect.unsafe_New` | 154.35GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 151.83GB |
| 6 | `fmt.Sprintf` | 140.85GB |
| 7 | `fmt.(*buffer).writeString` | 121.17GB |
| 8 | `carta/value.NewCell` | 110.33GB |
| 9 | `reflect.unsafe_NewArray` | 97.72GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 86.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.52GB | 10.51GB | 10.40GB | 0B |
| `evaluation.mergeMetadata` | 5.49GB | 5.48GB | 5.42GB | 0B |
| `local.(*Client).EvaluateV2` | 16.01GB | 16.00GB | 15.84GB | 0B |
| `local.topologicalSort` | 2.23GB | 2.23GB | 2.20GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.30GB | 15.29GB | 15.12GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.18GB | 2.18GB | 2.17GB | 0B |
| `localEvaluation.getMapOfValue` | 15.30GB | 15.29GB | 15.12GB | 0B |
| `utils.ParseFeatureFlag` | 15.33GB | 15.32GB | 15.15GB | 0B |

**Total FF alloc (current snapshot):** 82.36GB  |  **24h avg:** 81.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3364 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3364 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3015/3364 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.48MB | 3015/3364 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3364 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3364 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.42MB | 2367/3364 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3364 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3364 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3364 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3364 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3364 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3364 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.63GB | 1881/3364 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 63.63GB | 2576/3364 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.9GB | 2738/3364 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.32GB | 2592/3364 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 54.43GB | 2356/3364 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3364 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.37GB | 2103/3364 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
