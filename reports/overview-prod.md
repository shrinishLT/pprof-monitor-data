# Overview: prod
*Last updated: 2026-06-04 17:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T17:15 (1162 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,108 | avg: 11,197 | max: 84,644 | trend: decreasing (-13.78/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 203.0MB | avg: 170.6MB | max: 2823.8MB | trend: stable (-0.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁▁▂▂▂▂▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,108 | 15,848 | +260 | 11,197 | 84,644 | decreasing (-13.78/hr) |
| Heap InUse | 203.0MB | 199.4MB | +3.6MB | 170.6MB | 2823.8MB | stable (-0.16MB/hr) |
| Heap Sys | 966.6MB | 967.4MB | -0.8MB | 2652.5MB | 6883.9MB | |
| Heap Objects | 441,184 | 456,098 | -14914 | 736,749 | 14,090,816 | |

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
| 2026-06-04 | 208 | 16,923 | 280.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.41MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 7.54MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.61GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.03GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.03GB |
| 4 | `fmt.Sprintf` | 622.16MB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 600.63MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 558.51MB |
| 7 | `database/sql.convertAssignRows` | 540.54MB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 486.97MB |
| 9 | `segmentio/kafka-go.makePartitions` | 419.73MB |
| 10 | `fmt.Sprint` | 323.23MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 45.70MB | 32.05MB | 404.71MB | 0B |
| `evaluation.mergeMetadata` | 26.01MB | 17.00MB | 209.62MB | 0B |
| `local.(*Client).EvaluateV2` | 69.99MB | 49.12MB | 622.72MB | 0B |
| `local.topologicalSort` | 11.65MB | 7.58MB | 87.77MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 69.54MB | 50.19MB | 579.85MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 12.73MB | 7.12MB | 98.18MB | 0B |
| `localEvaluation.getMapOfValue` | 69.54MB | 50.19MB | 579.85MB | 0B |
| `utils.ParseFeatureFlag` | 69.54MB | 50.19MB | 579.85MB | 0B |

**Total FF alloc (current snapshot):** 374.71MB  |  **24h avg:** 3.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1162 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1162 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 813/1162 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 32.21MB | 50/1162 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 19.93MB | 813/1162 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1162 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.61MB | 599/1162 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1162 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1162 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1162 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1162 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1162 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1162 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1162 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1162 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.22GB | 785/1162 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1162 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.2GB | 709/1162 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.23GB | 404/1162 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.92GB | 546/1162 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
