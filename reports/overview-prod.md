# Overview: prod
*Last updated: 2026-05-21 01:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T01:00 (259 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,436 | avg: 15,692 | max: 84,644 | trend: INCREASING (+10.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁
```

**Heap InUse** (current: 297.3MB | avg: 235.6MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,436 | 15,154 | -718 | 15,692 | 84,644 | INCREASING (+10.88/hr) |
| Heap InUse | 297.3MB | 220.9MB | +76.4MB | 235.6MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4837.7MB | 4663.3MB | +174.4MB | 4309.6MB | 6579.6MB | |
| Heap Objects | 1,425,587 | 611,242 | +814345 | 993,499 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 3 | 14,915 | 245.3MB | 297.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 10.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `experiment/local.topologicalSort` | 6.06MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 4.71MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 3.74MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.58MB |
| 10 | `bytes.growSlice` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 93.16GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 55.99GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 55.91GB |
| 4 | `experiment/local.topologicalSort` | 37.13GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.37GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 17.77GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 11.11GB |
| 8 | `fmt.Sprintf` | 8.96GB |
| 9 | `reflect.growslice` | 8.55GB |
| 10 | `jackskj/carta.getUniqueId` | 7.84GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/259 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/259 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 257/259 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/259 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.28MB | 257/259 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.88MB | 172/259 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/259 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/259 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/259 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.57MB | 35/259 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.55GB | 248/259 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.63GB | 254/259 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.57GB | 254/259 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.94GB | 239/259 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.8GB | 236/259 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.53GB | 204/259 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.65GB | 181/259 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/259 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/259 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.82GB | 104/259 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
