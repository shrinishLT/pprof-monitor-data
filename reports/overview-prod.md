# Overview: prod
*Last updated: 2026-06-04 12:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T12:45 (1108 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,937 | avg: 10,909 | max: 84,644 | trend: decreasing (-19.16/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 454.9MB | avg: 164.0MB | max: 2823.8MB | trend: stable (-0.26MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,937 | 19,265 | +2672 | 10,909 | 84,644 | decreasing (-19.16/hr) |
| Heap InUse | 454.9MB | 302.9MB | +152.0MB | 164.0MB | 2823.8MB | stable (-0.26MB/hr) |
| Heap Sys | 1149.0MB | 1163.1MB | -14.1MB | 2629.2MB | 6883.9MB | |
| Heap Objects | 1,865,741 | 1,070,396 | +795345 | 705,384 | 14,090,816 | |

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
| 2026-06-04 | 154 | 16,859 | 271.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 52.85MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 23.59MB |
| 4 | `bufio.NewReaderSize` | 19.57MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 6 | `runtime.mallocgc` | 11.6MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 9.01MB |
| 9 | `crypto/tls.Client` | 6.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 6.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 2.92GB |
| 2 | `jackskj/carta.getUniqueId` | 2.64GB |
| 3 | `reflect.unsafe_New` | 2.31GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.2GB |
| 5 | `fmt.Sprintf` | 1.78GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.74GB |
| 7 | `fmt.(*buffer).writeString` | 1.67GB |
| 8 | `carta/value.NewCell` | 1.64GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.15GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 961.13MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 152.79MB | 142.67MB | 222.64MB | 0B |
| `evaluation.mergeMetadata` | 86.52MB | 80.02MB | 115.65MB | 0B |
| `local.(*Client).EvaluateV2` | 219.89MB | 202.58MB | 339.84MB | 0B |
| `local.topologicalSort` | 29.33MB | 25.29MB | 47.98MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 203.06MB | 188.81MB | 339.28MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 35.25MB | 31.69MB | 32.89MB | 0B |
| `localEvaluation.getMapOfValue` | 203.06MB | 188.81MB | 339.28MB | 0B |
| `utils.ParseFeatureFlag` | 203.06MB | 188.81MB | 339.67MB | 0B |

**Total FF alloc (current snapshot):** 1.11GB  |  **24h avg:** 1.74GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1108 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1108 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 759/1108 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1108 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.55MB | 759/1108 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1108 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.07MB | 546/1108 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1108 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1108 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.51MB | 345/1108 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1108 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1108 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1108 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1108 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1108 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.13GB | 732/1108 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1108 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.06GB | 662/1108 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.12GB | 351/1108 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.64GB | 493/1108 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
