# Overview: prod
*Last updated: 2026-06-16 14:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T14:10 (4576 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,900 | avg: 14,856 | max: 84,644 | trend: INCREASING (+2.32/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.8MB | avg: 246.0MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,900 | 14,456 | +444 | 14,856 | 84,644 | INCREASING (+2.32/hr) |
| Heap InUse | 160.8MB | 169.6MB | -8.8MB | 246.0MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 462.9MB | 463.4MB | -0.5MB | 2503.4MB | 6883.9MB | |
| Heap Objects | 564,244 | 787,120 | -222876 | 1,053,852 | 17,165,538 | |

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
| 2026-06-16 | 170 | 16,580 | 276.6MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 6.17MB |
| 5 | `bytes.growSlice` | 6.05MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `bufio.NewWriterSize` | 3.53MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 3.06MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.61GB |
| 2 | `jackskj/carta.getUniqueId` | 5.21GB |
| 3 | `reflect.unsafe_New` | 4.57GB |
| 4 | `segmentio/kafka-go.makePartitions` | 3.78GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.38GB |
| 6 | `fmt.(*buffer).writeString` | 3.36GB |
| 7 | `fmt.Sprintf` | 3.34GB |
| 8 | `carta/value.NewCell` | 3.22GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.78GB |
| 10 | `reflect.unsafe_NewArray` | 1.96GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 250.22MB | 244.11MB | 1.82GB | 0B |
| `evaluation.mergeMetadata` | 131.03MB | 128.53MB | 970.34MB | 0B |
| `local.(*Client).EvaluateV2` | 386.15MB | 374.36MB | 2.80GB | 0B |
| `local.topologicalSort` | 53.08MB | 51.05MB | 403.02MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 368.91MB | 359.71MB | 2.72GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 59.24MB | 56.65MB | 355.06MB | 0B |
| `localEvaluation.getMapOfValue` | 368.91MB | 359.71MB | 2.72GB | 0B |
| `utils.ParseFeatureFlag` | 369.91MB | 360.71MB | 2.72GB | 0B |

**Total FF alloc (current snapshot):** 1.94GB  |  **24h avg:** 14.46GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.44MB | 98/4576 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4227/4576 | `█████████████░░ 92%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.19MB | 130/4576 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 31.21MB | 4227/4576 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.6MB | 153/4576 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4576 | `██████░░░░░░░░░ 45%` |
| 7 | `bytes.growSlice` | 15.85MB | 3327/4576 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4576 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4576 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4576 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4576 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4576 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4576 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4576 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.4GB | 3788/4576 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.18GB | 3950/4576 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.52GB | 3804/4576 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.83GB | 3568/4576 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4576 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.92GB | 3122/4576 | `█████░░░░░░░░░░ 38%` |

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
