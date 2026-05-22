# Overview: prod
*Last updated: 2026-05-22 21:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T21:01 (369 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,259 | avg: 15,809 | max: 84,644 | trend: INCREASING (+6.60/hr))
```
▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 158.9MB | avg: 241.0MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,259 | 15,474 | -1215 | 15,809 | 84,644 | INCREASING (+6.60/hr) |
| Heap InUse | 158.9MB | 175.1MB | -16.2MB | 241.0MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 2903.1MB | 2902.4MB | +0.7MB | 4287.1MB | 6579.6MB | |
| Heap Objects | 776,352 | 591,315 | +185037 | 1,005,615 | 8,100,802 | |

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
| 2026-05-22 | 45 | 16,026 | 233.2MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `database/sql.convertAssignRows` | 4.0MB |
| 6 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.8MB |
| 8 | `reflect.mapassign_faststr0` | 3.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 24.09GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 14.62GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 14.62GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 12.9GB |
| 5 | `experiment/local.topologicalSort` | 9.64GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 7.41GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 4.94GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 4.69GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.03GB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.97GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/369 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/369 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 367/369 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/369 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.97MB | 367/369 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.99MB | 265/369 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/369 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/369 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/369 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.37MB | 57/369 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 131.48GB | 358/369 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 78.1GB | 364/369 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 78.08GB | 364/369 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.86GB | 346/369 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.59GB | 345/369 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.18GB | 314/369 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.65GB | 290/369 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.53GB | 304/369 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/369 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.22GB | 187/369 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
