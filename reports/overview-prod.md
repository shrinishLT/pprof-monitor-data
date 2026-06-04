# Overview: prod
*Last updated: 2026-06-04 06:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T06:25 (1032 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,907 | avg: 10,370 | max: 84,644 | trend: decreasing (-30.52/hr))
```
▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅▅▅▅▅▅▅▄▄▄▅▅▅▅▅
```

**Heap InUse** (current: 182.2MB | avg: 155.2MB | max: 2823.8MB | trend: stable (-0.43MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,907 | 14,675 | +232 | 10,370 | 84,644 | decreasing (-30.52/hr) |
| Heap InUse | 182.2MB | 361.5MB | -179.3MB | 155.2MB | 2823.8MB | stable (-0.43MB/hr) |
| Heap Sys | 2249.8MB | 2250.3MB | -0.5MB | 2546.8MB | 6883.9MB | |
| Heap Objects | 579,505 | 2,008,096 | -1428591 | 664,867 | 14,090,816 | |

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
| 2026-06-04 | 78 | 15,527 | 259.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.14MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.24MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `database/sql.convertAssignRows` | 23.5MB |
| 5 | `runtime.mallocgc` | 12.6MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bytes.growSlice` | 4.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `bufio.NewWriterSize` | 3.03MB |
| 10 | `bufio.NewReaderSize` | 3.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 26.25GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 10.33GB |
| 3 | `reflect.growslice` | 6.12GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.02GB |
| 5 | `jackskj/carta.getUniqueId` | 4.87GB |
| 6 | `reflect.unsafe_New` | 4.49GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.96GB |
| 8 | `fmt.(*buffer).writeString` | 3.61GB |
| 9 | `carta/value.NewCell` | 3.16GB |
| 10 | `database/sql.convertAssignRows` | 3.06GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 64.27MB | 56.72MB | 76.13MB | 0B |
| `evaluation.mergeMetadata` | 36.01MB | 32.51MB | 40.24MB | 0B |
| `local.(*Client).EvaluateV2` | 94.87MB | 82.20MB | 116.07MB | 0B |
| `local.topologicalSort` | 11.62MB | 8.08MB | 17.66MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 93.28MB | 82.64MB | 113.57MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 13.85MB | 11.81MB | 10.63MB | 0B |
| `localEvaluation.getMapOfValue` | 93.28MB | 82.64MB | 113.57MB | 0B |
| `utils.ParseFeatureFlag` | 93.28MB | 82.64MB | 113.57MB | 0B |

**Total FF alloc (current snapshot):** 500.45MB  |  **24h avg:** 601.43MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.2MB | 32/1032 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 61.74MB | 19/1032 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 683/1032 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.29MB | 40/1032 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.14MB | 683/1032 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1032 | `████░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.29MB | 488/1032 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1032 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1032 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.44MB | 20/1032 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1032 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1032 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1032 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1032 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1032 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.87GB | 656/1032 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1032 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.68GB | 587/1032 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1032 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1032 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
