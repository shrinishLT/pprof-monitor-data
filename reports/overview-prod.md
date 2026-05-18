# Overview: prod
*Last updated: 2026-05-19 00:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T00:00 (161 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,292 | avg: 15,407 | max: 84,644 | trend: decreasing (-5.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 214.7MB | avg: 230.3MB | max: 1896.6MB | trend: stable (+0.24MB/hr))
```
▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,292 | 14,719 | -427 | 15,407 | 84,644 | decreasing (-5.38/hr) |
| Heap InUse | 214.7MB | 286.9MB | -72.2MB | 230.3MB | 1896.6MB | stable (+0.24MB/hr) |
| Heap Sys | 6573.5MB | 6572.6MB | +0.9MB | 4609.4MB | 6579.6MB | |
| Heap Objects | 709,168 | 800,785 | -91617 | 983,974 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 1 | 14,292 | 214.7MB | 214.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.14MB |
| 9 | `bufio.NewWriterSize` | 1.55MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 525.49GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 317.84GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 316.95GB |
| 4 | `experiment/local.topologicalSort` | 209.89GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 164.85GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 148.53GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 100.0GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 67.9GB |
| 9 | `fmt.Sprintf` | 52.49GB |
| 10 | `segmentio/kafka-go.makePartitions` | 43.66GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/161 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/161 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/161 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 159/161 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.37MB | 159/161 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/161 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/161 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.63MB | 91/161 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/161 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/161 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.44GB | 150/161 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 72.0GB | 154/161 | `█████████░░░░░░ 61%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 68.93GB | 156/161 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 68.8GB | 156/161 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 50.14GB | 138/161 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.71GB | 106/161 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 35.25GB | 85/161 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.43GB | 152/161 | `████░░░░░░░░░░░ 26%` |
| 9 | `fmt.Sprintf` | 29.1GB | 35/161 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/161 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
