# Overview: prod
*Last updated: 2026-05-22 00:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T00:02 (326 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,144 | avg: 15,769 | max: 84,644 | trend: INCREASING (+7.90/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 252.9MB | avg: 241.9MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,144 | 14,126 | +18 | 15,769 | 84,644 | INCREASING (+7.90/hr) |
| Heap InUse | 252.9MB | 169.5MB | +83.4MB | 241.9MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 4886.0MB | 4886.1MB | -0.1MB | 4279.0MB | 6579.6MB | |
| Heap Objects | 1,431,999 | 593,193 | +838806 | 1,014,034 | 8,100,802 | |

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
| 2026-05-22 | 2 | 14,135 | 211.2MB | 252.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `kafka-go/protocol.newPage` | 1.6MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 260.29GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 156.09GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 155.76GB |
| 4 | `experiment/local.topologicalSort` | 103.19GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 81.38GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 49.46GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 44.51GB |
| 8 | `fmt.Sprintf` | 27.44GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 20.58GB |
| 10 | `segmentio/kafka-go.makePartitions` | 18.53GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/326 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/326 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 324/326 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/326 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.17MB | 324/326 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 13.86MB | 233/326 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/326 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/326 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/326 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.53MB | 47/326 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.27GB | 315/326 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.41GB | 321/326 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.4GB | 321/326 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.67GB | 302/326 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 49.47GB | 303/326 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.91GB | 271/326 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.74GB | 247/326 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.65GB | 265/326 | `███░░░░░░░░░░░░ 21%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/326 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.78GB | 150/326 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
