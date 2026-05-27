# Overview: prod
*Last updated: 2026-05-27 06:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T06:01 (577 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,737 | avg: 15,612 | max: 84,644 | trend: stable (-0.46/hr))
```
▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 615.8MB | avg: 230.1MB | max: 1896.6MB | trend: stable (-0.06MB/hr))
```
▂▁▂▁▁▁▁▂▁▅▂▄▂▂▄▄▅▃▄▃▂▅▂▂▄▃▃▄▃▂▂▂▃▂▂▂▃▂▁▁▁▂▁▁▁▁▁█▁▄▁▁▁▁▁▁▁▄▆▃▁▁▁▂▁▁▄▂▂▁▁▄▁▂▂▂▁▁▂▁▂▃▁▁▂▂▂▃▂▁▃▂▁▂▁▇
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,737 | 16,288 | -1551 | 15,612 | 84,644 | stable (-0.46/hr) |
| Heap InUse | 615.8MB | 174.1MB | +441.7MB | 230.1MB | 1896.6MB | stable (-0.06MB/hr) |
| Heap Sys | 2169.3MB | 1161.9MB | +1007.4MB | 4135.2MB | 6883.9MB | |
| Heap Objects | 2,506,232 | 382,784 | +2123448 | 983,259 | 8,100,802 | |

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
| 2026-05-27 | 13 | 15,543 | 246.6MB | 615.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 118.29MB |
| 2 | `database/sql.convertAssignRows` | 52.0MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 17.21MB |
| 5 | `runtime.mallocgc` | 12.01MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 8 | `bytes.growSlice` | 5.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 4.52MB |
| 10 | `bufio.NewReaderSize` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 10.51GB |
| 2 | `reflect.growslice` | 9.78GB |
| 3 | `jackskj/carta.getUniqueId` | 7.43GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.9GB |
| 5 | `reflect.unsafe_New` | 6.75GB |
| 6 | `fmt.(*buffer).writeString` | 4.91GB |
| 7 | `carta/value.NewCell` | 4.89GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 4.16GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.48GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.92GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 50.12MB | 23/577 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/577 | `██████████████░ 94%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 575/577 | `██████████░░░░░ 73%` |
| 4 | `database/sql.convertAssignRows` | 27.4MB | 29/577 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.56MB | 575/577 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.23MB | 391/577 | `███░░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 12.29MB | 7/577 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/577 | `███░░░░░░░░░░░░ 21%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/577 | `███░░░░░░░░░░░░ 21%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.79MB | 2/577 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/577 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/577 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/577 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/577 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 49.28GB | 552/577 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/577 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/577 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.11GB | 507/577 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `fmt.Sprintf` | 17.33GB | 252/577 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `segmentio/kafka-go.makePartitions` | 14.61GB | 367/577 | `█░░░░░░░░░░░░░░ 11%` |

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
