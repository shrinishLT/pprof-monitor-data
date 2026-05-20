# Overview: prod
*Last updated: 2026-05-20 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T23:00 (255 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,415 | avg: 15,698 | max: 84,644 | trend: INCREASING (+11.67/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁
```

**Heap InUse** (current: 189.5MB | avg: 235.5MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▂▁▂▂▁▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,415 | 14,924 | -509 | 15,698 | 84,644 | INCREASING (+11.67/hr) |
| Heap InUse | 189.5MB | 199.0MB | -9.5MB | 235.5MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4659.0MB | 2889.5MB | +1769.5MB | 4303.4MB | 6579.6MB | |
| Heap Objects | 504,382 | 473,085 | +31297 | 996,964 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 47 | 17,047 | 257.6MB | 1004.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 3.02MB |
| 6 | `internal/evaluation.mergeMetadata` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 75.24GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 45.17GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 45.08GB |
| 4 | `experiment/local.topologicalSort` | 29.96GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.67GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 14.3GB |
| 7 | `reflect.growslice` | 8.35GB |
| 8 | `jackskj/carta.getUniqueId` | 7.57GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.23GB |
| 10 | `fmt.Sprintf` | 6.96GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/255 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/255 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 253/255 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/255 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.07MB | 253/255 | `█████░░░░░░░░░░ 38%` |
| 6 | `bytes.growSlice` | 14.01MB | 168/255 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/255 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/255 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/255 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.57MB | 34/255 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.06GB | 244/255 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.91GB | 250/255 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.86GB | 250/255 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 60.14GB | 238/255 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 49.04GB | 232/255 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.86GB | 200/255 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.93GB | 177/255 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/255 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/255 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 19.24GB | 100/255 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
