# Overview: prod
*Last updated: 2026-06-06 09:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T09:45 (1647 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,413 | avg: 12,562 | max: 84,644 | trend: INCREASING (+2.14/hr))
```
▁▂▄▂▃▂█▄▁▁▂▁▁▁▇▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▂▃▃▁▁▁▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 203.0MB | avg: 189.3MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▄▅▂▃▂█▆▃▂▂▃▁▂▆▅▃▂▃▁▂▂▃▂▁▁▁▂▂▁▂▁▁▄▄▁▁▁▁▂▃▂▄▅▁▂▁▁▁▁▂▃▂▂▂▂▃▁▁▂▃▁▁▁▁▂▁▂▂▁▁▁▃▁▂▂▁▂▁▁▁▁▂▁▂▁▂▂▂▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,413 | 14,508 | -95 | 12,562 | 84,644 | INCREASING (+2.14/hr) |
| Heap InUse | 203.0MB | 221.1MB | -18.1MB | 189.3MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 1048.8MB | 1048.2MB | +0.6MB | 2436.5MB | 6883.9MB | |
| Heap Objects | 1,083,679 | 1,137,039 | -53360 | 837,483 | 17,165,538 | |

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
| 2026-06-06 | 118 | 15,662 | 226.6MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.05MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 31.2GB |
| 2 | `segmentio/kafka-go.makePartitions` | 30.49GB |
| 3 | `reflect.growslice` | 30.48GB |
| 4 | `jackskj/carta.getUniqueId` | 28.34GB |
| 5 | `reflect.unsafe_New` | 24.65GB |
| 6 | `fmt.(*buffer).writeString` | 20.43GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.15GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 19.75GB |
| 9 | `carta/value.NewCell` | 17.44GB |
| 10 | `reflect.unsafe_NewArray` | 15.57GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.60GB | 1.59GB | 1.51GB | 0B |
| `evaluation.mergeMetadata` | 843.21MB | 841.21MB | 799.77MB | 0B |
| `local.(*Client).EvaluateV2` | 2.44GB | 2.44GB | 2.31GB | 0B |
| `local.topologicalSort` | 350.22MB | 349.72MB | 334.87MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.36GB | 2.35GB | 2.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 314.54MB | 0B |
| `localEvaluation.getMapOfValue` | 2.36GB | 2.35GB | 2.22GB | 0B |
| `utils.ParseFeatureFlag` | 2.36GB | 2.36GB | 2.22GB | 0B |

**Total FF alloc (current snapshot):** 12.59GB  |  **24h avg:** 11.90GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1647 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1647 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1647 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1298/1647 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1647 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.02MB | 1298/1647 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.61MB | 1017/1647 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1647 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1647 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1647 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1647 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1647 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1647 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1647 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1647 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1647 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1647 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1647 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.8GB | 831/1647 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.42GB | 358/1647 | `█░░░░░░░░░░░░░░ 9%` |

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
