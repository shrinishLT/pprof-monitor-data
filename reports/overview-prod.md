# Overview: prod
*Last updated: 2026-06-04 10:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:55 (1086 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 29,870 | avg: 10,822 | max: 84,644 | trend: decreasing (-21.33/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃
```

**Heap InUse** (current: 891.9MB | avg: 163.2MB | max: 2823.8MB | trend: stable (-0.29MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 35%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 29,870 | 55,469 | -25599 | 10,822 | 84,644 | decreasing (-21.33/hr) |
| Heap InUse | 891.9MB | 1070.9MB | -179.0MB | 163.2MB | 2823.8MB | stable (-0.29MB/hr) |
| Heap Sys | 5003.9MB | 4961.5MB | +42.4MB | 2636.9MB | 6883.9MB | |
| Heap Objects | 3,583,373 | 2,758,063 | +825310 | 700,647 | 14,090,816 | |

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
| 2026-06-04 | 132 | 17,133 | 282.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 127.66MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 57.26MB |
| 3 | `bufio.NewReaderSize` | 52.21MB |
| 4 | `bufio.NewWriterSize` | 47.19MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 34.36MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 25.02MB |
| 8 | `net/http.(*Transport).dialConn` | 14.5MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 14.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 18.29GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 17.87GB |
| 5 | `jackskj/carta.getUniqueId` | 16.09GB |
| 6 | `reflect.unsafe_New` | 14.55GB |
| 7 | `fmt.(*buffer).writeString` | 10.89GB |
| 8 | `carta/value.NewCell` | 10.36GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.77GB |
| 10 | `fmt.Sprintf` | 7.39GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 358.64MB | 353.04MB | 215.82MB | 0B |
| `evaluation.mergeMetadata` | 182.55MB | 180.04MB | 112.65MB | 0B |
| `local.(*Client).EvaluateV2` | 559.86MB | 551.17MB | 329.25MB | 0B |
| `local.topologicalSort` | 83.02MB | 82.01MB | 46.57MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 562.38MB | 553.22MB | 329.96MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 50.65MB | 49.61MB | 31.55MB | 0B |
| `localEvaluation.getMapOfValue` | 562.38MB | 553.22MB | 329.96MB | 0B |
| `utils.ParseFeatureFlag` | 562.88MB | 553.72MB | 330.46MB | 0B |

**Total FF alloc (current snapshot):** 2.85GB  |  **24h avg:** 1.69GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1086 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1086 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 737/1086 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1086 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.69MB | 737/1086 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1086 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.31MB | 526/1086 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1086 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1086 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.55MB | 338/1086 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1086 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1086 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1086 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1086 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1086 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.97GB | 710/1086 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1086 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 641/1086 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1086 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.98GB | 474/1086 | `█░░░░░░░░░░░░░░ 9%` |

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
