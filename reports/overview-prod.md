# Overview: prod
*Last updated: 2026-06-04 00:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:15 (958 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,347 | avg: 9,971 | max: 84,644 | trend: decreasing (-43.54/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇
```

**Heap InUse** (current: 318.2MB | avg: 147.0MB | max: 1896.6MB | trend: decreasing (-0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,347 | 14,705 | +2642 | 9,971 | 84,644 | decreasing (-43.54/hr) |
| Heap InUse | 318.2MB | 139.1MB | +179.1MB | 147.0MB | 1896.6MB | decreasing (-0.65MB/hr) |
| Heap Sys | 2426.6MB | 2432.1MB | -5.5MB | 2580.4MB | 6883.9MB | |
| Heap Objects | 1,620,001 | 374,412 | +1245589 | 628,707 | 8,100,802 | |

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
| 2026-06-04 | 4 | 15,387 | 217.4MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.66MB |
| 3 | `bufio.NewReaderSize` | 12.06MB |
| 4 | `runtime.mallocgc` | 11.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `bufio.NewWriterSize` | 4.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.56GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.39GB |
| 3 | `fmt.Sprintf` | 941.24MB |
| 4 | `segmentio/kafka-go.makePartitions` | 927.94MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 887.78MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 750.73MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 613.01MB |
| 8 | `database/sql.convertAssignRows` | 514.53MB |
| 9 | `reflect.unsafe_NewArray` | 487.09MB |
| 10 | `fmt.Sprint` | 438.84MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 59.61MB | 54.53MB | 83.74MB | 0B |
| `evaluation.mergeMetadata` | 34.01MB | 30.51MB | 42.24MB | 0B |
| `local.(*Client).EvaluateV2` | 86.34MB | 80.75MB | 127.31MB | 0B |
| `local.topologicalSort` | 15.73MB | 15.21MB | 20.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 75.72MB | 69.63MB | 107.18MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 16.24MB | 16.24MB | 29.85MB | 0B |
| `localEvaluation.getMapOfValue` | 75.72MB | 69.63MB | 107.18MB | 0B |
| `utils.ParseFeatureFlag` | 76.22MB | 70.13MB | 107.50MB | 0B |

**Total FF alloc (current snapshot):** 439.61MB  |  **24h avg:** 625.79MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/958 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/958 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 609/958 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.65MB | 33/958 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.12MB | 609/958 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.36MB | 422/958 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/958 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/958 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.68MB | 3/958 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 602/958 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/958 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/958 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/958 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/958 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.41GB | 586/958 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/958 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/958 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.21GB | 539/958 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 16.03GB | 276/958 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.8GB | 392/958 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (3.0x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
