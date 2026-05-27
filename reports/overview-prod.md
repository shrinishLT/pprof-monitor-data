# Overview: prod
*Last updated: 2026-05-27 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T17:02 (599 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,989 | avg: 15,625 | max: 84,644 | trend: stable (-0.16/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▅▁▂▁▁▁▃▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 185.5MB | avg: 230.4MB | max: 1896.6MB | trend: stable (-0.05MB/hr))
```
▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇▄▁▁▁▁▂▁▅▃▄▁▁▁▄▃▂▂▃▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,989 | 14,206 | +783 | 15,625 | 84,644 | stable (-0.16/hr) |
| Heap InUse | 185.5MB | 174.1MB | +11.4MB | 230.4MB | 1896.6MB | stable (-0.05MB/hr) |
| Heap Sys | 3467.6MB | 903.7MB | +2563.9MB | 4073.8MB | 6883.9MB | |
| Heap Objects | 472,248 | 689,917 | -217669 | 985,912 | 8,100,802 | |

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
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 35 | 15,807 | 241.4MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.12MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.98MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `database/sql.convertAssignRows` | 21.0MB |
| 5 | `runtime.mallocgc` | 12.01MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bytes.growSlice` | 7.54MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.0MB |
| 10 | `dotlapse-event-service/project.FilterProjectsByTags` | 4.58MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 11.82GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 4.53GB |
| 3 | `segmentio/kafka-go.makePartitions` | 2.4GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.66GB |
| 5 | `database/sql.convertAssignRows` | 1.59GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.41GB |
| 7 | `reflect.unsafe_NewArray` | 1.21GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.15GB |
| 9 | `fmt.Sprintf` | 1.04GB |
| 10 | `reflect.MakeSlice` | 715.52MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/599 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/599 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 597/599 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 27.36MB | 32/599 | `████████░░░░░░░ 55%` |
| 5 | `runtime.mallocgc` | 22.33MB | 597/599 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.26MB | 411/599 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/599 | `███░░░░░░░░░░░░ 25%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/599 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/599 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 590/599 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/599 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/599 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/599 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/599 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.3GB | 574/599 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/599 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/599 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.65GB | 527/599 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 16.69GB | 264/599 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.2GB | 380/599 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
