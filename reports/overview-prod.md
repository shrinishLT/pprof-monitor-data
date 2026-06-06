# Overview: prod
*Last updated: 2026-06-06 09:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T09:51 (1648 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,232 | avg: 12,563 | max: 84,644 | trend: INCREASING (+2.15/hr))
```
▂▄▂▃▂█▄▁▁▂▁▁▁▇▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▂▃▃▁▁▁▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 192.7MB | avg: 189.3MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▄▅▂▃▂█▆▃▂▂▃▁▂▆▅▃▂▃▁▂▂▃▂▁▁▁▂▂▁▂▁▁▄▄▁▁▁▁▂▃▂▄▅▁▂▁▁▁▁▂▃▂▂▂▂▃▁▁▂▃▁▁▁▁▂▁▂▂▁▁▁▃▁▂▂▁▂▁▁▁▁▂▁▂▁▂▂▂▁▁▁▁▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,232 | 14,413 | -181 | 12,563 | 84,644 | INCREASING (+2.15/hr) |
| Heap InUse | 192.7MB | 203.0MB | -10.3MB | 189.3MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 1048.7MB | 1048.8MB | -0.1MB | 2435.6MB | 6883.9MB | |
| Heap Objects | 1,070,265 | 1,083,679 | -13414 | 837,624 | 17,165,538 | |

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
| 2026-06-06 | 119 | 15,650 | 226.4MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 9 | `reflect.unsafe_NewArray` | 2.01MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 31.23GB |
| 2 | `segmentio/kafka-go.makePartitions` | 30.62GB |
| 3 | `reflect.growslice` | 30.59GB |
| 4 | `jackskj/carta.getUniqueId` | 28.44GB |
| 5 | `reflect.unsafe_New` | 24.74GB |
| 6 | `fmt.(*buffer).writeString` | 20.49GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.17GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 19.75GB |
| 9 | `carta/value.NewCell` | 17.51GB |
| 10 | `reflect.unsafe_NewArray` | 15.63GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.60GB | 1.60GB | 1.51GB | 0B |
| `evaluation.mergeMetadata` | 844.71MB | 843.21MB | 801.77MB | 0B |
| `local.(*Client).EvaluateV2` | 2.45GB | 2.44GB | 2.32GB | 0B |
| `local.topologicalSort` | 351.23MB | 350.22MB | 335.60MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.36GB | 2.36GB | 2.23GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 314.84MB | 0B |
| `localEvaluation.getMapOfValue` | 2.36GB | 2.36GB | 2.23GB | 0B |
| `utils.ParseFeatureFlag` | 2.37GB | 2.36GB | 2.23GB | 0B |

**Total FF alloc (current snapshot):** 12.62GB  |  **24h avg:** 11.93GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1648 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1648 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1648 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1299/1648 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1648 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.02MB | 1299/1648 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.61MB | 1017/1648 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1648 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1648 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1648 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1648 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1648 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1648 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1648 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1648 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1648 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1648 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1648 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.83GB | 832/1648 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.44GB | 359/1648 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
