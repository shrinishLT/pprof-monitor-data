# Overview: prod
*Last updated: 2026-06-16 00:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T00:20 (4411 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,682 | avg: 14,791 | max: 84,644 | trend: INCREASING (+2.40/hr))
```
▂▂▃▂▂▁▁▂▃▂▃▂▂▂▂▂▂▁▁▁▁▂▆▄▁▂▂▃▄▂▃▂▄▃▃▁▄▂█▃▃▁▁▂▄▄▄▂▄▂▃▂▃▂▃▇▅▃▁▁▁▁▄▇▄▃▃▂▁▂▁▁▁▂▁▁▁▁▁▁▂▁▄▇▂▂▃▁▁▁▄▁▂▂▅▃
```

**Heap InUse** (current: 336.2MB | avg: 244.9MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▂▂▂▃▃▃▁▂▃▂▃▂▃▂▂▃▃▂▂▂▃▂▆▄▂▂▃▃▃▂▄▄▆▃▄▁▄▂▆▃▃▂▁▂▄▅▄▂▅▂▃▂▃▃▃▅▄▃▂▁▂▁▃▇▄▄▃▃▃▂▃▂▂▄▁▂▃▂▂▂▂▂▃█▂▂▄▁▁▁▃▂▂▃▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,682 | 18,595 | -1913 | 14,791 | 84,644 | INCREASING (+2.40/hr) |
| Heap InUse | 336.2MB | 348.8MB | -12.6MB | 244.9MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2427.0MB | 2425.9MB | +1.1MB | 2522.5MB | 6883.9MB | |
| Heap Objects | 1,098,156 | 1,139,308 | -41152 | 1,048,985 | 17,165,538 | |

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
| 2026-06-16 | 5 | 15,995 | 288.7MB | 348.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 14.08MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 8.73MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 7 | `bufio.NewReaderSize` | 7.53MB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 10 | `bufio.NewWriterSize` | 3.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 115.45GB |
| 2 | `reflect.growslice` | 110.71GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.85GB |
| 4 | `jackskj/carta.getUniqueId` | 100.85GB |
| 5 | `reflect.unsafe_New` | 88.1GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 82.8GB |
| 7 | `fmt.Sprintf` | 80.67GB |
| 8 | `fmt.(*buffer).writeString` | 68.43GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 68.1GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 64.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.14GB | 5.14GB | 4.97GB | 0B |
| `evaluation.mergeMetadata` | 2.67GB | 2.67GB | 2.58GB | 0B |
| `local.(*Client).EvaluateV2` | 7.90GB | 7.89GB | 7.63GB | 0B |
| `local.topologicalSort` | 1.12GB | 1.12GB | 1.08GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.65GB | 7.64GB | 7.40GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.01GB | 1.01GB | 991.88MB | 0B |
| `localEvaluation.getMapOfValue` | 7.65GB | 7.64GB | 7.40GB | 0B |
| `utils.ParseFeatureFlag` | 7.66GB | 7.65GB | 7.41GB | 0B |

**Total FF alloc (current snapshot):** 40.79GB  |  **24h avg:** 39.43GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 42.36MB | 90/4411 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.02MB | 123/4411 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4062/4411 | `████████████░░░ 86%` |
| 4 | `runtime.mallocgc` | 31.35MB | 4062/4411 | `███████████░░░░ 74%` |
| 5 | `database/sql.convertAssignRows` | 21.51MB | 145/4411 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4411 | `██████░░░░░░░░░ 42%` |
| 7 | `bytes.growSlice` | 15.81MB | 3179/4411 | `█████░░░░░░░░░░ 37%` |
| 8 | `net/http.(*Transport).dialConn` | 13.21MB | 119/4411 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4411 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4411 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4411 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4411 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4411 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.92GB | 2600/4411 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 62.94GB | 3623/4411 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.7GB | 3785/4411 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.18GB | 3639/4411 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.74GB | 3403/4411 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4411 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.27GB | 2957/4411 | `█████░░░░░░░░░░ 37%` |

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
