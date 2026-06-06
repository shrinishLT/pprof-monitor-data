# Overview: prod
*Last updated: 2026-06-06 12:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T12:35 (1681 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,107 | avg: 12,764 | max: 84,644 | trend: INCREASING (+3.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 236.1MB | avg: 194.7MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,107 | 14,970 | +137 | 12,764 | 84,644 | INCREASING (+3.42/hr) |
| Heap InUse | 236.1MB | 242.3MB | -6.2MB | 194.7MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2605.6MB | 2605.2MB | +0.4MB | 2433.5MB | 6883.9MB | |
| Heap Objects | 729,791 | 877,603 | -147812 | 862,445 | 17,165,538 | |

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
| 2026-06-06 | 152 | 17,207 | 278.0MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 36.02MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 6.53MB |
| 6 | `bufio.NewWriterSize` | 2.52MB |
| 7 | `bufio.NewReaderSize` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.growslice` | 2.08MB |
| 10 | `reflect.unsafe_NewArray` | 2.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 40.81GB |
| 2 | `jackskj/carta.getUniqueId` | 37.58GB |
| 3 | `segmentio/kafka-go.makePartitions` | 34.38GB |
| 4 | `fmt.Sprintf` | 34.13GB |
| 5 | `reflect.unsafe_New` | 33.11GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 27.57GB |
| 7 | `fmt.(*buffer).writeString` | 26.61GB |
| 8 | `carta/value.NewCell` | 23.54GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 22.34GB |
| 10 | `reflect.unsafe_NewArray` | 17.59GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.71GB | 1.71GB | 1.63GB | 0B |
| `evaluation.mergeMetadata` | 909.72MB | 907.22MB | 862.13MB | 0B |
| `local.(*Client).EvaluateV2` | 2.61GB | 2.60GB | 2.49GB | 0B |
| `local.topologicalSort` | 374.51MB | 372.49MB | 358.00MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.53GB | 2.53GB | 2.41GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 327.58MB | 327.58MB | 320.83MB | 0B |
| `localEvaluation.getMapOfValue` | 2.53GB | 2.53GB | 2.41GB | 0B |
| `utils.ParseFeatureFlag` | 2.54GB | 2.53GB | 2.41GB | 0B |

**Total FF alloc (current snapshot):** 13.50GB  |  **24h avg:** 12.86GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1681 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1681 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1681 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1332/1681 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1681 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.41MB | 1332/1681 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.65MB | 1038/1681 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1681 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1681 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1681 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1681 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1681 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1681 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1681 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1681 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1681 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1681 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1681 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.65GB | 392/1681 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.64GB | 865/1681 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
