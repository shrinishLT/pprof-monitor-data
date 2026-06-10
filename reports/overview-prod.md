# Overview: prod
*Last updated: 2026-06-10 23:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T23:05 (2958 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,813 | avg: 14,117 | max: 84,644 | trend: INCREASING (+3.96/hr))
```
▁▁▄▂▂▂▂▂▂▂▂▂▁▁▂▂▃▂▂▁▂▂▇▂▁▁▁▁▁▁▁▃▅▁▂▃▄▃▂▂▃▃▂▂▃▃▂▂▂▁▃▁▁▃▁▂▁▁▁█▂▄▅▄▄▅▃▂▁▄▅▃▁▁▃▁▁▁▁▁▁▂▂▂▁▂▂▄▁▁▁▁▂▂▁▂
```

**Heap InUse** (current: 229.4MB | avg: 228.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▂▃▃▅▃▃▃▄▂▂▃▁▃▅▄▅▂▄▂▄▅▅▄▂▁▃▁▃▁▁▃▅▂▃▅▆▆▄▅▄▃▃▂▃▂▅▆▄▄▅▃▂▃▅▄▄▄▁▇▃▄▅▄▄▇▄▂▁▄█▄▄▃▆▅▃▁▂▂▁▃▅▂▂▂▃▅▃▁▁▃▅▄▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,813 | 14,445 | +368 | 14,117 | 84,644 | INCREASING (+3.96/hr) |
| Heap InUse | 229.4MB | 266.4MB | -37.0MB | 228.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.5MB | 3343.6MB | -0.1MB | 2591.3MB | 6883.9MB | |
| Heap Objects | 646,770 | 1,259,394 | -612624 | 988,927 | 17,165,538 | |

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
| 2026-06-10 | 277 | 16,447 | 304.9MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.68MB |
| 6 | `compress/flate.NewWriter` | 5.29MB |
| 7 | `bufio.NewWriterSize` | 2.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `bufio.NewReaderSize` | 2.51MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 144.92GB |
| 2 | `reflect.growslice` | 139.26GB |
| 3 | `jackskj/carta.getUniqueId` | 125.08GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.9GB |
| 5 | `reflect.unsafe_New` | 110.56GB |
| 6 | `fmt.Sprintf` | 99.56GB |
| 7 | `fmt.(*buffer).writeString` | 87.53GB |
| 8 | `carta/value.NewCell` | 79.03GB |
| 9 | `reflect.unsafe_NewArray` | 74.04GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 60.11GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.61GB | 7.61GB | 7.42GB | 0B |
| `evaluation.mergeMetadata` | 3.99GB | 3.99GB | 3.89GB | 0B |
| `local.(*Client).EvaluateV2` | 11.61GB | 11.59GB | 11.32GB | 0B |
| `local.topologicalSort` | 1.61GB | 1.60GB | 1.57GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.03GB | 11.02GB | 10.77GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.63GB | 1.63GB | 1.57GB | 0B |
| `localEvaluation.getMapOfValue` | 11.03GB | 11.02GB | 10.77GB | 0B |
| `utils.ParseFeatureFlag` | 11.05GB | 11.04GB | 10.79GB | 0B |

**Total FF alloc (current snapshot):** 59.57GB  |  **24h avg:** 58.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.57MB | 53/2958 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2958 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2609/2958 | `████████░░░░░░░ 55%` |
| 4 | `runtime.mallocgc` | 29.69MB | 2609/2958 | `██████░░░░░░░░░ 45%` |
| 5 | `database/sql.convertAssignRows` | 28.12MB | 102/2958 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2958 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.57MB | 2014/2958 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2958 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2958 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2958 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2958 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2958 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2958 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.8GB | 1475/2958 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2958 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 44.55GB | 2332/2958 | `█████░░░░░░░░░░ 35%` |
| 7 | `reflect.growslice` | 43.72GB | 2170/2958 | `█████░░░░░░░░░░ 34%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2958 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 38.19GB | 2186/2958 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.unsafe_New` | 37.49GB | 1950/2958 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
