# Overview: prod
*Last updated: 2026-06-08 17:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T17:20 (2314 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,526 | avg: 13,544 | max: 84,644 | trend: INCREASING (+4.45/hr))
```
▁▁▁▁▁▁▁▃▃▄▅█▇▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 312.4MB | avg: 208.1MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▃▂▃▄▇█▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,526 | 17,283 | -757 | 13,544 | 84,644 | INCREASING (+4.45/hr) |
| Heap InUse | 312.4MB | 322.1MB | -9.7MB | 208.1MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 3331.5MB | 3331.5MB | +0.0MB | 2385.8MB | 6883.9MB | |
| Heap Objects | 878,281 | 756,044 | +122237 | 921,409 | 17,165,538 | |

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
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 209 | 16,728 | 311.7MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 20.25MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 8.55MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 9 | `bufio.NewReaderSize` | 4.02MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 71.25GB |
| 2 | `reflect.growslice` | 65.5GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.1GB |
| 4 | `jackskj/carta.getUniqueId` | 56.8GB |
| 5 | `reflect.unsafe_New` | 51.08GB |
| 6 | `fmt.(*buffer).writeString` | 40.92GB |
| 7 | `fmt.Sprintf` | 36.98GB |
| 8 | `carta/value.NewCell` | 36.47GB |
| 9 | `reflect.unsafe_NewArray` | 36.36GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 24.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.68GB | 2.67GB | 2.37GB | 0B |
| `evaluation.mergeMetadata` | 1.39GB | 1.39GB | 1.23GB | 0B |
| `local.(*Client).EvaluateV2` | 4.04GB | 4.03GB | 3.59GB | 0B |
| `local.topologicalSort` | 566.51MB | 564.98MB | 497.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.94GB | 3.93GB | 3.55GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 504.85MB | 500.19MB | 405.01MB | 0B |
| `localEvaluation.getMapOfValue` | 3.94GB | 3.93GB | 3.55GB | 0B |
| `utils.ParseFeatureFlag` | 3.95GB | 3.94GB | 3.55GB | 0B |

**Total FF alloc (current snapshot):** 20.99GB  |  **24h avg:** 18.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2314 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.79MB | 65/2314 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1965/2314 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.65MB | 88/2314 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 22.87MB | 1965/2314 | `████░░░░░░░░░░░ 26%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2314 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.52MB | 1443/2314 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2314 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2314 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2314 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2314 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2314 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2314 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2314 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2314 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2314 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2314 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 26.68GB | 831/2314 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 20.34GB | 1688/2314 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `reflect.growslice` | 18.35GB | 1526/2314 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
