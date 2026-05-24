# Overview: prod
*Last updated: 2026-05-24 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T21:02 (465 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,099 | avg: 15,625 | max: 84,644 | trend: decreasing (-0.71/hr))
```
▁▂▃▁▅▄▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.8MB | avg: 230.0MB | max: 1896.6MB | trend: stable (-0.12MB/hr))
```
▁▃▃▁▃▃▂▁▂▂▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,099 | 14,186 | -87 | 15,625 | 84,644 | decreasing (-0.71/hr) |
| Heap InUse | 129.8MB | 113.1MB | +16.7MB | 230.0MB | 1896.6MB | stable (-0.12MB/hr) |
| Heap Sys | 4062.8MB | 4062.7MB | +0.1MB | 4177.0MB | 6883.9MB | |
| Heap Objects | 706,982 | 430,053 | +276929 | 984,508 | 8,100,802 | |

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
| 2026-05-24 | 43 | 14,765 | 195.6MB | 689.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 1.5MB |
| 10 | `regexp.onePassCopy` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 40.13GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.34GB |
| 3 | `segmentio/kafka-go.makePartitions` | 9.5GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.34GB |
| 5 | `reflect.unsafe_NewArray` | 4.92GB |
| 6 | `database/sql.convertAssignRows` | 4.65GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.12GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 3.38GB |
| 9 | `reflect.MakeSlice` | 2.79GB |
| 10 | `reflect.growslice` | 2.54GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 52.69MB | 11/465 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.2MB | 18/465 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 463/465 | `██████████░░░░░ 69%` |
| 4 | `database/sql.convertAssignRows` | 30.41MB | 22/465 | `████████░░░░░░░ 57%` |
| 5 | `runtime.mallocgc` | 22.14MB | 463/465 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.54MB | 308/465 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/465 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/465 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/465 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/465 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/465 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/465 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/465 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 51.62GB | 440/465 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/465 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/465 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/465 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.92GB | 397/465 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/465 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.99GB | 271/465 | `█░░░░░░░░░░░░░░ 12%` |

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
