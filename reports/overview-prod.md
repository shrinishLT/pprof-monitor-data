# Overview: prod
*Last updated: 2026-05-21 08:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T08:00 (276 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,149 | avg: 15,677 | max: 84,644 | trend: INCREASING (+8.28/hr))
```
▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.9MB | avg: 236.3MB | max: 1896.6MB | trend: stable (+0.27MB/hr))
```
▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,149 | 14,237 | -88 | 15,677 | 84,644 | INCREASING (+8.28/hr) |
| Heap InUse | 159.9MB | 143.5MB | +16.4MB | 236.3MB | 1896.6MB | stable (+0.27MB/hr) |
| Heap Sys | 3205.5MB | 3205.4MB | +0.1MB | 4234.6MB | 6579.6MB | |
| Heap Objects | 883,771 | 695,024 | +188747 | 1,002,250 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 20 | 15,360 | 247.1MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 104.29GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 63.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 62.77GB |
| 4 | `experiment/local.topologicalSort` | 41.98GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.79GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.17GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 20.04GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.76GB |
| 9 | `reflect.growslice` | 11.24GB |
| 10 | `jackskj/carta.getUniqueId` | 8.96GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/276 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/276 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 274/276 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/276 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.91MB | 274/276 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.72MB | 186/276 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/276 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/276 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.88MB | 40/276 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/276 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.07GB | 265/276 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.82GB | 271/276 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.79GB | 271/276 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.64GB | 254/276 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.06GB | 253/276 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.49GB | 221/276 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.88GB | 197/276 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.35GB | 230/276 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/276 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.13GB | 112/276 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
