# Overview: prod
*Last updated: 2026-06-13 20:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T20:00 (3785 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,429 | avg: 14,600 | max: 84,644 | trend: INCREASING (+3.09/hr))
```
▂▁▁▁▂█▄▄▅▄▃▂▂▄▂▂▂▁▁▁▄▂▁▁▂▂▁▁▂▃▂▁▂▂▅▃▂▆▁▁▂▁▂▁▂▁▁▃▃▁▁▁▁▁▆▁▁▁▁▁▂▁▁▁▃▁▃▁▁▃▄▁▃▃▂▅▇▁▁▁▄▁▁▁▂▁▁▁▄▄▁▁▁▁▁▃
```

**Heap InUse** (current: 239.2MB | avg: 240.4MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▅▂▂▄▆▇▇▃▅▃▃▄▆▄▂▂▂▂▃▂▃▂▅▂▅▆▃▂▄▁▁▃▄▄▅▆▂▇▅▂▁▅▄▆▃▂▄▄▇▁▃▄▆▁▄▁▆▁▂▅▄▁▂▁▄▅▇▁▂▂▆▂▃▄▁▃▄▂▂▃▃▁▄▂▆▅▁▅█▃▁▂▅▅▁▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,429 | 14,140 | +289 | 14,600 | 84,644 | INCREASING (+3.09/hr) |
| Heap InUse | 239.2MB | 167.5MB | +71.7MB | 240.4MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2272.1MB | 2272.0MB | +0.1MB | 2548.2MB | 6883.9MB | |
| Heap Objects | 1,193,215 | 590,727 | +602488 | 1,036,563 | 17,165,538 | |

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
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 241 | 16,452 | 267.5MB | 1566.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewReaderSize` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `bytes.growSlice` | 1.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 43.63GB |
| 2 | `reflect.growslice` | 39.95GB |
| 3 | `jackskj/carta.getUniqueId` | 35.89GB |
| 4 | `reflect.unsafe_New` | 32.09GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 30.33GB |
| 6 | `fmt.Sprintf` | 25.18GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 24.95GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 23.51GB |
| 9 | `fmt.(*buffer).writeString` | 23.48GB |
| 10 | `carta/value.NewCell` | 23.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.96GB | 1.96GB | 1.90GB | 0B |
| `evaluation.mergeMetadata` | 1.01GB | 1.01GB | 1006.23MB | 0B |
| `local.(*Client).EvaluateV2` | 3.01GB | 3.01GB | 2.92GB | 0B |
| `local.topologicalSort` | 428.41MB | 428.41MB | 415.60MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.92GB | 2.92GB | 2.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 380.79MB | 380.79MB | 369.78MB | 0B |
| `localEvaluation.getMapOfValue` | 2.92GB | 2.92GB | 2.84GB | 0B |
| `utils.ParseFeatureFlag` | 2.93GB | 2.93GB | 2.84GB | 0B |

**Total FF alloc (current snapshot):** 15.54GB  |  **24h avg:** 15.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3785 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.38MB | 103/3785 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3436/3785 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.24MB | 3436/3785 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.7MB | 125/3785 | `███████░░░░░░░░ 49%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3785 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.83MB | 2704/3785 | `████░░░░░░░░░░░ 32%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 13.5MB | 5/3785 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.43MB | 99/3785 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3785 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3785 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3785 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3785 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.87GB | 2004/3785 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 59.48GB | 2997/3785 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.34GB | 3159/3785 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.78GB | 3013/3785 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3785 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.35GB | 2777/3785 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.49GB | 2359/3785 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
