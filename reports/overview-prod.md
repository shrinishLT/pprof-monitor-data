# Overview: prod
*Last updated: 2026-06-12 08:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T08:20 (3357 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,323 | avg: 14,341 | max: 84,644 | trend: INCREASING (+3.41/hr))
```
▂▁▁▂▂▂▇▄▂▂▂▁▁▂▃▁▂▁▃▃▃▂▁▁▁▁▂▃▃▁▁▁▁▂▂█▂▁▂▂▃▂▂▂▃▂▁▃▄▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▂▂▂▂▂▂▆▃▂▂▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁▁▁▄
```

**Heap InUse** (current: 350.4MB | avg: 237.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▂▂▃▁▃▆▇▅▂▄▄▃▅▄▂▅▁▂▃▃▅▁▅▁▁▂▅▄▂▄▃▂▂▄█▃▄▃▃▃▆▃▂▇▃▁▅▅▂▁▃▃▄▄▆▃▃▄▄▂▄▁▁▄▄▄▄▂▄▅▅▇▆▃▂▅▁▄▆▄▁▄▃▁▄▁▃▆▂▂▁▁▄▂▇
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,323 | 14,226 | +2097 | 14,341 | 84,644 | INCREASING (+3.41/hr) |
| Heap InUse | 350.4MB | 231.6MB | +118.8MB | 237.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3337.8MB | 3342.0MB | -4.2MB | 2679.0MB | 6883.9MB | |
| Heap Objects | 1,668,921 | 1,143,223 | +525698 | 1,018,505 | 17,165,538 | |

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
| 2026-06-12 | 101 | 14,837 | 259.6MB | 361.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 12.09MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `bufio.NewReaderSize` | 5.03MB |
| 8 | `bufio.NewWriterSize` | 3.53MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 193.55GB |
| 2 | `segmentio/kafka-go.makePartitions` | 190.83GB |
| 3 | `jackskj/carta.getUniqueId` | 174.59GB |
| 4 | `reflect.unsafe_New` | 154.19GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 151.82GB |
| 6 | `fmt.Sprintf` | 140.31GB |
| 7 | `fmt.(*buffer).writeString` | 121.1GB |
| 8 | `carta/value.NewCell` | 110.22GB |
| 9 | `reflect.unsafe_NewArray` | 97.32GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 86.58GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.48GB | 10.47GB | 10.37GB | 0B |
| `evaluation.mergeMetadata` | 5.46GB | 5.46GB | 5.41GB | 0B |
| `local.(*Client).EvaluateV2` | 15.96GB | 15.95GB | 15.79GB | 0B |
| `local.topologicalSort` | 2.22GB | 2.22GB | 2.20GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.24GB | 15.24GB | 15.07GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.18GB | 2.18GB | 2.17GB | 0B |
| `localEvaluation.getMapOfValue` | 15.24GB | 15.24GB | 15.07GB | 0B |
| `utils.ParseFeatureFlag` | 15.27GB | 15.26GB | 15.10GB | 512.56kB |

**Total FF alloc (current snapshot):** 82.05GB  |  **24h avg:** 81.18GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.55MB | 64/3357 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.55MB | 91/3357 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3008/3357 | `█████████░░░░░░ 65%` |
| 4 | `runtime.mallocgc` | 32.44MB | 3008/3357 | `████████░░░░░░░ 58%` |
| 5 | `database/sql.convertAssignRows` | 25.78MB | 113/3357 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3357 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.42MB | 2363/3357 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3357 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3357 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3357 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3357 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3357 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3357 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.33GB | 1874/3357 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 63.27GB | 2569/3357 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.58GB | 2731/3357 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.0GB | 2585/3357 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 54.13GB | 2349/3357 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3357 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.13GB | 2096/3357 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
