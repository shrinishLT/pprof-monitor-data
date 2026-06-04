# Overview: prod
*Last updated: 2026-06-05 00:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T00:20 (1247 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,425 | avg: 11,493 | max: 84,644 | trend: decreasing (-8.50/hr))
```
▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 174.5MB | avg: 174.3MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▂▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▂▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█▁▁▁▁▁▃▂▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,425 | 14,260 | +165 | 11,493 | 84,644 | decreasing (-8.50/hr) |
| Heap InUse | 174.5MB | 152.5MB | +22.0MB | 174.3MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 799.2MB | 799.5MB | -0.3MB | 2643.9MB | 6883.9MB | |
| Heap Objects | 1,037,682 | 858,901 | +178781 | 758,240 | 14,090,816 | |

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
| 2026-06-05 | 5 | 14,523 | 182.5MB | 208.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.0MB |
| 9 | `reflect.unsafe_New` | 1.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.85GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.75GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.56GB |
| 4 | `fmt.Sprintf` | 1.16GB |
| 5 | `jackskj/carta.getUniqueId` | 1.05GB |
| 6 | `reflect.unsafe_NewArray` | 937.37MB |
| 7 | `reflect.growslice` | 897.93MB |
| 8 | `reflect.unsafe_New` | 783.34MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 721.02MB |
| 10 | `fmt.(*buffer).writeString` | 592.34MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 120.55MB | 114.47MB | 359.34MB | 0B |
| `evaluation.mergeMetadata` | 64.02MB | 61.52MB | 185.84MB | 0B |
| `local.(*Client).EvaluateV2` | 163.94MB | 156.33MB | 557.87MB | 0B |
| `local.topologicalSort` | 21.71MB | 20.70MB | 76.17MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 150.17MB | 143.06MB | 491.79MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 25.57MB | 24.55MB | 114.73MB | 0B |
| `localEvaluation.getMapOfValue` | 150.17MB | 143.06MB | 491.79MB | 0B |
| `utils.ParseFeatureFlag` | 150.17MB | 143.06MB | 492.03MB | 0B |

**Total FF alloc (current snapshot):** 846.28MB  |  **24h avg:** 2.70GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1247 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1247 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 898/1247 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1247 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.08MB | 898/1247 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1247 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.11MB | 678/1247 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1247 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1247 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1247 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1247 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1247 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1247 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1247 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1247 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.05GB | 870/1247 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1247 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.6GB | 793/1247 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.77GB | 485/1247 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 9.92GB | 631/1247 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
