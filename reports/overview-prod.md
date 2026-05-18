# Overview: prod
*Last updated: 2026-05-18 18:47 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:47 (146 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,329 | avg: 15,307 | max: 84,644 | trend: decreasing (-15.84/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁
```

**Heap InUse** (current: 308.4MB | avg: 220.5MB | max: 1896.6MB | trend: decreasing (-0.54MB/hr))
```
▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,329 | 18,829 | -4500 | 15,307 | 84,644 | decreasing (-15.84/hr) |
| Heap InUse | 308.4MB | 424.1MB | -115.7MB | 220.5MB | 1896.6MB | decreasing (-0.54MB/hr) |
| Heap Sys | 6171.4MB | 6169.0MB | +2.4MB | 4421.6MB | 6179.8MB | |
| Heap Objects | 2,408,763 | 1,716,711 | +692052 | 965,495 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 39 | 15,336 | 240.0MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewWriterSize` | 2.02MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `reflect.unsafe_NewArray` | 1.52MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 418.81GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 253.58GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 252.83GB |
| 4 | `experiment/local.topologicalSort` | 167.26GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 131.31GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 80.05GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 40.46GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/146 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 144/146 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 24.49MB | 144/146 | `█████████░░░░░░ 66%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/146 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/146 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/146 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.34MB | 78/146 | `█████░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/146 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/146 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/146 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 78.44GB | 135/146 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 64.57GB | 139/146 | `████████████░░░ 82%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 46.1GB | 141/146 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 46.05GB | 141/146 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.7GB | 91/146 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 33.43GB | 123/146 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.83GB | 137/146 | `█████░░░░░░░░░░ 35%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/146 | `████░░░░░░░░░░░ 30%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 23.66GB | 70/146 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.growslice` | 22.61GB | 47/146 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
