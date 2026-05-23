# Overview: prod
*Last updated: 2026-05-24 01:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T01:32 (426 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 15,697 | max: 84,644 | trend: INCREASING (+1.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.1MB | avg: 232.7MB | max: 1896.6MB | trend: stable (-0.08MB/hr))
```
▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,102 | -31 | 15,697 | 84,644 | INCREASING (+1.32/hr) |
| Heap InUse | 181.1MB | 165.4MB | +15.7MB | 232.7MB | 1896.6MB | stable (-0.08MB/hr) |
| Heap Sys | 4435.5MB | 4435.3MB | +0.2MB | 4199.2MB | 6883.9MB | |
| Heap Objects | 1,380,204 | 1,148,533 | +231671 | 984,414 | 8,100,802 | |

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
| 2026-05-24 | 4 | 14,080 | 145.9MB | 181.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 5.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 64.08GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 24.5GB |
| 3 | `segmentio/kafka-go.makePartitions` | 14.98GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.0GB |
| 5 | `reflect.unsafe_NewArray` | 7.7GB |
| 6 | `database/sql.convertAssignRows` | 7.18GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.41GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.24GB |
| 9 | `reflect.MakeSlice` | 4.34GB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/426 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.79MB | 16/426 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 424/426 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 20/426 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 23.03MB | 424/426 | `██████░░░░░░░░░ 40%` |
| 6 | `bytes.growSlice` | 13.75MB | 291/426 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/426 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/426 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/426 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/426 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/426 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/426 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/426 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/426 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.76GB | 401/426 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/426 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/426 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.58GB | 358/426 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.(*buffer).writeString` | 18.59GB | 21/426 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `fmt.Sprintf` | 18.14GB | 201/426 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
