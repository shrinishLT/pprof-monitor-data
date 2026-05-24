# Overview: prod
*Last updated: 2026-05-24 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T15:30 (454 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,268 | avg: 15,660 | max: 84,644 | trend: stable (+0.18/hr))
```
▂▁▂▁▂▂▁▁▂▁▁▁▂▃▁▅▄▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 689.3MB | avg: 232.3MB | max: 1896.6MB | trend: stable (-0.07MB/hr))
```
▃▁▃▁▂▂▁▂▁▁▁▁▃▃▁▃▃▂▁▂▂▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,268 | 14,211 | +57 | 15,660 | 84,644 | stable (+0.18/hr) |
| Heap InUse | 689.3MB | 135.9MB | +553.4MB | 232.3MB | 1896.6MB | stable (-0.07MB/hr) |
| Heap Sys | 3533.3MB | 2380.9MB | +1152.4MB | 4185.6MB | 6883.9MB | |
| Heap Objects | 3,063,355 | 710,147 | +2353208 | 991,161 | 8,100,802 | |

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
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 32 | 14,963 | 216.1MB | 689.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 126.65MB |
| 2 | `database/sql.convertAssignRows` | 68.0MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 36.27MB |
| 5 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 13.58MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `runtime.mallocgc` | 9.01MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 9 | `dotlapse-event-service/project.FilterProjectsByTags` | 5.09MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.64GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.82GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.01GB |
| 4 | `reflect.growslice` | 2.38GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.24GB |
| 6 | `jackskj/carta.getUniqueId` | 2.08GB |
| 7 | `reflect.unsafe_New` | 1.83GB |
| 8 | `database/sql.convertAssignRows` | 1.76GB |
| 9 | `reflect.unsafe_NewArray` | 1.6GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.38GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.69MB | 11/454 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.2MB | 18/454 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 452/454 | `██████████░░░░░ 69%` |
| 4 | `database/sql.convertAssignRows` | 30.41MB | 22/454 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 22.46MB | 452/454 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.57MB | 307/454 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/454 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/454 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/454 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/454 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/454 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/454 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/454 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.21GB | 429/454 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/454 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/454 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/454 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.29GB | 386/454 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/454 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 16.39GB | 260/454 | `█░░░░░░░░░░░░░░ 13%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
