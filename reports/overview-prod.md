# Overview: prod
*Last updated: 2026-06-04 00:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T00:20 (959 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,781 | avg: 9,976 | max: 84,644 | trend: decreasing (-43.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▁█▇▆▇▇▆▆▆▆▇▆
```

**Heap InUse** (current: 229.5MB | avg: 147.1MB | max: 1896.6MB | trend: decreasing (-0.65MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▇▆▅▅▆▄▄▆▄█▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,781 | 17,347 | -2566 | 9,976 | 84,644 | decreasing (-43.34/hr) |
| Heap InUse | 229.5MB | 318.2MB | -88.7MB | 147.1MB | 1896.6MB | decreasing (-0.65MB/hr) |
| Heap Sys | 2428.2MB | 2426.6MB | +1.6MB | 2580.2MB | 6883.9MB | |
| Heap Objects | 1,215,957 | 1,620,001 | -404044 | 629,319 | 8,100,802 | |

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
| 2026-06-04 | 5 | 15,266 | 219.8MB | 318.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.58MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 7 | `bufio.NewWriterSize` | 5.03MB |
| 8 | `bufio.NewReaderSize` | 5.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.56GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 1.39GB |
| 3 | `fmt.Sprintf` | 1.01GB |
| 4 | `segmentio/kafka-go.makePartitions` | 1007.29MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 970.24MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 820.18MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 621.01MB |
| 8 | `reflect.unsafe_NewArray` | 526.7MB |
| 9 | `database/sql.convertAssignRows` | 521.03MB |
| 10 | `strconv.appendQuotedWith` | 480.55MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 63.66MB | 59.61MB | 82.06MB | 0B |
| `evaluation.mergeMetadata` | 36.01MB | 34.01MB | 41.72MB | 0B |
| `local.(*Client).EvaluateV2` | 92.44MB | 86.34MB | 124.41MB | 0B |
| `local.topologicalSort` | 16.74MB | 15.73MB | 20.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 80.28MB | 75.72MB | 104.94MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 17.78MB | 16.24MB | 28.85MB | 0B |
| `localEvaluation.getMapOfValue` | 80.28MB | 75.72MB | 104.94MB | 0B |
| `utils.ParseFeatureFlag` | 80.78MB | 76.22MB | 105.27MB | 0B |

**Total FF alloc (current snapshot):** 467.98MB  |  **24h avg:** 612.64MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/959 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/959 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 610/959 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.65MB | 33/959 | `████████░░░░░░░ 54%` |
| 5 | `runtime.mallocgc` | 22.1MB | 610/959 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.36MB | 423/959 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/959 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/959 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.68MB | 3/959 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 603/959 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/959 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/959 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/959 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/959 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.34GB | 587/959 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/959 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/959 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.18GB | 540/959 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.97GB | 277/959 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.77GB | 393/959 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.3x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.8x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.2x avg)
