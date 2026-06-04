# Overview: prod
*Last updated: 2026-06-04 10:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:15 (1078 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 30,304 | avg: 10,580 | max: 84,644 | trend: decreasing (-24.52/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▂▄▁▁▁▁▂▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▅█
```

**Heap InUse** (current: 622.9MB | avg: 157.2MB | max: 2823.8MB | trend: stable (-0.36MB/hr))
```
▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 35%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 30,304 | 23,535 | +6769 | 10,580 | 84,644 | decreasing (-24.52/hr) |
| Heap InUse | 622.9MB | 326.6MB | +296.3MB | 157.2MB | 2823.8MB | stable (-0.36MB/hr) |
| Heap Sys | 5075.5MB | 5103.7MB | -28.2MB | 2619.3MB | 6883.9MB | |
| Heap Objects | 3,071,763 | 775,362 | +2296401 | 677,083 | 14,090,816 | |

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
| 2026-06-04 | 124 | 15,439 | 237.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 83.3MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 40.69MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewReaderSize` | 35.15MB |
| 5 | `bufio.NewWriterSize` | 30.13MB |
| 6 | `runtime.mallocgc` | 16.51MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 13.01MB |
| 8 | `net/http.(*Transport).dialConn` | 9.5MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 8.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 12.88GB |
| 4 | `jackskj/carta.getUniqueId` | 11.35GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.41GB |
| 6 | `reflect.unsafe_New` | 10.14GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.98GB |
| 8 | `fmt.(*buffer).writeString` | 7.57GB |
| 9 | `carta/value.NewCell` | 7.2GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 306.85MB | 301.26MB | 172.45MB | 0B |
| `evaluation.mergeMetadata` | 157.04MB | 154.54MB | 90.91MB | 0B |
| `local.(*Client).EvaluateV2` | 474.38MB | 464.68MB | 260.68MB | 0B |
| `local.topologicalSort` | 70.38MB | 68.34MB | 35.94MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 478.95MB | 468.23MB | 260.64MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 42.50MB | 41.46MB | 26.21MB | 0B |
| `localEvaluation.getMapOfValue` | 478.95MB | 468.23MB | 260.64MB | 0B |
| `utils.ParseFeatureFlag` | 479.45MB | 468.73MB | 261.07MB | 0B |

**Total FF alloc (current snapshot):** 2.43GB  |  **24h avg:** 1.34GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1078 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1078 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 729/1078 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1078 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.61MB | 729/1078 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1078 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.16MB | 518/1078 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1078 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.4MB | 10/1078 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1078 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1078 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1078 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1078 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1078 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1078 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.91GB | 702/1078 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1078 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 633/1078 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1078 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.04GB | 468/1078 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
