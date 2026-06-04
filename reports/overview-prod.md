# Overview: prod
*Last updated: 2026-06-05 05:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T05:20 (1307 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,756 | avg: 11,653 | max: 84,644 | trend: decreasing (-5.98/hr))
```
▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▃▃▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁
```

**Heap InUse** (current: 198.6MB | avg: 179.3MB | max: 3154.1MB | trend: stable (-0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,756 | 14,912 | -156 | 11,653 | 84,644 | decreasing (-5.98/hr) |
| Heap InUse | 198.6MB | 1935.2MB | -1736.6MB | 179.3MB | 3154.1MB | stable (-0.04MB/hr) |
| Heap Sys | 4531.9MB | 4529.5MB | +2.4MB | 2685.8MB | 6883.9MB | |
| Heap Objects | 1,076,287 | 14,331,470 | -13255183 | 795,485 | 17,165,538 | |

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
| 2026-06-05 | 65 | 14,942 | 275.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `bytes.growSlice` | 7.04MB |
| 5 | `bufio.NewReaderSize` | 6.05MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.54MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.62GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 8.16GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.91GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.73GB |
| 5 | `database/sql.convertAssignRows` | 2.46GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.05GB |
| 7 | `reflect.unsafe_NewArray` | 2.05GB |
| 8 | `fmt.Sprintf` | 1.8GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 1.69GB |
| 10 | `reflect.MakeSlice` | 1.09GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 209.35MB | 205.75MB | 144.52MB | 0B |
| `evaluation.mergeMetadata` | 107.03MB | 105.53MB | 73.28MB | 0B |
| `local.(*Client).EvaluateV2` | 312.65MB | 308.01MB | 213.43MB | 0B |
| `local.topologicalSort` | 43.99MB | 43.47MB | 30.90MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 312.69MB | 308.06MB | 204.60MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 29.10MB | 29.10MB | 26.50MB | 0B |
| `localEvaluation.getMapOfValue` | 312.69MB | 308.06MB | 204.60MB | 0B |
| `utils.ParseFeatureFlag` | 313.69MB | 309.06MB | 205.07MB | 0B |

**Total FF alloc (current snapshot):** 1.60GB  |  **24h avg:** 1.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 99.07MB | 29/1307 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 81.93MB | 46/1307 | `████████████░░░ 82%` |
| 3 | `database/sql.convertAssignRows` | 41.93MB | 58/1307 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 958/1307 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 18.43MB | 958/1307 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1307 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.56MB | 730/1307 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1307 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1307 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1307 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1307 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1307 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1307 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1307 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1307 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.33GB | 930/1307 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1307 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.73GB | 853/1307 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.85GB | 538/1307 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.77GB | 175/1307 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.3x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
