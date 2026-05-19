# Overview: prod
*Last updated: 2026-05-19 18:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T18:30 (198 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,709 | avg: 15,378 | max: 84,644 | trend: decreasing (-3.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 191.4MB | avg: 230.5MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,709 | 15,122 | -413 | 15,378 | 84,644 | decreasing (-3.91/hr) |
| Heap InUse | 191.4MB | 207.7MB | -16.3MB | 230.5MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4939.8MB | 4938.2MB | +1.6MB | 4496.6MB | 6579.6MB | |
| Heap Objects | 801,561 | 706,496 | +95065 | 986,766 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 38 | 15,228 | 230.9MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bufio.NewWriterSize` | 3.53MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `bufio.NewReaderSize` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 165.73GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 99.36GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 99.35GB |
| 4 | `experiment/local.topologicalSort` | 65.9GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.53GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.17GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.38GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 22.57GB |
| 9 | `fmt.Sprintf` | 16.34GB |
| 10 | `segmentio/kafka-go.makePartitions` | 11.02GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/198 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/198 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 196/198 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/198 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.89MB | 196/198 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/198 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/198 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.92MB | 121/198 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/198 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 194/198 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.76GB | 187/198 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.04GB | 193/198 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.94GB | 193/198 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.48GB | 188/198 | `████████░░░░░░░ 55%` |
| 5 | `experiment/local.topologicalSort` | 50.0GB | 175/198 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.92GB | 143/198 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.96GB | 121/198 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.12GB | 179/198 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/198 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.79GB | 58/198 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
