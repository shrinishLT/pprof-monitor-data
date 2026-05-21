# Overview: prod
*Last updated: 2026-05-21 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T09:30 (281 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,005 | avg: 15,656 | max: 84,644 | trend: INCREASING (+7.00/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.0MB | avg: 234.7MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,005 | 14,511 | +494 | 15,656 | 84,644 | INCREASING (+7.00/hr) |
| Heap InUse | 161.0MB | 126.7MB | +34.3MB | 234.7MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 3770.3MB | 3771.2MB | -0.9MB | 4222.3MB | 6579.6MB | |
| Heap Objects | 571,637 | 357,085 | +214552 | 993,299 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 25 | 15,196 | 226.5MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bufio.NewReaderSize` | 5.02MB |
| 6 | `bytes.growSlice` | 4.02MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 117.74GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 71.33GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 70.98GB |
| 4 | `experiment/local.topologicalSort` | 47.41GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 38.53GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 37.45GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 22.6GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96GB |
| 9 | `reflect.growslice` | 12.31GB |
| 10 | `jackskj/carta.getUniqueId` | 10.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/281 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/281 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 279/281 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/281 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.69MB | 279/281 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/281 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/281 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.5MB | 190/281 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.78MB | 41/281 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/281 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.95GB | 270/281 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.77GB | 276/281 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.75GB | 276/281 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.24GB | 259/281 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 47.99GB | 258/281 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.32GB | 226/281 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.72GB | 202/281 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.13GB | 235/281 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/281 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/281 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
