# Overview: prod
*Last updated: 2026-06-12 15:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T15:16 (3440 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,226 | avg: 14,436 | max: 84,644 | trend: INCREASING (+3.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 251.9MB | avg: 239.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,226 | 17,514 | -1288 | 14,436 | 84,644 | INCREASING (+3.49/hr) |
| Heap InUse | 251.9MB | 241.2MB | +10.7MB | 239.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 609.5MB | 610.7MB | -1.2MB | 2660.1MB | 6883.9MB | |
| Heap Objects | 1,201,258 | 543,030 | +658228 | 1,027,154 | 17,165,538 | |

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
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 184 | 16,384 | 286.8MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.11MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 8.01MB |
| 6 | `bufio.NewReaderSize` | 7.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 9 | `bufio.NewWriterSize` | 3.51MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.5GB |
| 2 | `reflect.growslice` | 4.37GB |
| 3 | `jackskj/carta.getUniqueId` | 4.3GB |
| 4 | `fmt.Sprintf` | 3.81GB |
| 5 | `reflect.unsafe_New` | 3.6GB |
| 6 | `carta/value.NewCell` | 2.54GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.46GB |
| 8 | `fmt.(*buffer).writeString` | 2.46GB |
| 9 | `reflect.unsafe_NewArray` | 2.33GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 2.18GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 301.94MB | 298.88MB | 1.69GB | 0B |
| `evaluation.mergeMetadata` | 161.54MB | 160.04MB | 904.54MB | 0B |
| `local.(*Client).EvaluateV2` | 468.49MB | 461.80MB | 2.57GB | 0B |
| `local.topologicalSort` | 66.28MB | 64.75MB | 367.39MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 434.76MB | 429.65MB | 2.46GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 69.14MB | 67.04MB | 358.79MB | 0B |
| `localEvaluation.getMapOfValue` | 434.76MB | 429.65MB | 2.46GB | 0B |
| `utils.ParseFeatureFlag` | 435.76MB | 430.65MB | 2.46GB | 0B |

**Total FF alloc (current snapshot):** 2.32GB  |  **24h avg:** 13.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.03MB | 66/3440 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3440 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3091/3440 | `██████████░░░░░ 67%` |
| 4 | `runtime.mallocgc` | 32.36MB | 3091/3440 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.26MB | 116/3440 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3440 | `████░░░░░░░░░░░ 33%` |
| 7 | `bytes.growSlice` | 15.81MB | 2433/3440 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3440 | `███░░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3440 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3440 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3440 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3440 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3440 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3440 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.5GB | 2652/3440 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.65GB | 2814/3440 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.13GB | 2668/3440 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.07GB | 2432/3440 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3440 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.91GB | 2171/3440 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
