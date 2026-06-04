# Overview: prod
*Last updated: 2026-06-04 16:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T16:12 (1149 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,627 | avg: 11,133 | max: 84,644 | trend: decreasing (-14.93/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 207.3MB | avg: 169.3MB | max: 2823.8MB | trend: stable (-0.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,627 | 15,902 | -1275 | 11,133 | 84,644 | decreasing (-14.93/hr) |
| Heap InUse | 207.3MB | 300.2MB | -92.9MB | 169.3MB | 2823.8MB | stable (-0.18MB/hr) |
| Heap Sys | 4152.6MB | 4151.7MB | +0.9MB | 2650.1MB | 6883.9MB | |
| Heap Objects | 1,037,454 | 1,553,469 | -516015 | 729,972 | 14,090,816 | |

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
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 195 | 16,926 | 280.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 4.76MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewReaderSize` | 2.01MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 21.66GB |
| 2 | `fmt.Sprintf` | 9.37GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 8.57GB |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.72GB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.39GB |
| 6 | `reflect.growslice` | 6.34GB |
| 7 | `jackskj/carta.getUniqueId` | 6.24GB |
| 8 | `reflect.unsafe_New` | 5.28GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.75GB |
| 10 | `fmt.Sprint` | 4.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 593.64MB | 581.98MB | 336.47MB | 0B |
| `evaluation.mergeMetadata` | 305.58MB | 299.07MB | 176.01MB | 0B |
| `local.(*Client).EvaluateV2` | 918.63MB | 901.31MB | 512.64MB | 0B |
| `local.topologicalSort` | 129.05MB | 126.52MB | 71.37MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 854.78MB | 837.44MB | 477.81MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 142.69MB | 141.67MB | 80.95MB | 0B |
| `localEvaluation.getMapOfValue` | 854.78MB | 837.44MB | 477.81MB | 0B |
| `utils.ParseFeatureFlag` | 854.78MB | 837.44MB | 477.81MB | 0B |

**Total FF alloc (current snapshot):** 4.54GB  |  **24h avg:** 2.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1149 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1149 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 800/1149 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1149 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.07MB | 800/1149 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1149 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.5MB | 587/1149 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1149 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1149 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1149 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1149 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1149 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1149 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1149 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1149 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.6GB | 773/1149 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1149 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.41GB | 697/1149 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.39GB | 392/1149 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.06GB | 534/1149 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
