# Overview: prod
*Last updated: 2026-06-16 15:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T15:11 (4588 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,489 | avg: 14,856 | max: 84,644 | trend: INCREASING (+2.30/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 183.1MB | avg: 245.8MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,489 | 15,246 | -757 | 14,856 | 84,644 | INCREASING (+2.30/hr) |
| Heap InUse | 183.1MB | 197.7MB | -14.6MB | 245.8MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 848.0MB | 847.8MB | +0.2MB | 2498.8MB | 6883.9MB | |
| Heap Objects | 821,278 | 819,145 | +2133 | 1,053,387 | 17,165,538 | |

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
| 2026-06-16 | 182 | 16,454 | 270.1MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 5.68MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `bufio.NewReaderSize` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 5.89GB |
| 2 | `jackskj/carta.getUniqueId` | 5.56GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.18GB |
| 4 | `reflect.unsafe_New` | 4.78GB |
| 5 | `fmt.Sprintf` | 3.89GB |
| 6 | `fmt.(*buffer).writeString` | 3.48GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 3.41GB |
| 8 | `carta/value.NewCell` | 3.4GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 2.81GB |
| 10 | `reflect.unsafe_NewArray` | 2.71GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 366.05MB | 353.34MB | 423.97MB | 0B |
| `evaluation.mergeMetadata` | 187.05MB | 181.54MB | 220.54MB | 0B |
| `local.(*Client).EvaluateV2` | 572.01MB | 551.50MB | 651.19MB | 0B |
| `local.topologicalSort` | 79.38MB | 75.83MB | 90.25MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 549.12MB | 531.74MB | 632.36MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 82.76MB | 78.62MB | 85.25MB | 0B |
| `localEvaluation.getMapOfValue` | 549.12MB | 531.74MB | 632.36MB | 0B |
| `utils.ParseFeatureFlag` | 550.62MB | 533.24MB | 633.52MB | 0B |

**Total FF alloc (current snapshot):** 2.87GB  |  **24h avg:** 3.29GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.44MB | 98/4588 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4239/4588 | `█████████████░░ 92%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.19MB | 130/4588 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 31.15MB | 4239/4588 | `███████████░░░░ 78%` |
| 5 | `database/sql.convertAssignRows` | 20.6MB | 153/4588 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4588 | `██████░░░░░░░░░ 45%` |
| 7 | `bytes.growSlice` | 15.81MB | 3339/4588 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4588 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4588 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4588 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4588 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4588 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4588 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4588 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 64.21GB | 3800/4588 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.0GB | 3962/4588 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.36GB | 3816/4588 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.67GB | 3580/4588 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4588 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.75GB | 3134/4588 | `█████░░░░░░░░░░ 38%` |

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
