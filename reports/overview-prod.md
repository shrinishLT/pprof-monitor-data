# Overview: prod
*Last updated: 2026-05-19 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T12:02 (185 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,233 | avg: 15,369 | max: 84,644 | trend: decreasing (-5.35/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁
```

**Heap InUse** (current: 181.3MB | avg: 228.5MB | max: 1896.6MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,233 | 14,644 | -411 | 15,369 | 84,644 | decreasing (-5.35/hr) |
| Heap InUse | 181.3MB | 220.7MB | -39.4MB | 228.5MB | 1896.6MB | stable (+0.06MB/hr) |
| Heap Sys | 4950.0MB | 4949.7MB | +0.3MB | 4465.1MB | 6579.6MB | |
| Heap Objects | 930,050 | 1,009,243 | -79193 | 978,809 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 25 | 15,083 | 216.9MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `compress/flate.NewWriter` | 1.76MB |
| 7 | `reflect.growslice` | 1.51MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 9 | `bufio.NewReaderSize` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 46.57GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 27.76GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 27.72GB |
| 4 | `experiment/local.topologicalSort` | 18.5GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.8GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 8.73GB |
| 7 | `reflect.growslice` | 5.8GB |
| 8 | `jackskj/carta.getUniqueId` | 5.41GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 4.75GB |
| 10 | `reflect.unsafe_New` | 4.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/185 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/185 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/185 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 183/185 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.29MB | 183/185 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/185 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/185 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.85MB | 16/185 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 11.99MB | 109/185 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/185 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.63GB | 174/185 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.46GB | 180/185 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.35GB | 180/185 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 69.27GB | 176/185 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 50.59GB | 162/185 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.26GB | 130/185 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.37GB | 108/185 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/185 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 27.73GB | 45/185 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/185 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
