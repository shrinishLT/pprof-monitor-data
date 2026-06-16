# Overview: prod
*Last updated: 2026-06-16 18:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T18:56 (4632 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,361 | avg: 14,858 | max: 84,644 | trend: INCREASING (+2.24/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 217.4MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
█▂▁▁▂▂▁▁▁▁▁▁▁▂▁▁▁▂▁▁▁▁▂▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,361 | 15,537 | +824 | 14,858 | 84,644 | INCREASING (+2.24/hr) |
| Heap InUse | 217.4MB | 231.4MB | -14.0MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1004.9MB | 1005.0MB | -0.1MB | 2484.3MB | 6883.9MB | |
| Heap Objects | 704,157 | 1,350,927 | -646770 | 1,052,136 | 17,165,538 | |

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
| 2026-06-16 | 226 | 16,176 | 255.2MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.08MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.04MB |
| 6 | `bufio.NewReaderSize` | 6.02MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 10.34GB |
| 2 | `fmt.Sprintf` | 6.67GB |
| 3 | `reflect.growslice` | 6.51GB |
| 4 | `jackskj/carta.getUniqueId` | 6.43GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 5.64GB |
| 6 | `reflect.unsafe_New` | 5.48GB |
| 7 | `reflect.unsafe_NewArray` | 5.41GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 5.12GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 4.63GB |
| 10 | `carta/value.NewCell` | 3.85GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 831.27MB | 823.66MB | 584.26MB | 0B |
| `evaluation.mergeMetadata` | 426.60MB | 423.10MB | 299.58MB | 0B |
| `local.(*Client).EvaluateV2` | 1.24GB | 1.22GB | 893.17MB | 0B |
| `local.topologicalSort` | 169.98MB | 166.93MB | 118.82MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.16GB | 1.15GB | 845.10MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 204.59MB | 204.07MB | 139.58MB | 0B |
| `localEvaluation.getMapOfValue` | 1.16GB | 1.15GB | 845.10MB | 0B |
| `utils.ParseFeatureFlag` | 1.16GB | 1.15GB | 847.19MB | 0B |

**Total FF alloc (current snapshot):** 6.31GB  |  **24h avg:** 4.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.78MB | 100/4632 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4283/4632 | `██████████████░ 94%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.83MB | 132/4632 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.94MB | 4283/4632 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.56MB | 154/4632 | `███████░░░░░░░░ 53%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4632 | `██████░░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.71MB | 3382/4632 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4632 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4632 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4632 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4632 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4632 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4632 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4632 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.55GB | 3844/4632 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.38GB | 4006/4632 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.77GB | 3860/4632 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.08GB | 3624/4632 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4632 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4632 | `█████░░░░░░░░░░ 37%` |

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
