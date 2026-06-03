# Overview: prod
*Last updated: 2026-06-04 04:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T04:25 (1008 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,448 | avg: 10,241 | max: 84,644 | trend: decreasing (-34.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆
```

**Heap InUse** (current: 319.6MB | avg: 152.8MB | max: 2823.8MB | trend: stable (-0.50MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,448 | 14,596 | +3852 | 10,241 | 84,644 | decreasing (-34.32/hr) |
| Heap InUse | 319.6MB | 159.8MB | +159.8MB | 152.8MB | 2823.8MB | stable (-0.50MB/hr) |
| Heap Sys | 4528.4MB | 4528.8MB | -0.4MB | 2579.7MB | 6883.9MB | |
| Heap Objects | 1,178,387 | 465,247 | +713140 | 654,546 | 14,090,816 | |

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
| 2026-06-04 | 54 | 15,414 | 260.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 26.9MB |
| 3 | `runtime.mallocgc` | 14.13MB |
| 4 | `bufio.NewReaderSize` | 11.06MB |
| 5 | `bufio.NewWriterSize` | 9.54MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.04MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `net/http.(*Transport).dialConn` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.41GB |
| 2 | `fmt.Sprintf` | 5.22GB |
| 3 | `jackskj/carta.getUniqueId` | 4.68GB |
| 4 | `reflect.growslice` | 4.52GB |
| 5 | `reflect.unsafe_New` | 3.94GB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.81GB |
| 7 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.37GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 3.34GB |
| 9 | `fmt.(*buffer).writeString` | 3.08GB |
| 10 | `carta/value.NewCell` | 2.78GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 178.15MB | 172.13MB | 91.44MB | 0B |
| `evaluation.mergeMetadata` | 96.52MB | 93.02MB | 47.71MB | 0B |
| `local.(*Client).EvaluateV2` | 274.27MB | 265.68MB | 141.16MB | 0B |
| `local.topologicalSort` | 40.55MB | 39.02MB | 22.97MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 267.26MB | 258.67MB | 133.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.35MB | 22.35MB | 15.99MB | 0B |
| `localEvaluation.getMapOfValue` | 267.26MB | 258.67MB | 133.93MB | 0B |
| `utils.ParseFeatureFlag` | 267.26MB | 258.67MB | 134.02MB | 0B |

**Total FF alloc (current snapshot):** 1.38GB  |  **24h avg:** 721.16MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 67.61MB | 27/1008 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1008 | `█████████████░░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 659/1008 | `████████░░░░░░░ 54%` |
| 4 | `database/sql.convertAssignRows` | 33.77MB | 35/1008 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.45MB | 659/1008 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1008 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 13.16MB | 466/1008 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 17/1008 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1008 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1008 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1008 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1008 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1008 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1008 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 44.06GB | 636/1008 | `█████░░░░░░░░░░ 35%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1008 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1008 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.9GB | 579/1008 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.91GB | 326/1008 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1008 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.3x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
