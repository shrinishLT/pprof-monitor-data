# Overview: prod
*Last updated: 2026-06-04 12:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T12:55 (1110 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 21,180 | avg: 10,928 | max: 84,644 | trend: decreasing (-18.85/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂
```

**Heap InUse** (current: 444.7MB | avg: 164.5MB | max: 2823.8MB | trend: stable (-0.25MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 25%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 21,180 | 21,786 | -606 | 10,928 | 84,644 | decreasing (-18.85/hr) |
| Heap InUse | 444.7MB | 468.6MB | -23.9MB | 164.5MB | 2823.8MB | stable (-0.25MB/hr) |
| Heap Sys | 1146.8MB | 1148.0MB | -1.2MB | 2626.6MB | 6883.9MB | |
| Heap Objects | 1,992,888 | 1,969,423 | +23465 | 707,682 | 14,090,816 | |

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
| 2026-06-04 | 156 | 16,919 | 273.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 46.59MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 20.6MB |
| 4 | `bufio.NewReaderSize` | 15.56MB |
| 5 | `runtime.mallocgc` | 11.6MB |
| 6 | `bufio.NewWriterSize` | 11.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.01MB |
| 9 | `net/http.(*Transport).dialConn` | 5.0MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 3.18GB |
| 2 | `jackskj/carta.getUniqueId` | 2.92GB |
| 3 | `fmt.Sprintf` | 2.61GB |
| 4 | `reflect.unsafe_New` | 2.57GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 2.2GB |
| 6 | `segmentio/kafka-go.makePartitions` | 1.96GB |
| 7 | `fmt.(*buffer).writeString` | 1.84GB |
| 8 | `carta/value.NewCell` | 1.83GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.39GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.39GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 169.03MB | 163.42MB | 221.61MB | 0B |
| `evaluation.mergeMetadata` | 96.02MB | 92.52MB | 115.38MB | 0B |
| `local.(*Client).EvaluateV2` | 246.01MB | 236.85MB | 338.04MB | 0B |
| `local.topologicalSort` | 32.86MB | 30.33MB | 47.77MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 230.11MB | 219.40MB | 336.73MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 38.41MB | 38.41MB | 33.38MB | 0B |
| `localEvaluation.getMapOfValue` | 230.11MB | 219.40MB | 336.73MB | 0B |
| `utils.ParseFeatureFlag` | 230.11MB | 219.40MB | 337.10MB | 0B |

**Total FF alloc (current snapshot):** 1.24GB  |  **24h avg:** 1.73GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1110 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1110 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 761/1110 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1110 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.53MB | 761/1110 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1110 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.18MB | 548/1110 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1110 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1110 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.57MB | 347/1110 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1110 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1110 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1110 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1110 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1110 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.02GB | 734/1110 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1110 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.06GB | 662/1110 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.06GB | 353/1110 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.6GB | 495/1110 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
