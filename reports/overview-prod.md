# Overview: prod
*Last updated: 2026-06-12 00:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T00:05 (3258 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,154 | avg: 14,326 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▂▂▂▂▃▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁
```

**Heap InUse** (current: 207.0MB | avg: 236.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▂▂▂▂▂▁▁▂▁▁▁▂▃▃▃▂▃▁▂▂▂▁▁▁▁▂▂▃▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▁▂▁▁▂▃▂▂▁▁▁▁▁▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,154 | 14,113 | +41 | 14,326 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 207.0MB | 260.0MB | -53.0MB | 236.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3304.1MB | 3304.1MB | +0.0MB | 2659.2MB | 6883.9MB | |
| Heap Objects | 871,699 | 1,575,202 | -703503 | 1,017,191 | 17,165,538 | |

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
| 2026-06-12 | 2 | 14,134 | 233.5MB | 260.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 179.36GB |
| 2 | `reflect.growslice` | 179.35GB |
| 3 | `jackskj/carta.getUniqueId` | 163.38GB |
| 4 | `reflect.unsafe_New` | 143.89GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.78GB |
| 6 | `fmt.Sprintf` | 133.7GB |
| 7 | `fmt.(*buffer).writeString` | 112.87GB |
| 8 | `carta/value.NewCell` | 102.76GB |
| 9 | `reflect.unsafe_NewArray` | 91.5GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 82.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.97GB | 9.97GB | 9.80GB | 0B |
| `evaluation.mergeMetadata` | 5.21GB | 5.21GB | 5.12GB | 0B |
| `local.(*Client).EvaluateV2` | 15.17GB | 15.17GB | 14.92GB | 0B |
| `local.topologicalSort` | 2.10GB | 2.10GB | 2.07GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.45GB | 14.45GB | 14.22GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.11GB | 2.11GB | 2.06GB | 0B |
| `localEvaluation.getMapOfValue` | 14.45GB | 14.45GB | 14.22GB | 0B |
| `utils.ParseFeatureFlag` | 14.48GB | 14.47GB | 14.24GB | 0B |

**Total FF alloc (current snapshot):** 77.94GB  |  **24h avg:** 76.64GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3258 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3258 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2909/3258 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.83MB | 2909/3258 | `████████░░░░░░░ 54%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3258 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3258 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.72MB | 2281/3258 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3258 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3258 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3258 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3258 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3258 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3258 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 67.14GB | 1775/3258 | `████████░░░░░░░ 53%` |
| 5 | `reflect.growslice` | 58.41GB | 2470/3258 | `███████░░░░░░░░ 46%` |
| 6 | `segmentio/kafka-go.makePartitions` | 57.96GB | 2632/3258 | `██████░░░░░░░░░ 46%` |
| 7 | `jackskj/carta.getUniqueId` | 51.55GB | 2486/3258 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3258 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.01GB | 2250/3258 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 44.77GB | 1997/3258 | `█████░░░░░░░░░░ 35%` |

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
