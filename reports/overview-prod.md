# Overview: prod
*Last updated: 2026-05-22 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T11:30 (350 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,251 | avg: 15,823 | max: 84,644 | trend: INCREASING (+8.21/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

**Heap InUse** (current: 156.5MB | avg: 243.2MB | max: 1896.6MB | trend: stable (+0.32MB/hr))
```
▁▂▁▁▂▂▁▄▂▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,251 | 14,452 | +799 | 15,823 | 84,644 | INCREASING (+8.21/hr) |
| Heap InUse | 156.5MB | 182.8MB | -26.3MB | 243.2MB | 1896.6MB | stable (+0.32MB/hr) |
| Heap Sys | 986.7MB | 5041.3MB | -4054.6MB | 4314.6MB | 6579.6MB | |
| Heap Objects | 615,509 | 322,414 | +293095 | 1,012,957 | 8,100,802 | |

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
| 2026-05-22 | 26 | 16,365 | 257.1MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.01MB |
| 4 | `internal/evaluation.mergeMetadata` | 7.0MB |
| 5 | `bytes.growSlice` | 6.53MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.27MB |
| 7 | `bufio.NewWriterSize` | 5.54MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.13MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.08GB |
| 2 | `internal/evaluation.mergeMetadata` | 3.03GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 1.85GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 1.75GB |
| 5 | `experiment/local.topologicalSort` | 1.19GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 935.0MB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 634.87MB |
| 9 | `reflect.growslice` | 593.85MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 584.04MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/350 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/350 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 348/350 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/350 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.8MB | 348/350 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 14.29MB | 247/350 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/350 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/350 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.9MB | 51/350 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/350 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 135.19GB | 339/350 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 80.24GB | 345/350 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 80.22GB | 345/350 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 55.47GB | 327/350 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 54.72GB | 326/350 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.84GB | 295/350 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.86GB | 271/350 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.49GB | 289/350 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/350 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `fmt.Sprintf` | 20.13GB | 173/350 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
