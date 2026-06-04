# Overview: prod
*Last updated: 2026-06-04 07:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T07:05 (1040 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,873 | avg: 10,401 | max: 84,644 | trend: decreasing (-29.46/hr))
```
▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅▅▅▅▅▅▄▄▄▄▅
```

**Heap InUse** (current: 432.4MB | avg: 155.9MB | max: 2823.8MB | trend: stable (-0.42MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,873 | 14,265 | +608 | 10,401 | 84,644 | decreasing (-29.46/hr) |
| Heap InUse | 432.4MB | 122.2MB | +310.2MB | 155.9MB | 2823.8MB | stable (-0.42MB/hr) |
| Heap Sys | 4134.8MB | 2735.2MB | +1399.6MB | 2548.7MB | 6883.9MB | |
| Heap Objects | 1,496,588 | 378,468 | +1118120 | 668,789 | 14,090,816 | |

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
| 2026-06-04 | 86 | 15,425 | 257.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 27.53MB |
| 3 | `database/sql.convertAssignRows` | 18.0MB |
| 4 | `runtime.mallocgc` | 12.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.58MB |
| 7 | `bufio.NewReaderSize` | 5.03MB |
| 8 | `bytes.growSlice` | 5.03MB |
| 9 | `bufio.NewWriterSize` | 4.03MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.2GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.7GB |
| 3 | `reflect.growslice` | 6.19GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.94GB |
| 6 | `jackskj/carta.getUniqueId` | 4.94GB |
| 7 | `database/sql.convertAssignRows` | 4.88GB |
| 8 | `reflect.unsafe_New` | 4.55GB |
| 9 | `fmt.(*buffer).writeString` | 3.64GB |
| 10 | `carta/value.NewCell` | 3.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 107.34MB | 97.21MB | 76.72MB | 0B |
| `evaluation.mergeMetadata` | 62.52MB | 56.01MB | 41.48MB | 0B |
| `local.(*Client).EvaluateV2` | 164.29MB | 148.45MB | 115.51MB | 0B |
| `local.topologicalSort` | 22.75MB | 20.22MB | 16.58MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 161.68MB | 148.36MB | 114.07MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 20.00MB | 16.95MB | 10.96MB | 0B |
| `localEvaluation.getMapOfValue` | 161.68MB | 148.36MB | 114.07MB | 0B |
| `utils.ParseFeatureFlag` | 162.18MB | 148.86MB | 114.10MB | 0B |

**Total FF alloc (current snapshot):** 862.42MB  |  **24h avg:** 603.49MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.64MB | 35/1040 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.47MB | 20/1040 | `█████████████░░ 92%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 691/1040 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.78MB | 43/1040 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 21.04MB | 691/1040 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1040 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 13.17MB | 494/1040 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1040 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1040 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.58MB | 23/1040 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1040 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1040 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1040 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1040 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1040 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.78GB | 664/1040 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1040 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.6GB | 595/1040 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1040 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1040 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.1x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
