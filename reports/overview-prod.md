# Overview: prod
*Last updated: 2026-06-04 10:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:20 (1079 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 36,441 | avg: 10,604 | max: 84,644 | trend: decreasing (-24.19/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▆█
```

**Heap InUse** (current: 632.4MB | avg: 157.6MB | max: 2823.8MB | trend: stable (-0.35MB/hr))
```
▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 43%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 36,441 | 30,304 | +6137 | 10,604 | 84,644 | decreasing (-24.19/hr) |
| Heap InUse | 632.4MB | 622.9MB | +9.5MB | 157.6MB | 2823.8MB | stable (-0.35MB/hr) |
| Heap Sys | 5047.8MB | 5075.5MB | -27.7MB | 2621.5MB | 6883.9MB | |
| Heap Objects | 1,766,796 | 3,071,763 | -1304967 | 678,093 | 14,090,816 | |

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
| 2026-06-04 | 125 | 15,607 | 241.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 125.12MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 51.24MB |
| 3 | `bufio.NewReaderSize` | 50.21MB |
| 4 | `bufio.NewWriterSize` | 42.17MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 24.52MB |
| 7 | `runtime.mallocgc` | 22.22MB |
| 8 | `crypto/tls.Client` | 12.51MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 11.01MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 13.96GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.53GB |
| 5 | `jackskj/carta.getUniqueId` | 12.34GB |
| 6 | `reflect.unsafe_New` | 10.98GB |
| 7 | `fmt.(*buffer).writeString` | 8.23GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.13GB |
| 9 | `carta/value.NewCell` | 7.82GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.58GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 316.39MB | 306.85MB | 177.86MB | 0B |
| `evaluation.mergeMetadata` | 163.54MB | 157.04MB | 93.64MB | 0B |
| `local.(*Client).EvaluateV2` | 488.60MB | 474.38MB | 269.14MB | 0B |
| `local.topologicalSort` | 72.41MB | 70.38MB | 37.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 493.68MB | 478.95MB | 269.21MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 43.50MB | 42.50MB | 26.87MB | 0B |
| `localEvaluation.getMapOfValue` | 493.68MB | 478.95MB | 269.21MB | 0B |
| `utils.ParseFeatureFlag` | 494.18MB | 479.45MB | 269.65MB | 0B |

**Total FF alloc (current snapshot):** 2.51GB  |  **24h avg:** 1.38GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1079 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1079 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 730/1079 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1079 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.61MB | 730/1079 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1079 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.38MB | 519/1079 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1079 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.4MB | 10/1079 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1079 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1079 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1079 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1079 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1079 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1079 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.91GB | 703/1079 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1079 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 634/1079 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1079 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.03GB | 469/1079 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
