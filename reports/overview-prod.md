# Overview: prod
*Last updated: 2026-05-21 04:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T04:00 (265 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,933 | avg: 15,706 | max: 84,644 | trend: INCREASING (+10.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 211.3MB | avg: 237.0MB | max: 1896.6MB | trend: stable (+0.34MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,933 | 16,618 | -1685 | 15,706 | 84,644 | INCREASING (+10.75/hr) |
| Heap InUse | 211.3MB | 224.0MB | -12.7MB | 237.0MB | 1896.6MB | stable (+0.34MB/hr) |
| Heap Sys | 730.1MB | 747.3MB | -17.2MB | 4292.8MB | 6579.6MB | |
| Heap Objects | 1,034,577 | 884,893 | +149684 | 996,778 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 9 | 15,831 | 279.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.61MB |
| 3 | `internal/evaluation.mergeMetadata` | 12.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `experiment/local.topologicalSort` | 9.1MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 6.81MB |
| 7 | `bytes.growSlice` | 6.03MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 3.67MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 15.11GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 9.12GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 9.12GB |
| 4 | `experiment/local.topologicalSort` | 6.13GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.76GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 2.88GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 1.73GB |
| 8 | `fmt.Sprintf` | 1.35GB |
| 9 | `jackskj/carta.getUniqueId` | 1.06GB |
| 10 | `internal/evaluation.coerceString` | 1019.52MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/265 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/265 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 263/265 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/265 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.4MB | 263/265 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 14.0MB | 178/265 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/265 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/265 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/265 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.68MB | 37/265 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.89GB | 254/265 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.27GB | 260/265 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.21GB | 260/265 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 58.78GB | 245/265 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.47GB | 242/265 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.1GB | 210/265 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.43GB | 186/265 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.73GB | 223/265 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/265 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.43GB | 109/265 | `██░░░░░░░░░░░░░ 15%` |

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
