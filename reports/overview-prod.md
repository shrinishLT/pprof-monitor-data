# Overview: prod
*Last updated: 2026-06-12 14:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T14:26 (3430 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,889 | avg: 14,433 | max: 84,644 | trend: INCREASING (+3.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.3MB | avg: 239.4MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,889 | 14,460 | +1429 | 14,433 | 84,644 | INCREASING (+3.51/hr) |
| Heap InUse | 193.3MB | 164.1MB | +29.2MB | 239.4MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 613.9MB | 613.7MB | +0.2MB | 2666.1MB | 6883.9MB | |
| Heap Objects | 666,688 | 887,160 | -220472 | 1,027,364 | 17,165,538 | |

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
| 2026-06-12 | 174 | 16,432 | 291.0MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 8.01MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `bufio.NewReaderSize` | 4.52MB |
| 8 | `bufio.NewWriterSize` | 4.02MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 3.98GB |
| 2 | `jackskj/carta.getUniqueId` | 3.72GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.35GB |
| 4 | `reflect.unsafe_New` | 3.22GB |
| 5 | `fmt.Sprintf` | 2.78GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.35GB |
| 7 | `fmt.(*buffer).writeString` | 2.3GB |
| 8 | `carta/value.NewCell` | 2.26GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.93GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 1.83GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 225.25MB | 220.12MB | 3.85GB | 0B |
| `evaluation.mergeMetadata` | 122.03MB | 119.03MB | 2.01GB | 0B |
| `local.(*Client).EvaluateV2` | 347.85MB | 335.42MB | 5.87GB | 0B |
| `local.topologicalSort` | 50.09MB | 48.07MB | 838.45MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 320.74MB | 309.84MB | 5.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 51.74MB | 49.69MB | 813.82MB | 0B |
| `localEvaluation.getMapOfValue` | 320.74MB | 309.84MB | 5.62GB | 0B |
| `utils.ParseFeatureFlag` | 321.24MB | 310.34MB | 5.62GB | 0B |

**Total FF alloc (current snapshot):** 1.72GB  |  **24h avg:** 30.20GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3430 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3430 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3081/3430 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.44MB | 3081/3430 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.45MB | 115/3430 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3430 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.83MB | 2423/3430 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3430 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3430 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3430 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3430 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3430 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3430 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3430 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.72GB | 2642/3430 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.86GB | 2804/3430 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.33GB | 2658/3430 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.29GB | 2422/3430 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3430 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.12GB | 2161/3430 | `█████░░░░░░░░░░ 39%` |

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
