# Overview: prod
*Last updated: 2026-06-04 09:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T09:35 (1070 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,182 | avg: 10,514 | max: 84,644 | trend: decreasing (-25.82/hr))
```
▁▁▁▂▂▁▄▁▄▂▁▂▂▁▁▁▁▁▁▁▂▇▂▁▁▁▁▁▁▁▁▁▁▄▂▄█▂▁▁▂▄▁▂▂▂▃▁▃▃▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 207.4MB | avg: 156.2MB | max: 2823.8MB | trend: stable (-0.38MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,182 | 14,817 | +1365 | 10,514 | 84,644 | decreasing (-25.82/hr) |
| Heap InUse | 207.4MB | 176.0MB | +31.4MB | 156.2MB | 2823.8MB | stable (-0.38MB/hr) |
| Heap Sys | 5126.9MB | 5127.5MB | -0.6MB | 2600.6MB | 6883.9MB | |
| Heap Objects | 733,908 | 709,692 | +24216 | 672,998 | 14,090,816 | |

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
| 2026-06-04 | 116 | 15,168 | 234.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 18.88MB |
| 3 | `runtime.mallocgc` | 12.6MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 6 | `bufio.NewWriterSize` | 7.04MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `bufio.NewReaderSize` | 3.04MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 8.38GB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.26GB |
| 5 | `jackskj/carta.getUniqueId` | 7.14GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.82GB |
| 7 | `reflect.unsafe_New` | 6.46GB |
| 8 | `database/sql.convertAssignRows` | 5.88GB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.57GB |
| 10 | `fmt.(*buffer).writeString` | 4.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 249.62MB | 237.97MB | 131.15MB | 0B |
| `evaluation.mergeMetadata` | 128.53MB | 120.53MB | 70.02MB | 0B |
| `local.(*Client).EvaluateV2` | 383.53MB | 367.21MB | 196.39MB | 0B |
| `local.topologicalSort` | 54.69MB | 52.65MB | 26.28MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 383.94MB | 368.11MB | 196.15MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 36.41MB | 34.90MB | 20.47MB | 0B |
| `localEvaluation.getMapOfValue` | 383.94MB | 368.11MB | 196.15MB | 0B |
| `utils.ParseFeatureFlag` | 384.44MB | 368.61MB | 196.50MB | 0B |

**Total FF alloc (current snapshot):** 1.96GB  |  **24h avg:** 1.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1070 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1070 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 721/1070 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1070 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.69MB | 721/1070 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1070 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 12.91MB | 510/1070 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1070 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1070 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1070 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1070 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1070 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1070 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1070 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1070 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.84GB | 694/1070 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1070 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.5GB | 625/1070 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1070 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.15GB | 460/1070 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.1x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
