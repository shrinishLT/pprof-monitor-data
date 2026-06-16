# Overview: prod
*Last updated: 2026-06-16 21:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T21:33 (4663 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,843 | avg: 14,868 | max: 84,644 | trend: INCREASING (+2.22/hr))
```
▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁
```

**Heap InUse** (current: 229.0MB | avg: 245.4MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▃▂▃▂▁▁▁▁▁▁▂▂▁▂▁▂▁▂▂▁▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▂▂▁▂▂▁▂▂▂▄▂▂▁▁▁▂▂▂▂▂▂▂▁▂▂▂▁▁▂▂▃█▇▆▄▃▅▅▄▄▂▃▂▃▂▂▄▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,843 | 16,841 | -1998 | 14,868 | 84,644 | INCREASING (+2.22/hr) |
| Heap InUse | 229.0MB | 295.2MB | -66.2MB | 245.4MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 996.5MB | 993.8MB | +2.7MB | 2474.4MB | 6883.9MB | |
| Heap Objects | 1,505,118 | 1,280,737 | +224381 | 1,052,618 | 17,165,538 | |

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
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 257 | 16,212 | 255.7MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.58MB |
| 5 | `bufio.NewReaderSize` | 4.52MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 13.88GB |
| 2 | `fmt.Sprintf` | 10.78GB |
| 3 | `jackskj/carta.getUniqueId` | 7.64GB |
| 4 | `reflect.unsafe_NewArray` | 7.28GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.27GB |
| 6 | `reflect.growslice` | 7.18GB |
| 7 | `reflect.unsafe_New` | 6.29GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.96GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 5.73GB |
| 10 | `fmt.Sprint` | 5.41GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.12GB | 1.11GB | 910.35MB | 0B |
| `evaluation.mergeMetadata` | 585.64MB | 581.64MB | 466.83MB | 0B |
| `local.(*Client).EvaluateV2` | 1.70GB | 1.69GB | 1.35GB | 0B |
| `local.topologicalSort` | 232.80MB | 230.77MB | 183.81MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.59GB | 1.58GB | 1.27GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 280.96MB | 280.46MB | 224.24MB | 0B |
| `localEvaluation.getMapOfValue` | 1.59GB | 1.58GB | 1.27GB | 0B |
| `utils.ParseFeatureFlag` | 1.59GB | 1.58GB | 1.27GB | 0B |

**Total FF alloc (current snapshot):** 8.67GB  |  **24h avg:** 6.90GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4663 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4314/4663 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4663 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.81MB | 4314/4663 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.45MB | 155/4663 | `███████░░░░░░░░ 53%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4663 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.71MB | 3413/4663 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4663 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4663 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4663 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4663 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4663 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4663 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4663 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.09GB | 3875/4663 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.99GB | 4037/4663 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.38GB | 3891/4663 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.68GB | 3655/4663 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4663 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4663 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
