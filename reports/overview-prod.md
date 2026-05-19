# Overview: prod
*Last updated: 2026-05-19 13:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T13:30 (188 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,965 | avg: 15,389 | max: 84,644 | trend: decreasing (-3.88/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁
```

**Heap InUse** (current: 180.2MB | avg: 229.1MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,965 | 15,093 | -128 | 15,389 | 84,644 | decreasing (-3.88/hr) |
| Heap InUse | 180.2MB | 173.5MB | +6.7MB | 229.1MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 4944.6MB | 4944.1MB | +0.5MB | 4472.7MB | 6579.6MB | |
| Heap Objects | 621,169 | 542,752 | +78417 | 980,352 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 28 | 15,246 | 221.8MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 6.03MB |
| 6 | `bufio.NewReaderSize` | 4.02MB |
| 7 | `bufio.NewWriterSize` | 3.51MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 71.76GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 42.91GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 42.86GB |
| 4 | `experiment/local.topologicalSort` | 28.54GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.73GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 13.52GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 11.98GB |
| 8 | `fmt.Sprintf` | 6.55GB |
| 9 | `reflect.growslice` | 6.52GB |
| 10 | `jackskj/carta.getUniqueId` | 6.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/188 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/188 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/188 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 186/188 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.19MB | 186/188 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/188 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/188 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.85MB | 16/188 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 12.18MB | 112/188 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/188 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.71GB | 177/188 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.95GB | 183/188 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.84GB | 183/188 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 68.59GB | 178/188 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 50.14GB | 165/188 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.64GB | 133/188 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.8GB | 111/188 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/188 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 26.37GB | 48/188 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/188 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
