# Overview: prod
*Last updated: 2026-05-19 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T20:30 (202 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,123 | avg: 15,400 | max: 84,644 | trend: decreasing (-2.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂▁▃▁
```

**Heap InUse** (current: 195.5MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.17MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▃▃▅▃▂▃▂▂▃▄▃▃▂▃▄▃▃▂▄▄▄▃█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▁▄▁▁▁▁▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▁▂▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,123 | 19,406 | -4283 | 15,400 | 84,644 | decreasing (-2.42/hr) |
| Heap InUse | 195.5MB | 305.8MB | -110.3MB | 230.8MB | 1896.6MB | stable (+0.17MB/hr) |
| Heap Sys | 4941.2MB | 4942.4MB | -1.2MB | 4505.4MB | 6579.6MB | |
| Heap Objects | 648,395 | 953,648 | -305253 | 984,650 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 42 | 15,347 | 232.4MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `bytes.growSlice` | 11.57MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `internal/evaluation.mergeMetadata` | 5.0MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 3.19MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 198.13GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 119.06GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 118.81GB |
| 4 | `experiment/local.topologicalSort` | 78.97GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 61.59GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 58.3GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 37.6GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.77GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 20.55GB |
| 10 | `fmt.Sprintf` | 20.24GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/202 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/202 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 200/202 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/202 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.77MB | 200/202 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/202 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/202 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 12.07MB | 125/202 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.43MB | 20/202 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 198/202 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.13GB | 191/202 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.86GB | 197/202 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.77GB | 197/202 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.29GB | 192/202 | `████████░░░░░░░ 55%` |
| 5 | `experiment/local.topologicalSort` | 50.52GB | 179/202 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.2GB | 147/202 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.06GB | 125/202 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.04GB | 183/202 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/202 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.46GB | 62/202 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
