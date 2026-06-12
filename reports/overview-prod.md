# Overview: prod
*Last updated: 2026-06-12 12:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T12:40 (3409 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,290 | avg: 14,429 | max: 84,644 | trend: INCREASING (+3.56/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 226.4MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,290 | 14,615 | +675 | 14,429 | 84,644 | INCREASING (+3.56/hr) |
| Heap InUse | 226.4MB | 140.3MB | +86.1MB | 239.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 306.1MB | 225.3MB | +80.8MB | 2679.5MB | 6883.9MB | |
| Heap Objects | 1,432,874 | 527,934 | +904940 | 1,028,341 | 17,165,538 | |

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
| 2026-06-12 | 153 | 16,614 | 304.3MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `bytes.growSlice` | 9.18MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 6.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1022.38MB |
| 2 | `jackskj/carta.getUniqueId` | 720.13MB |
| 3 | `reflect.growslice` | 657.8MB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 546.94MB |
| 5 | `reflect.unsafe_New` | 539.73MB |
| 6 | `reflect.unsafe_NewArray` | 527.34MB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 463.59MB |
| 8 | `carta/value.NewCell` | 397.03MB |
| 9 | `reflect.MakeSlice` | 300.51MB |
| 10 | `fmt.(*buffer).writeString` | 296.93MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 55.79MB | 44.09MB | 8.41GB | 0B |
| `evaluation.mergeMetadata` | 30.51MB | 22.01MB | 4.38GB | 0B |
| `local.(*Client).EvaluateV2` | 80.61MB | 63.76MB | 12.81GB | 0B |
| `local.topologicalSort` | 11.63MB | 9.10MB | 1.78GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 75.49MB | 60.17MB | 12.25GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 12.26MB | 8.68MB | 1.74GB | 0B |
| `localEvaluation.getMapOfValue` | 75.49MB | 60.17MB | 12.25GB | 0B |
| `utils.ParseFeatureFlag` | 75.49MB | 60.17MB | 12.27GB | 0B |

**Total FF alloc (current snapshot):** 417.26MB  |  **24h avg:** 65.89GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3409 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3409 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3060/3409 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.61MB | 3060/3409 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3409 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3409 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.89MB | 2404/3409 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3409 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3409 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3409 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3409 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3409 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3409 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.22GB | 1916/3409 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 65.22GB | 2621/3409 | `███████░░░░░░░░ 52%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.32GB | 2783/3409 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.76GB | 2637/3409 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 55.75GB | 2401/3409 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3409 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.58GB | 2140/3409 | `█████░░░░░░░░░░ 39%` |

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
