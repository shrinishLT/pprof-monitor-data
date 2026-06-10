# Overview: prod
*Last updated: 2026-06-10 20:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T20:26 (2926 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,311 | avg: 14,108 | max: 84,644 | trend: INCREASING (+4.06/hr))
```
▁▃▃▃▂▁▁▂▂▂▃▂▂▁▁▁▁▄▇█▇▆▂▁▁▁▂▂▂▂▁▂▁▁▃▂▁▂▂▁▂▂▂▁▁▁▂▂▂▂▁▁▁▂▅▂▁▁▁▁▁▁▁▃▄▁▂▃▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▁▁▁▆▁▃▄▃
```

**Heap InUse** (current: 298.1MB | avg: 228.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▄▄▃▅▂▂▂▃▄▅▃▃▄▁▁▁▆█▆▆▆▆▃▄▂▃▂▃▃▂▆▂▂▃▃▄▃▂▂▃▂▂▂▁▃▄▃▅▂▃▂▃▄▅▄▂▁▃▁▃▁▁▃▅▂▂▄▆▅▄▄▄▂▃▂▂▂▄▅▄▄▅▂▁▃▅▃▄▃▁▆▃▄▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,311 | 16,913 | -602 | 14,108 | 84,644 | INCREASING (+4.06/hr) |
| Heap InUse | 298.1MB | 307.7MB | -9.6MB | 228.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3342.4MB | 3342.2MB | +0.2MB | 2583.1MB | 6883.9MB | |
| Heap Objects | 633,766 | 701,316 | -67550 | 987,672 | 17,165,538 | |

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
| 2026-06-10 | 245 | 16,646 | 309.3MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 20.19MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `bufio.NewReaderSize` | 6.02MB |
| 8 | `bufio.NewWriterSize` | 5.02MB |
| 9 | `reflect.unsafe_NewArray` | 3.53MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 141.24GB |
| 2 | `reflect.growslice` | 138.64GB |
| 3 | `jackskj/carta.getUniqueId` | 124.19GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.82GB |
| 5 | `reflect.unsafe_New` | 109.89GB |
| 6 | `fmt.Sprintf` | 96.92GB |
| 7 | `fmt.(*buffer).writeString` | 87.43GB |
| 8 | `carta/value.NewCell` | 78.55GB |
| 9 | `reflect.unsafe_NewArray` | 72.18GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.35GB | 7.34GB | 7.15GB | 0B |
| `evaluation.mergeMetadata` | 3.85GB | 3.85GB | 3.75GB | 0B |
| `local.(*Client).EvaluateV2` | 11.20GB | 11.19GB | 10.90GB | 0B |
| `local.topologicalSort` | 1.56GB | 1.56GB | 1.52GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.67GB | 10.66GB | 10.40GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.55GB | 1.55GB | 1.50GB | 0B |
| `localEvaluation.getMapOfValue` | 10.67GB | 10.66GB | 10.40GB | 0B |
| `utils.ParseFeatureFlag` | 10.68GB | 10.68GB | 10.41GB | 0B |

**Total FF alloc (current snapshot):** 57.52GB  |  **24h avg:** 56.02GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 66.73MB | 52/2926 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2926 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2577/2926 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.43MB | 2577/2926 | `██████░░░░░░░░░ 44%` |
| 5 | `database/sql.convertAssignRows` | 28.37MB | 101/2926 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2926 | `████░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.69MB | 1985/2926 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2926 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2926 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2926 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2926 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2926 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2926 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 52.49GB | 1443/2926 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2926 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2926 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 43.18GB | 2300/2926 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 42.29GB | 2138/2926 | `█████░░░░░░░░░░ 33%` |
| 9 | `jackskj/carta.getUniqueId` | 36.9GB | 2154/2926 | `████░░░░░░░░░░░ 29%` |
| 10 | `reflect.unsafe_New` | 36.28GB | 1918/2926 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
