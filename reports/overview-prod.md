# Overview: prod
*Last updated: 2026-05-21 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T04:31 (266 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,086 | avg: 15,707 | max: 84,644 | trend: INCREASING (+10.70/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 342.1MB | avg: 237.4MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,086 | 14,933 | +1153 | 15,707 | 84,644 | INCREASING (+10.70/hr) |
| Heap InUse | 342.1MB | 211.3MB | +130.8MB | 237.4MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 3978.7MB | 730.1MB | +3248.6MB | 4291.6MB | 6579.6MB | |
| Heap Objects | 1,977,990 | 1,034,577 | +943413 | 1,000,467 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 10 | 15,856 | 285.8MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 15.5MB |
| 3 | `runtime.mallocgc` | 14.61MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 8.49MB |
| 6 | `bytes.growSlice` | 6.03MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 5.21MB |
| 8 | `experiment/local.topologicalSort` | 4.05MB |
| 9 | `bufio.NewReaderSize` | 4.02MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.59MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 64.61GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 38.83GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 38.63GB |
| 4 | `experiment/local.topologicalSort` | 25.69GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 20.42GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 12.23GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 6.46GB |
| 8 | `fmt.Sprintf` | 5.35GB |
| 9 | `internal/evaluation.coerceString` | 4.18GB |
| 10 | `internal/evaluation.(*Engine).bucket` | 3.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/266 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/266 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 264/266 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/266 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.37MB | 264/266 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.96MB | 179/266 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/266 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/266 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.8MB | 38/266 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/266 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.69GB | 255/266 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.15GB | 261/266 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.1GB | 261/266 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 58.57GB | 246/266 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.38GB | 243/266 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.99GB | 211/266 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.35GB | 187/266 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.73GB | 223/266 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/266 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.31GB | 110/266 | `██░░░░░░░░░░░░░ 15%` |

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
