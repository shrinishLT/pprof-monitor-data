# Overview: prod
*Last updated: 2026-06-13 04:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-13T04:55 (3604 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,308 | avg: 14,528 | max: 84,644 | trend: INCREASING (+3.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▅▃▄▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▃▄▃▄▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▄▃▂▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 287.3MB | avg: 239.5MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▅▃▃▄▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▄▃▃▃▄▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▃▄▄▂▃▂▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,308 | 14,106 | +1202 | 14,528 | 84,644 | INCREASING (+3.33/hr) |
| Heap InUse | 287.3MB | 153.4MB | +133.9MB | 239.5MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 1409.8MB | 1412.2MB | -2.4MB | 2581.9MB | 6883.9MB | |
| Heap Objects | 1,728,454 | 574,529 | +1153925 | 1,029,554 | 17,165,538 | |

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
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 60 | 17,738 | 296.8MB | 1133.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 23.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 8.04MB |
| 6 | `bufio.NewWriterSize` | 3.03MB |
| 7 | `bufio.NewReaderSize` | 3.03MB |
| 8 | `compress/flate.NewWriter` | 2.64MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.23GB |
| 2 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 16.85GB |
| 3 | `fmt.Sprintf` | 15.68GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 13.88GB |
| 5 | `jackskj/carta.getUniqueId` | 12.38GB |
| 6 | `reflect.growslice` | 12.33GB |
| 7 | `reflect.unsafe_NewArray` | 11.82GB |
| 8 | `reflect.unsafe_New` | 10.91GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 9.74GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 7.88GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.38GB | 1.38GB | 1.28GB | 0B |
| `evaluation.mergeMetadata` | 723.68MB | 722.18MB | 672.92MB | 0B |
| `local.(*Client).EvaluateV2` | 2.13GB | 2.12GB | 1.97GB | 0B |
| `local.topologicalSort` | 306.28MB | 305.78MB | 285.22MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.01GB | 2.01GB | 1.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 311.93MB | 311.93MB | 300.13MB | 0B |
| `localEvaluation.getMapOfValue` | 2.01GB | 2.01GB | 1.85GB | 0B |
| `utils.ParseFeatureFlag` | 2.02GB | 2.01GB | 1.86GB | 512.56kB |

**Total FF alloc (current snapshot):** 10.86GB  |  **24h avg:** 10.05GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.56MB | 71/3604 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.23MB | 96/3604 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3255/3604 | `██████████░░░░░ 72%` |
| 4 | `runtime.mallocgc` | 31.43MB | 3255/3604 | `█████████░░░░░░ 62%` |
| 5 | `database/sql.convertAssignRows` | 24.35MB | 121/3604 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3604 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 15.87MB | 2575/3604 | `████░░░░░░░░░░░ 31%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3604 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*Transport).dialConn` | 13.54MB | 89/3604 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3604 | `███░░░░░░░░░░░░ 20%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3604 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3604 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3604 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3604 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 61.19GB | 2816/3604 | `███████░░░░░░░░ 48%` |
| 6 | `segmentio/kafka-go.makePartitions` | 60.91GB | 2978/3604 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.28GB | 2832/3604 | `██████░░░░░░░░░ 43%` |
| 8 | `reflect.unsafe_New` | 52.02GB | 2596/3604 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3604 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.65GB | 2183/3604 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
