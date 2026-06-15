# Overview: prod
*Last updated: 2026-06-15 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T20:30 (4365 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,648 | avg: 14,780 | max: 84,644 | trend: INCREASING (+2.45/hr))
```
▁▁▅▅▃▃▅▄▄▂▁▁▁▁▂▃▁▁▁▃▃▁▁▁▁▁▂▂▁▁▁▁▃▂▅▂▁▁▂▇▆▆▄▄▇▂▂▂▃▂▂▁▁▁▃▂▃▂▂▂▂▂▂▁▁▁▁▂▆▄▁▂▂▃▄▂▃▂▄▃▃▁▄▁█▃▃▁▁▂▄▄▄▂▄▂
```

**Heap InUse** (current: 254.3MB | avg: 244.5MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▄▄▃▃▃▅▅▂▂▁▁▁▃▃▁▂▁▄▄▃▃▁▁▂▂▃▂▃▂▂▂▃▄▃▂▂▂▅▇█▅▅▆▃▂▂▂▃▃▃▁▁▃▂▃▂▂▂▂▃▃▂▂▁▃▂▆▅▂▂▃▃▄▂▄▄▆▃▄▁▄▂▆▃▃▂▁▂▄▅▄▂▅▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,648 | 17,784 | -2136 | 14,780 | 84,644 | INCREASING (+2.45/hr) |
| Heap InUse | 254.3MB | 385.9MB | -131.6MB | 244.5MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2426.9MB | 2425.2MB | +1.7MB | 2523.5MB | 6883.9MB | |
| Heap Objects | 528,947 | 1,715,151 | -1186204 | 1,048,061 | 17,165,538 | |

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
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 245 | 16,193 | 281.8MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 12.76MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewReaderSize` | 5.02MB |
| 7 | `bufio.NewWriterSize` | 4.53MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 110.27GB |
| 2 | `segmentio/kafka-go.makePartitions` | 110.17GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.77GB |
| 4 | `jackskj/carta.getUniqueId` | 100.23GB |
| 5 | `reflect.unsafe_New` | 87.63GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 80.77GB |
| 7 | `fmt.Sprintf` | 76.53GB |
| 8 | `fmt.(*buffer).writeString` | 68.24GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 66.47GB |
| 10 | `carta/value.NewCell` | 63.4GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.75GB | 4.74GB | 4.47GB | 0B |
| `evaluation.mergeMetadata` | 2.47GB | 2.46GB | 2.32GB | 0B |
| `local.(*Client).EvaluateV2` | 7.31GB | 7.29GB | 6.88GB | 0B |
| `local.topologicalSort` | 1.04GB | 1.03GB | 998.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.10GB | 7.09GB | 6.70GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 936.73MB | 931.16MB | 863.52MB | 0B |
| `localEvaluation.getMapOfValue` | 7.10GB | 7.09GB | 6.70GB | 0B |
| `utils.ParseFeatureFlag` | 7.11GB | 7.10GB | 6.71GB | 0B |

**Total FF alloc (current snapshot):** 37.80GB  |  **24h avg:** 35.59GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.75MB | 89/4365 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.23MB | 122/4365 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4016/4365 | `████████████░░░ 85%` |
| 4 | `runtime.mallocgc` | 31.34MB | 4016/4365 | `██████████░░░░░ 73%` |
| 5 | `database/sql.convertAssignRows` | 21.63MB | 144/4365 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4365 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.84MB | 3138/4365 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.35MB | 117/4365 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4365 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4365 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4365 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4365 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4365 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.28GB | 2554/4365 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 62.33GB | 3577/4365 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.08GB | 3739/4365 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.61GB | 3593/4365 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.26GB | 3357/4365 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4365 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.94GB | 2911/4365 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
