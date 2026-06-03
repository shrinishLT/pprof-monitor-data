# Overview: prod
*Last updated: 2026-06-04 04:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:55 (1014 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,433 | avg: 10,280 | max: 84,644 | trend: decreasing (-33.26/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄
```

**Heap InUse** (current: 172.2MB | avg: 153.9MB | max: 2823.8MB | trend: stable (-0.47MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,433 | 14,957 | -524 | 10,280 | 84,644 | decreasing (-33.26/hr) |
| Heap InUse | 172.2MB | 166.6MB | +5.6MB | 153.9MB | 2823.8MB | stable (-0.47MB/hr) |
| Heap Sys | 939.3MB | 939.7MB | -0.4MB | 2569.8MB | 6883.9MB | |
| Heap Objects | 857,303 | 482,853 | +374450 | 659,144 | 14,090,816 | |

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
| 2026-06-04 | 60 | 15,548 | 268.9MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `bytes.growSlice` | 6.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `reflect.mapassign_faststr0` | 3.0MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 1.01MB |
| 10 | `bufio.NewReaderSize` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 2.76GB |
| 2 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 2.63GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 1.95GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.94GB |
| 5 | `jackskj/carta.getUniqueId` | 1.54GB |
| 6 | `strconv.appendQuotedWith` | 1.35GB |
| 7 | `fmt.Sprint` | 1.31GB |
| 8 | `reflect.growslice` | 1.25GB |
| 9 | `reflect.unsafe_New` | 1.24GB |
| 10 | `fmt.(*buffer).writeString` | 1.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 27.54MB | 23.48MB | 82.34MB | 0B |
| `evaluation.mergeMetadata` | 13.50MB | 12.00MB | 42.73MB | 0B |
| `local.(*Client).EvaluateV2` | 38.29MB | 32.70MB | 127.53MB | 0B |
| `local.topologicalSort` | 6.56MB | 6.05MB | 20.68MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 40.38MB | 34.26MB | 122.06MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 512.14kB | 512.14kB | 12.97MB | 0B |
| `localEvaluation.getMapOfValue` | 40.38MB | 34.26MB | 122.06MB | 0B |
| `utils.ParseFeatureFlag` | 40.38MB | 34.26MB | 122.08MB | 0B |

**Total FF alloc (current snapshot):** 207.53MB  |  **24h avg:** 652.46MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1014 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1014 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 665/1014 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1014 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.37MB | 665/1014 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1014 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.3MB | 472/1014 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1014 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1014 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1014 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1014 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1014 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1014 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1014 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 43.66GB | 642/1014 | `█████░░░░░░░░░░ 34%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1014 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1014 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.8GB | 582/1014 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.69GB | 332/1014 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1014 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Goroutine spike to 20,625 at 2026-05-18T12:33 (2.0x avg)
