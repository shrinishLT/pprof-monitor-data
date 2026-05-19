# Overview: prod
*Last updated: 2026-05-19 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T10:30 (182 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,739 | avg: 15,385 | max: 84,644 | trend: decreasing (-4.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁
```

**Heap InUse** (current: 217.8MB | avg: 229.2MB | max: 1896.6MB | trend: stable (+0.11MB/hr))
```
▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,739 | 26,874 | -12135 | 15,385 | 84,644 | decreasing (-4.58/hr) |
| Heap InUse | 217.8MB | 661.0MB | -443.2MB | 229.2MB | 1896.6MB | stable (+0.11MB/hr) |
| Heap Sys | 2122.6MB | 3120.7MB | -998.1MB | 4472.7MB | 6579.6MB | |
| Heap Objects | 841,277 | 3,436,931 | -2595654 | 981,122 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 22 | 15,172 | 221.1MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewWriterSize` | 2.01MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 8.72GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 5.25GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 5.24GB |
| 4 | `experiment/local.topologicalSort` | 3.48GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.84GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 2.09GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 1.65GB |
| 8 | `fmt.Sprintf` | 738.78MB |
| 9 | `reflect.growslice` | 672.45MB |
| 10 | `jackskj/carta.getUniqueId` | 632.12MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/182 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/182 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/182 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 180/182 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.39MB | 180/182 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/182 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/182 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.77MB | 15/182 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 12.17MB | 107/182 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/182 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.17GB | 171/182 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.34GB | 177/182 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 177/182 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.01GB | 174/182 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.31GB | 159/182 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.16GB | 127/182 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.16GB | 105/182 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/182 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 27.73GB | 45/182 | `███░░░░░░░░░░░░ 22%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/182 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
