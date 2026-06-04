# Overview: prod
*Last updated: 2026-06-04 10:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:50 (1085 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 55,469 | avg: 10,804 | max: 84,644 | trend: decreasing (-21.58/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇
```

**Heap InUse** (current: 1070.9MB | avg: 162.5MB | max: 2823.8MB | trend: stable (-0.29MB/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▃▄▃▃
```

## Current Status

Goroutines: `█████████████░░░░░░░ 65%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 55,469 | 59,354 | -3885 | 10,804 | 84,644 | decreasing (-21.58/hr) |
| Heap InUse | 1070.9MB | 1253.0MB | -182.1MB | 162.5MB | 2823.8MB | stable (-0.29MB/hr) |
| Heap Sys | 4961.5MB | 4954.0MB | +7.5MB | 2634.7MB | 6883.9MB | |
| Heap Objects | 2,758,063 | 4,440,397 | -1682334 | 697,990 | 14,090,816 | |

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
| 2026-06-04 | 131 | 17,036 | 277.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 192.01MB |
| 2 | `bufio.NewWriterSize` | 92.87MB |
| 3 | `bufio.NewReaderSize` | 87.85MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 77.36MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 34.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 28.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 22.52MB |
| 9 | `net/http.(*Transport).dialConn` | 21.5MB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.48MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 18.0GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 17.42GB |
| 5 | `jackskj/carta.getUniqueId` | 15.82GB |
| 6 | `reflect.unsafe_New` | 14.31GB |
| 7 | `fmt.(*buffer).writeString` | 10.72GB |
| 8 | `carta/value.NewCell` | 10.19GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.73GB |
| 10 | `fmt.Sprintf` | 7.28GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 353.04MB | 348.50MB | 210.28MB | 0B |
| `evaluation.mergeMetadata` | 180.04MB | 177.54MB | 109.93MB | 0B |
| `local.(*Client).EvaluateV2` | 551.17MB | 544.03MB | 320.50MB | 0B |
| `local.topologicalSort` | 82.01MB | 81.00MB | 45.23MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 553.22MB | 546.08MB | 321.14MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 49.61MB | 49.61MB | 30.84MB | 0B |
| `localEvaluation.getMapOfValue` | 553.22MB | 546.08MB | 321.14MB | 0B |
| `utils.ParseFeatureFlag` | 553.72MB | 546.58MB | 321.64MB | 0B |

**Total FF alloc (current snapshot):** 2.81GB  |  **24h avg:** 1.64GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1085 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1085 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 736/1085 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1085 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.67MB | 736/1085 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1085 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.1MB | 525/1085 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.64MB | 14/1085 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1085 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1085 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1085 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1085 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1085 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1085 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1085 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.96GB | 709/1085 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1085 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 640/1085 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.21GB | 348/1085 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.98GB | 474/1085 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.5x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 408.4MB at 2026-05-18T19:04 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
