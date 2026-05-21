# Overview: prod
*Last updated: 2026-05-21 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T07:31 (275 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,237 | avg: 15,682 | max: 84,644 | trend: INCREASING (+8.61/hr))
```
▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 143.5MB | avg: 236.6MB | max: 1896.6MB | trend: stable (+0.28MB/hr))
```
▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,237 | 14,243 | -6 | 15,682 | 84,644 | INCREASING (+8.61/hr) |
| Heap InUse | 143.5MB | 140.3MB | +3.2MB | 236.6MB | 1896.6MB | stable (+0.28MB/hr) |
| Heap Sys | 3205.4MB | 3205.4MB | +0.0MB | 4238.3MB | 6579.6MB | |
| Heap Objects | 695,024 | 629,303 | +65721 | 1,002,681 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 19 | 15,424 | 251.7MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 9 | `bytes.growSlice` | 1.01MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 103.5GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 62.74GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 62.31GB |
| 4 | `experiment/local.topologicalSort` | 41.66GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.76GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 32.94GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 19.88GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.74GB |
| 9 | `reflect.growslice` | 11.16GB |
| 10 | `jackskj/carta.getUniqueId` | 8.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/275 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/275 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 273/275 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/275 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.96MB | 273/275 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.78MB | 185/275 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/275 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/275 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.88MB | 40/275 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/275 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.11GB | 264/275 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.85GB | 270/275 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.81GB | 270/275 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.74GB | 253/275 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.08GB | 252/275 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.53GB | 220/275 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.92GB | 196/275 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.4GB | 229/275 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/275 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.13GB | 112/275 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
