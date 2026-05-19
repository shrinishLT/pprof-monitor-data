# Overview: prod
*Last updated: 2026-05-19 11:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T11:02 (183 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,409 | avg: 15,379 | max: 84,644 | trend: decreasing (-4.85/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

**Heap InUse** (current: 158.3MB | avg: 228.9MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,409 | 14,739 | -330 | 15,379 | 84,644 | decreasing (-4.85/hr) |
| Heap InUse | 158.3MB | 217.8MB | -59.5MB | 228.9MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 2115.0MB | 2122.6MB | -7.6MB | 4459.8MB | 6579.6MB | |
| Heap Objects | 576,180 | 841,277 | -265097 | 978,909 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 23 | 15,139 | 218.3MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `bytes.growSlice` | 2.01MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `aws/endpoints.init` | 1.5MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 15.05GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 8.94GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 8.94GB |
| 4 | `experiment/local.topologicalSort` | 5.95GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.83GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 2.82GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 2.48GB |
| 8 | `reflect.growslice` | 2.17GB |
| 9 | `jackskj/carta.getUniqueId` | 2.06GB |
| 10 | `reflect.unsafe_New` | 1.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/183 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/183 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/183 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 181/183 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.36MB | 181/183 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/183 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/183 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.77MB | 15/183 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 12.08MB | 108/183 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/183 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.55GB | 172/183 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.99GB | 178/183 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.88GB | 178/183 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.01GB | 174/183 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 51.02GB | 160/183 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.81GB | 128/183 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.86GB | 106/183 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/183 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 27.73GB | 45/183 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/183 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
