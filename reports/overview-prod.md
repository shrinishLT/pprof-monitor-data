# Overview: prod
*Last updated: 2026-06-05 18:17 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T18:17 (1462 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,249 | avg: 12,195 | max: 84,644 | trend: stable (-0.31/hr))
```
▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 181.4MB | avg: 185.8MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▅▄▄▅▆▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,249 | 14,613 | +636 | 12,195 | 84,644 | stable (-0.31/hr) |
| Heap InUse | 181.4MB | 191.3MB | -9.9MB | 185.8MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1044.8MB | 1044.2MB | +0.6MB | 2613.2MB | 6883.9MB | |
| Heap Objects | 519,515 | 935,612 | -416097 | 826,170 | 17,165,538 | |

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
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 220 | 16,232 | 251.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.34MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 5.52MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 9.29GB |
| 2 | `fmt.Sprintf` | 6.79GB |
| 3 | `reflect.growslice` | 6.56GB |
| 4 | `jackskj/carta.getUniqueId` | 6.39GB |
| 5 | `reflect.unsafe_New` | 5.44GB |
| 6 | `reflect.unsafe_NewArray` | 4.85GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.8GB |
| 8 | `fmt.(*buffer).writeString` | 4.16GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 4.14GB |
| 10 | `carta/value.NewCell` | 3.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 670.16MB | 651.35MB | 478.22MB | 0B |
| `evaluation.mergeMetadata` | 345.58MB | 334.08MB | 245.91MB | 0B |
| `local.(*Client).EvaluateV2` | 1.01GB | 1014.67MB | 751.54MB | 0B |
| `local.topologicalSort` | 145.69MB | 143.15MB | 110.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 980.37MB | 960.90MB | 713.23MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 157.30MB | 149.67MB | 107.02MB | 0B |
| `localEvaluation.getMapOfValue` | 980.37MB | 960.90MB | 713.23MB | 0B |
| `utils.ParseFeatureFlag` | 982.87MB | 962.90MB | 714.71MB | 0B |

**Total FF alloc (current snapshot):** 5.18GB  |  **24h avg:** 3.74GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1462 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1462 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1462 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1113/1462 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1462 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.54MB | 1113/1462 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.02MB | 867/1462 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `fmt.Sprint` | 14.4MB | 3/1462 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1462 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1462 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1462 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1462 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1462 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1462 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1462 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 31.38GB | 1084/1462 | `███░░░░░░░░░░░░ 25%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1462 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1462 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1462 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.82GB | 646/1462 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
