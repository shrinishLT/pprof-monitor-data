# Overview: prod
*Last updated: 2026-05-23 15:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T15:32 (406 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,131 | avg: 15,774 | max: 84,644 | trend: INCREASING (+3.90/hr))
```
▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 127.0MB | avg: 237.0MB | max: 1896.6MB | trend: stable (+0.04MB/hr))
```
▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,131 | 14,283 | -152 | 15,774 | 84,644 | INCREASING (+3.90/hr) |
| Heap InUse | 127.0MB | 191.3MB | -64.3MB | 237.0MB | 1896.6MB | stable (+0.04MB/hr) |
| Heap Sys | 3921.1MB | 1553.7MB | +2367.4MB | 4203.0MB | 6883.9MB | |
| Heap Objects | 588,193 | 1,315,161 | -726968 | 989,180 | 8,100,802 | |

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
| 2026-05-23 | 32 | 15,056 | 189.4MB | 359.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 5.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `aws/endpoints.init` | 2.0MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `bytes.growSlice` | 1.51MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 13.68GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 5.2GB |
| 3 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.68GB |
| 4 | `database/sql.convertAssignRows` | 1.52GB |
| 5 | `segmentio/kafka-go.makePartitions` | 1.36GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 994.89MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 814.84MB |
| 8 | `reflect.unsafe_NewArray` | 717.32MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 550.61MB |
| 10 | `fmt.Sprintf` | 412.62MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/406 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.79MB | 16/406 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 404/406 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 20/406 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 23.93MB | 404/406 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.77MB | 290/406 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/406 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/406 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/406 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/406 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/406 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/406 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/406 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/406 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.35GB | 381/406 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/406 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/406 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.11GB | 338/406 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 18.59GB | 21/406 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `fmt.Sprintf` | 18.14GB | 201/406 | `██░░░░░░░░░░░░░ 14%` |

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
