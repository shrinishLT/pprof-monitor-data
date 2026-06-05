# Overview: prod
*Last updated: 2026-06-05 10:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:01 (1363 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,992 | avg: 11,783 | max: 84,644 | trend: decreasing (-4.17/hr))
```
▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▂▂▄▃▄▆▆▁▁▁▁▁▁▂▂▁▇▃▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▁▁▂▁▁▃▁▁▁▂▂▂▁▃▂▃▂▃▆
```

**Heap InUse** (current: 241.3MB | avg: 179.9MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,992 | 15,527 | +1465 | 11,783 | 84,644 | decreasing (-4.17/hr) |
| Heap InUse | 241.3MB | 250.6MB | -9.3MB | 179.9MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4420.8MB | 4420.5MB | +0.3MB | 2695.5MB | 6883.9MB | |
| Heap Objects | 1,267,285 | 1,309,959 | -42674 | 802,698 | 17,165,538 | |

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
| 2026-06-05 | 121 | 14,886 | 238.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 13.57MB |
| 3 | `runtime.mallocgc` | 13.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 8.53MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `bufio.NewWriterSize` | 5.52MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 2 | `jackskj/carta.getUniqueId` | 4.4GB |
| 3 | `reflect.growslice` | 4.36GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.14GB |
| 5 | `reflect.unsafe_New` | 3.63GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |
| 7 | `fmt.Sprintf` | 2.68GB |
| 8 | `carta/value.NewCell` | 2.59GB |
| 9 | `fmt.(*buffer).writeString` | 2.53GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 2.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 223.68MB | 216.50MB | 152.45MB | 0B |
| `evaluation.mergeMetadata` | 111.53MB | 109.53MB | 77.26MB | 0B |
| `local.(*Client).EvaluateV2` | 335.89MB | 322.49MB | 228.69MB | 0B |
| `local.topologicalSort` | 45.53MB | 42.99MB | 32.85MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 352.72MB | 338.80MB | 232.70MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 18.01MB | 18.01MB | 19.67MB | 0B |
| `localEvaluation.getMapOfValue` | 352.72MB | 338.80MB | 232.70MB | 0B |
| `utils.ParseFeatureFlag` | 352.72MB | 338.80MB | 232.91MB | 0B |

**Total FF alloc (current snapshot):** 1.75GB  |  **24h avg:** 1.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1363 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1363 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1363 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1014/1363 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1363 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.99MB | 1014/1363 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.06MB | 777/1363 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1363 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1363 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.71MB | 17/1363 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1363 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1363 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1363 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1363 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1363 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.16GB | 985/1363 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1363 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.12GB | 908/1363 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.54GB | 188/1363 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.47GB | 563/1363 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
