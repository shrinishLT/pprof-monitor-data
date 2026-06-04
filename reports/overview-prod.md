# Overview: prod
*Last updated: 2026-06-04 11:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:00 (1087 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,443 | avg: 10,825 | max: 84,644 | trend: decreasing (-21.23/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁
```

**Heap InUse** (current: 208.5MB | avg: 163.2MB | max: 2823.8MB | trend: stable (-0.28MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,443 | 29,870 | -15427 | 10,825 | 84,644 | decreasing (-21.23/hr) |
| Heap InUse | 208.5MB | 891.9MB | -683.4MB | 163.2MB | 2823.8MB | stable (-0.28MB/hr) |
| Heap Sys | 5103.7MB | 5003.9MB | +99.8MB | 2639.1MB | 6883.9MB | |
| Heap Objects | 844,661 | 3,583,373 | -2738712 | 700,779 | 14,090,816 | |

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
| 2026-06-04 | 133 | 17,113 | 281.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 34.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewReaderSize` | 2.02MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.7GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.23GB |
| 3 | `reflect.growslice` | 18.36GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 17.94GB |
| 5 | `jackskj/carta.getUniqueId` | 16.16GB |
| 6 | `reflect.unsafe_New` | 14.62GB |
| 7 | `fmt.(*buffer).writeString` | 10.94GB |
| 8 | `carta/value.NewCell` | 10.41GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.79GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.46GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 370.84MB | 358.64MB | 221.52MB | 1.06MB |
| `evaluation.mergeMetadata` | 189.05MB | 182.55MB | 115.42MB | 0B |
| `local.(*Client).EvaluateV2` | 573.63MB | 559.86MB | 338.11MB | 1.58MB |
| `local.topologicalSort` | 83.02MB | 83.02MB | 47.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 575.64MB | 562.38MB | 338.86MB | 1.58MB |
| `localEvaluation.GetFeatureFlagPayload` | 51.66MB | 50.65MB | 32.27MB | 0B |
| `localEvaluation.getMapOfValue` | 575.64MB | 562.38MB | 338.86MB | 1.58MB |
| `utils.ParseFeatureFlag` | 576.14MB | 562.88MB | 339.36MB | 1.58MB |

**Total FF alloc (current snapshot):** 2.93GB  |  **24h avg:** 1.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1087 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1087 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 738/1087 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1087 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.71MB | 738/1087 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1087 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.31MB | 526/1087 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1087 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1087 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.55MB | 338/1087 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1087 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1087 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1087 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1087 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1087 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.98GB | 711/1087 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1087 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 642/1087 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1087 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.97GB | 475/1087 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.5x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 408.4MB at 2026-05-18T19:04 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
