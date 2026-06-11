# Overview: prod
*Last updated: 2026-06-12 01:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T01:01 (3269 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,209 | avg: 14,328 | max: 84,644 | trend: INCREASING (+3.65/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▂▂▂▃▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 353.3MB | avg: 236.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▂▁▁▂▂▂▂▂▁▁▂▁▁▁▂▃▃▃▂▃▁▂▂▂▁▁▁▁▂▂▃▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▂▁▁▁▁▁▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,209 | 17,725 | -1516 | 14,328 | 84,644 | INCREASING (+3.65/hr) |
| Heap InUse | 353.3MB | 322.1MB | +31.2MB | 236.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3306.1MB | 3304.8MB | +1.3MB | 2661.3MB | 6883.9MB | |
| Heap Objects | 1,336,005 | 701,850 | +634155 | 1,016,731 | 17,165,538 | |

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
| 2026-06-12 | 13 | 14,896 | 247.6MB | 353.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 14.13MB |
| 4 | `bufio.NewReaderSize` | 11.06MB |
| 5 | `bufio.NewWriterSize` | 10.07MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 180.61GB |
| 2 | `reflect.growslice` | 179.43GB |
| 3 | `jackskj/carta.getUniqueId` | 163.46GB |
| 4 | `reflect.unsafe_New` | 143.96GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.79GB |
| 6 | `fmt.Sprintf` | 134.23GB |
| 7 | `fmt.(*buffer).writeString` | 112.9GB |
| 8 | `carta/value.NewCell` | 102.81GB |
| 9 | `reflect.unsafe_NewArray` | 92.14GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.03GB | 10.02GB | 9.88GB | 0B |
| `evaluation.mergeMetadata` | 5.24GB | 5.23GB | 5.16GB | 0B |
| `local.(*Client).EvaluateV2` | 15.26GB | 15.25GB | 15.04GB | 0B |
| `local.topologicalSort` | 2.12GB | 2.12GB | 2.08GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.54GB | 14.53GB | 14.33GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.12GB | 2.11GB | 2.08GB | 0B |
| `localEvaluation.getMapOfValue` | 14.54GB | 14.53GB | 14.33GB | 0B |
| `utils.ParseFeatureFlag` | 14.56GB | 14.55GB | 14.35GB | 0B |

**Total FF alloc (current snapshot):** 78.38GB  |  **24h avg:** 77.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3269 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 49.51MB | 89/3269 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2920/3269 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.9MB | 2920/3269 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 26.83MB | 108/3269 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3269 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.69MB | 2291/3269 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3269 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3269 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3269 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3269 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3269 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3269 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 67.61GB | 1786/3269 | `████████░░░░░░░ 54%` |
| 5 | `reflect.growslice` | 58.95GB | 2481/3269 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 58.47GB | 2643/3269 | `███████░░░░░░░░ 46%` |
| 7 | `jackskj/carta.getUniqueId` | 52.04GB | 2497/3269 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3269 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.47GB | 2261/3269 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.14GB | 2008/3269 | `█████░░░░░░░░░░ 36%` |

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
