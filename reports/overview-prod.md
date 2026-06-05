# Overview: prod
*Last updated: 2026-06-05 11:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T11:05 (1376 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,334 | avg: 12,006 | max: 84,644 | trend: decreasing (-2.12/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁
```

**Heap InUse** (current: 183.9MB | avg: 185.0MB | max: 3154.1MB | trend: stable (+0.01MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▄▄▅▄▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,334 | 15,362 | -1028 | 12,006 | 84,644 | decreasing (-2.12/hr) |
| Heap InUse | 183.9MB | 267.7MB | -83.8MB | 185.0MB | 3154.1MB | stable (+0.01MB/hr) |
| Heap Sys | 4398.4MB | 4391.0MB | +7.4MB | 2711.0MB | 6883.9MB | |
| Heap Objects | 516,357 | 1,195,381 | -679024 | 821,154 | 17,165,538 | |

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
| 2026-06-05 | 134 | 16,882 | 284.3MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 31.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 12.25GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.17GB |
| 3 | `jackskj/carta.getUniqueId` | 11.74GB |
| 4 | `reflect.unsafe_New` | 10.13GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.22GB |
| 6 | `carta/value.NewCell` | 7.45GB |
| 7 | `fmt.(*buffer).writeString` | 7.34GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.64GB |
| 9 | `fmt.Sprintf` | 5.26GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 4.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 318.49MB | 312.39MB | 166.47MB | 0B |
| `evaluation.mergeMetadata` | 166.04MB | 162.04MB | 85.32MB | 0B |
| `local.(*Client).EvaluateV2` | 478.27MB | 467.04MB | 247.50MB | 0B |
| `local.topologicalSort` | 63.24MB | 60.72MB | 33.32MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 498.76MB | 489.05MB | 257.83MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 27.62MB | 25.59MB | 15.75MB | 0B |
| `localEvaluation.getMapOfValue` | 498.76MB | 489.05MB | 257.83MB | 0B |
| `utils.ParseFeatureFlag` | 498.76MB | 489.05MB | 257.83MB | 0B |

**Total FF alloc (current snapshot):** 2.49GB  |  **24h avg:** 1.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1376 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1376 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1376 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1027/1376 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.09MB | 1027/1376 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1376 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.58MB | 790/1376 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1376 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1376 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1376 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1376 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1376 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1376 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1376 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1376 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.83GB | 998/1376 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1376 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1376 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.47GB | 201/1376 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.35GB | 576/1376 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
