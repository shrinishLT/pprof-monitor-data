# Overview: prod
*Last updated: 2026-06-04 10:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:25 (1080 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,817 | avg: 10,618 | max: 84,644 | trend: decreasing (-23.96/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▆█▄
```

**Heap InUse** (current: 491.7MB | avg: 157.9MB | max: 2823.8MB | trend: stable (-0.35MB/hr))
```
▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 30%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,817 | 36,441 | -10624 | 10,618 | 84,644 | decreasing (-23.96/hr) |
| Heap InUse | 491.7MB | 632.4MB | -140.7MB | 157.9MB | 2823.8MB | stable (-0.35MB/hr) |
| Heap Sys | 5071.0MB | 5047.8MB | +23.2MB | 2623.8MB | 6883.9MB | |
| Heap Objects | 1,876,366 | 1,766,796 | +109570 | 679,202 | 14,090,816 | |

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
| 2026-06-04 | 126 | 15,688 | 243.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 57.79MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bufio.NewReaderSize` | 27.11MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 26.62MB |
| 5 | `bufio.NewWriterSize` | 23.1MB |
| 6 | `runtime.mallocgc` | 22.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 15.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 5.5MB |
| 10 | `net/http.(*Transport).dialConn` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 14.42GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.9GB |
| 5 | `jackskj/carta.getUniqueId` | 12.76GB |
| 6 | `reflect.unsafe_New` | 11.37GB |
| 7 | `fmt.(*buffer).writeString` | 8.49GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.2GB |
| 9 | `carta/value.NewCell` | 8.11GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.7GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 322.98MB | 316.39MB | 183.25MB | 0B |
| `evaluation.mergeMetadata` | 167.54MB | 163.54MB | 96.38MB | 0B |
| `local.(*Client).EvaluateV2` | 498.82MB | 488.60MB | 277.56MB | 0B |
| `local.topologicalSort` | 72.92MB | 72.41MB | 38.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 504.43MB | 493.68MB | 277.77MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 43.50MB | 43.50MB | 27.48MB | 0B |
| `localEvaluation.getMapOfValue` | 504.43MB | 493.68MB | 277.77MB | 0B |
| `utils.ParseFeatureFlag` | 504.93MB | 494.18MB | 278.22MB | 0B |

**Total FF alloc (current snapshot):** 2.56GB  |  **24h avg:** 1.42GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1080 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1080 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 731/1080 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1080 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.61MB | 731/1080 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1080 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.46MB | 520/1080 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1080 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 9.95MB | 11/1080 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1080 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1080 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1080 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1080 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1080 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1080 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.92GB | 704/1080 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1080 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 635/1080 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1080 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.02GB | 470/1080 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
