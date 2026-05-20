# Overview: prod
*Last updated: 2026-05-20 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T22:31 (254 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,924 | avg: 15,703 | max: 84,644 | trend: INCREASING (+12.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁
```

**Heap InUse** (current: 199.0MB | avg: 235.7MB | max: 1896.6MB | trend: stable (+0.32MB/hr))
```
▂▂▁▂▂▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,924 | 48,719 | -33795 | 15,703 | 84,644 | INCREASING (+12.05/hr) |
| Heap InUse | 199.0MB | 1004.2MB | -805.2MB | 235.7MB | 1896.6MB | stable (+0.32MB/hr) |
| Heap Sys | 2889.5MB | 2812.8MB | +76.7MB | 4302.0MB | 6579.6MB | |
| Heap Objects | 473,085 | 3,352,310 | -2879225 | 998,904 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 46 | 17,104 | 259.1MB | 1004.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 6.5MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 4.77MB |
| 7 | `experiment/local.topologicalSort` | 4.06MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.59MB |
| 10 | `bytes.growSlice` | 3.08MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 72.69GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 43.65GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 43.59GB |
| 4 | `experiment/local.topologicalSort` | 28.98GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.92GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 13.84GB |
| 7 | `reflect.growslice` | 8.29GB |
| 8 | `jackskj/carta.getUniqueId` | 7.5GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.22GB |
| 10 | `reflect.unsafe_New` | 6.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/254 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/254 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 252/254 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/254 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.02MB | 252/254 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 14.08MB | 167/254 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/254 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/254 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 33/254 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/254 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.23GB | 243/254 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.01GB | 249/254 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.96GB | 249/254 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/254 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.13GB | 231/254 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.96GB | 199/254 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.01GB | 176/254 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/254 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/254 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.37GB | 99/254 | `██░░░░░░░░░░░░░ 16%` |

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
