# Overview: prod
*Last updated: 2026-05-23 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T09:31 (394 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,816 | avg: 15,790 | max: 84,644 | trend: INCREASING (+4.79/hr))
```
▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 231.7MB | avg: 238.5MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,816 | 14,586 | +230 | 15,790 | 84,644 | INCREASING (+4.79/hr) |
| Heap InUse | 231.7MB | 146.2MB | +85.5MB | 238.5MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4213.6MB | 4213.5MB | +0.1MB | 4226.2MB | 6579.6MB | |
| Heap Objects | 1,275,767 | 569,098 | +706669 | 995,049 | 8,100,802 | |

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
| 2026-05-23 | 20 | 14,941 | 190.7MB | 359.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `experiment/local.topologicalSort` | 14.69MB |
| 3 | `internal/evaluation.mergeMetadata` | 14.0MB |
| 4 | `runtime.mallocgc` | 9.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.35MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 6.37MB |
| 8 | `bytes.growSlice` | 6.03MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.13MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 70.62GB |
| 2 | `internal/evaluation.mergeMetadata` | 70.56GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 42.19GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 41.88GB |
| 5 | `experiment/local.topologicalSort` | 28.04GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 26.78GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.96GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 13.42GB |
| 9 | `reflect.growslice` | 12.78GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/394 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.79MB | 16/394 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 392/394 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 20/394 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.07MB | 392/394 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.92MB | 281/394 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/394 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/394 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/394 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/394 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.44GB | 383/394 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.58GB | 389/394 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.55GB | 389/394 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.27GB | 371/394 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.89GB | 370/394 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.67GB | 339/394 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.15GB | 312/394 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.51GB | 327/394 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/394 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/394 | `██░░░░░░░░░░░░░ 14%` |

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
