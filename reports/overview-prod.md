# Overview: prod
*Last updated: 2026-05-22 16:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T16:30 (360 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,500 | avg: 15,810 | max: 84,644 | trend: INCREASING (+7.15/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.4MB | avg: 242.1MB | max: 1896.6MB | trend: stable (+0.26MB/hr))
```
▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,500 | 17,585 | -3085 | 15,810 | 84,644 | INCREASING (+7.15/hr) |
| Heap InUse | 132.4MB | 324.8MB | -192.4MB | 242.1MB | 1896.6MB | stable (+0.26MB/hr) |
| Heap Sys | 5050.8MB | 5054.0MB | -3.2MB | 4301.2MB | 6579.6MB | |
| Heap Objects | 373,233 | 1,702,599 | -1329366 | 1,010,874 | 8,100,802 | |

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
| 2026-05-22 | 36 | 16,091 | 241.7MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.growslice` | 1.51MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 114.56GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 68.64GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 68.61GB |
| 4 | `experiment/local.topologicalSort` | 45.63GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.8GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 22.83GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 21.89GB |
| 8 | `fmt.Sprintf` | 11.01GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 8.66GB |
| 10 | `internal/evaluation.coerceString` | 7.47GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/360 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/360 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 358/360 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/360 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.34MB | 358/360 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.09MB | 257/360 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/360 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/360 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/360 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/360 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.17GB | 349/360 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.07GB | 355/360 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.05GB | 355/360 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.59GB | 337/360 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.5GB | 336/360 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.93GB | 305/360 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.2GB | 281/360 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.09GB | 295/360 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/360 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.56GB | 181/360 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
