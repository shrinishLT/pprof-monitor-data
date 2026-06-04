# Overview: prod
*Last updated: 2026-06-04 10:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:10 (1077 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,535 | avg: 10,562 | max: 84,644 | trend: decreasing (-24.79/hr))
```
▁▃▂▁▁▂▁▁▁▁▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▄▂▃▆▁▁▁▂▄▁▁▁▁▃▁▂▃▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▂▄▅█
```

**Heap InUse** (current: 326.6MB | avg: 156.7MB | max: 2823.8MB | trend: stable (-0.37MB/hr))
```
▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,535 | 20,238 | +3297 | 10,562 | 84,644 | decreasing (-24.79/hr) |
| Heap InUse | 326.6MB | 332.5MB | -5.9MB | 156.7MB | 2823.8MB | stable (-0.37MB/hr) |
| Heap Sys | 5103.7MB | 5115.5MB | -11.8MB | 2617.0MB | 6883.9MB | |
| Heap Objects | 775,362 | 1,565,717 | -790355 | 674,860 | 14,090,816 | |

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
| 2026-06-04 | 123 | 15,318 | 234.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 54.29MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewWriterSize` | 26.62MB |
| 4 | `bufio.NewReaderSize` | 21.6MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 19.09MB |
| 6 | `runtime.mallocgc` | 14.51MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `reflect.growslice` | 9.24MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.01MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 7.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 12.05GB |
| 4 | `jackskj/carta.getUniqueId` | 10.6GB |
| 5 | `reflect.unsafe_New` | 9.47GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.19GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.86GB |
| 8 | `fmt.(*buffer).writeString` | 7.07GB |
| 9 | `carta/value.NewCell` | 6.71GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.36GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 301.26MB | 293.15MB | 167.12MB | 0B |
| `evaluation.mergeMetadata` | 154.54MB | 149.54MB | 88.26MB | 0B |
| `local.(*Client).EvaluateV2` | 464.68MB | 450.30MB | 252.34MB | 0B |
| `local.topologicalSort` | 68.34MB | 66.83MB | 34.62MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 468.23MB | 454.89MB | 252.20MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 41.46MB | 40.42MB | 25.57MB | 0B |
| `localEvaluation.getMapOfValue` | 468.23MB | 454.89MB | 252.20MB | 0B |
| `utils.ParseFeatureFlag` | 468.73MB | 455.39MB | 252.61MB | 0B |

**Total FF alloc (current snapshot):** 2.38GB  |  **24h avg:** 1.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1077 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1077 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 728/1077 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1077 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.62MB | 728/1077 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1077 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.03MB | 517/1077 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1077 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1077 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1077 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1077 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1077 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1077 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1077 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1077 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.9GB | 701/1077 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1077 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 632/1077 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1077 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.05GB | 467/1077 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
