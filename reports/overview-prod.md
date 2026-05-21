# Overview: prod
*Last updated: 2026-05-21 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T18:31 (308 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,507 | avg: 15,720 | max: 84,644 | trend: INCREASING (+7.43/hr))
```
▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 306.9MB | avg: 238.7MB | max: 1896.6MB | trend: stable (+0.28MB/hr))
```
▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,507 | 15,484 | +23 | 15,720 | 84,644 | INCREASING (+7.43/hr) |
| Heap InUse | 306.9MB | 206.5MB | +100.4MB | 238.7MB | 1896.6MB | stable (+0.28MB/hr) |
| Heap Sys | 4879.5MB | 4879.5MB | +0.0MB | 4243.8MB | 6579.6MB | |
| Heap Objects | 1,505,105 | 605,518 | +899587 | 1,004,851 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 52 | 15,811 | 254.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `bytes.growSlice` | 14.57MB |
| 4 | `internal/evaluation.mergeMetadata` | 11.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.45MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 5.23MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.11MB |
| 10 | `experiment/local.topologicalSort` | 4.05MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 157.87GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 94.68GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 94.66GB |
| 4 | `experiment/local.topologicalSort` | 62.45GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.52GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 29.95GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 24.89GB |
| 8 | `fmt.Sprintf` | 16.09GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 11.45GB |
| 10 | `segmentio/kafka-go.makePartitions` | 11.09GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/308 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/308 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 306/308 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/308 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.57MB | 306/308 | `██████░░░░░░░░░ 42%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/308 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/308 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.52MB | 217/308 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/308 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/308 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.91GB | 297/308 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.64GB | 303/308 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.62GB | 303/308 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.75GB | 284/308 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 46.96GB | 285/308 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.95GB | 253/308 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.55GB | 229/308 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.24GB | 249/308 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/308 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.51GB | 152/308 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
