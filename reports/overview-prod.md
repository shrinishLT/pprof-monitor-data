# Overview: prod
*Last updated: 2026-05-19 01:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T01:02 (163 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,517 | avg: 15,397 | max: 84,644 | trend: decreasing (-5.93/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 256.7MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.27MB/hr))
```
▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,517 | 14,637 | -120 | 15,397 | 84,644 | decreasing (-5.93/hr) |
| Heap InUse | 256.7MB | 287.5MB | -30.8MB | 230.8MB | 1896.6MB | stable (+0.27MB/hr) |
| Heap Sys | 6571.3MB | 6573.7MB | -2.4MB | 4633.4MB | 6579.6MB | |
| Heap Objects | 1,101,915 | 1,214,436 | -112521 | 986,111 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 3 | 14,482 | 253.0MB | 287.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `bufio.NewWriterSize` | 2.55MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 543.29GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 328.71GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 327.59GB |
| 4 | `experiment/local.topologicalSort` | 216.94GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 170.47GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 152.93GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 103.42GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 69.96GB |
| 9 | `fmt.Sprintf` | 54.38GB |
| 10 | `segmentio/kafka-go.makePartitions` | 45.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/163 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/163 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/163 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 161/163 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.71MB | 161/163 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/163 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/163 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.45MB | 93/163 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/163 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/163 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.97GB | 152/163 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 73.04GB | 156/163 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 72.17GB | 158/163 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 72.03GB | 158/163 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 52.49GB | 140/163 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.91GB | 108/163 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 36.8GB | 87/163 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.93GB | 154/163 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 30.43GB | 37/163 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/163 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
