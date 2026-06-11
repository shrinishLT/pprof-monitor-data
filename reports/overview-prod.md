# Overview: prod
*Last updated: 2026-06-11 06:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T06:05 (3042 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,682 | avg: 14,144 | max: 84,644 | trend: INCREASING (+3.75/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 243.4MB | avg: 230.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▃▂▁▂▂▁▃▂▂▃▂▃▂▂▂▂▂▂▂▁▁▁▃▃▃▂▁▁▁▂▂▂▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▃▂▂▂▂▃▃▂▂▂▂▃▃▄▂▃▃▁▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,682 | 14,174 | +508 | 14,144 | 84,644 | INCREASING (+3.75/hr) |
| Heap InUse | 243.4MB | 253.3MB | -9.9MB | 230.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.2MB | 3344.7MB | -0.5MB | 2611.8MB | 6883.9MB | |
| Heap Objects | 950,803 | 1,351,079 | -400276 | 993,686 | 17,165,538 | |

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
| 2026-06-11 | 74 | 14,895 | 270.5MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.02MB |
| 6 | `bufio.NewWriterSize` | 4.56MB |
| 7 | `bytes.growSlice` | 4.17MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 158.83GB |
| 2 | `segmentio/kafka-go.makePartitions` | 154.51GB |
| 3 | `jackskj/carta.getUniqueId` | 142.99GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 128.68GB |
| 5 | `reflect.unsafe_New` | 126.29GB |
| 6 | `fmt.Sprintf` | 114.0GB |
| 7 | `fmt.(*buffer).writeString` | 100.59GB |
| 8 | `carta/value.NewCell` | 90.12GB |
| 9 | `reflect.unsafe_NewArray` | 78.99GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 74.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.13GB | 8.12GB | 8.00GB | 0B |
| `evaluation.mergeMetadata` | 4.25GB | 4.25GB | 4.19GB | 0B |
| `local.(*Client).EvaluateV2` | 12.39GB | 12.38GB | 12.20GB | 0B |
| `local.topologicalSort` | 1.71GB | 1.71GB | 1.68GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.82GB | 11.81GB | 11.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.70GB | 1.70GB | 1.68GB | 0B |
| `localEvaluation.getMapOfValue` | 11.82GB | 11.81GB | 11.62GB | 0B |
| `utils.ParseFeatureFlag` | 11.84GB | 11.83GB | 11.64GB | 0B |

**Total FF alloc (current snapshot):** 63.65GB  |  **24h avg:** 62.63GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3042 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3042 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2693/3042 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.33MB | 2693/3042 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3042 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3042 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.35MB | 2088/3042 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3042 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3042 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3042 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3042 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3042 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3042 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 57.15GB | 1559/3042 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3042 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 48.21GB | 2416/3042 | `█████░░░░░░░░░░ 38%` |
| 7 | `reflect.growslice` | 47.44GB | 2254/3042 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3042 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 41.57GB | 2270/3042 | `████░░░░░░░░░░░ 33%` |
| 10 | `reflect.unsafe_New` | 40.67GB | 2034/3042 | `████░░░░░░░░░░░ 32%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
