# Overview: prod
*Last updated: 2026-06-04 15:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T15:46 (1144 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,369 | avg: 11,114 | max: 84,644 | trend: decreasing (-15.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 227.3MB | avg: 169.0MB | max: 2823.8MB | trend: stable (-0.19MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,369 | 15,569 | -200 | 11,114 | 84,644 | decreasing (-15.33/hr) |
| Heap InUse | 227.3MB | 249.1MB | -21.8MB | 169.0MB | 2823.8MB | stable (-0.19MB/hr) |
| Heap Sys | 4151.6MB | 4150.9MB | +0.7MB | 2643.5MB | 6883.9MB | |
| Heap Objects | 1,030,646 | 1,201,545 | -170899 | 728,391 | 14,090,816 | |

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
| 2026-06-04 | 190 | 16,964 | 281.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `bytes.growSlice` | 10.2MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewWriterSize` | 2.51MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 21.66GB |
| 2 | `fmt.Sprintf` | 8.85GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 8.57GB |
| 4 | `reflect.growslice` | 6.3GB |
| 5 | `jackskj/carta.getUniqueId` | 6.2GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.0GB |
| 7 | `segmentio/kafka-go.makePartitions` | 5.79GB |
| 8 | `reflect.unsafe_New` | 5.24GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.63GB |
| 10 | `fmt.Sprint` | 4.29GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 544.31MB | 538.74MB | 283.01MB | 0B |
| `evaluation.mergeMetadata` | 280.57MB | 278.07MB | 148.92MB | 0B |
| `local.(*Client).EvaluateV2` | 843.90MB | 834.70MB | 428.54MB | 0B |
| `local.topologicalSort` | 120.43MB | 119.42MB | 59.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 784.67MB | 774.45MB | 400.17MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 131.92MB | 131.92MB | 67.23MB | 0B |
| `localEvaluation.getMapOfValue` | 784.67MB | 774.45MB | 400.17MB | 0B |
| `utils.ParseFeatureFlag` | 784.67MB | 774.45MB | 400.17MB | 0B |

**Total FF alloc (current snapshot):** 4.17GB  |  **24h avg:** 2.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1144 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1144 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 795/1144 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1144 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.12MB | 795/1144 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1144 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.51MB | 582/1144 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1144 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1144 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1144 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1144 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1144 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1144 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1144 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1144 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.72GB | 768/1144 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1144 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48GB | 692/1144 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.44GB | 387/1144 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.11GB | 529/1144 | `█░░░░░░░░░░░░░░ 8%` |

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
