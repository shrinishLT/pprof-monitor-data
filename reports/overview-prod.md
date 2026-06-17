# Overview: prod
*Last updated: 2026-06-17 23:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T23:46 (4978 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,701 | avg: 14,975 | max: 84,644 | trend: INCREASING (+2.07/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▂▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▆▃▄▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 227.3MB | avg: 246.6MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▂▂▂▃▂▂▂▂▁▂▁▁▃▃▂▃▃▃▁▂▁▁▁▁▁▁▂▁▂▄▃▂▂▂▁▁▂▁▁▁▂▁▂▂▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▂▁█▇▆▅▅▂▃▂▁▂▁▁▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,701 | 15,528 | -827 | 14,975 | 84,644 | INCREASING (+2.07/hr) |
| Heap InUse | 227.3MB | 239.3MB | -12.0MB | 246.6MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2218.9MB | 2218.3MB | +0.6MB | 2417.8MB | 6883.9MB | |
| Heap Objects | 903,061 | 700,321 | +202740 | 1,056,045 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 286 | 16,643 | 267.9MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.49MB |
| 5 | `bufio.NewReaderSize` | 4.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.8GB |
| 2 | `reflect.growslice` | 42.27GB |
| 3 | `jackskj/carta.getUniqueId` | 40.22GB |
| 4 | `fmt.Sprintf` | 37.95GB |
| 5 | `reflect.unsafe_New` | 34.98GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 30.31GB |
| 7 | `fmt.(*buffer).writeString` | 26.3GB |
| 8 | `reflect.unsafe_NewArray` | 25.69GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 25.06GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 24.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 3.49GB | 3.49GB | 3.30GB | 0B |
| `evaluation.mergeMetadata` | 1.81GB | 1.80GB | 1.70GB | 0B |
| `local.(*Client).EvaluateV2` | 5.30GB | 5.29GB | 5.00GB | 0B |
| `local.topologicalSort` | 755.22MB | 754.72MB | 708.03MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 5.05GB | 5.04GB | 4.76GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 767.71MB | 765.65MB | 728.21MB | 0B |
| `localEvaluation.getMapOfValue` | 5.05GB | 5.04GB | 4.76GB | 0B |
| `utils.ParseFeatureFlag` | 5.07GB | 5.05GB | 4.77GB | 0B |

**Total FF alloc (current snapshot):** 27.26GB  |  **24h avg:** 25.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.25MB | 105/4978 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4629/4978 | `██████████████░ 98%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.39MB | 140/4978 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4629/4978 | `████████████░░░ 81%` |
| 5 | `database/sql.convertAssignRows` | 19.66MB | 164/4978 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4978 | `███████░░░░░░░░ 48%` |
| 7 | `bytes.growSlice` | 15.81MB | 3696/4978 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.19MB | 140/4978 | `█████░░░░░░░░░░ 35%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4978 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.Client` | 10.36MB | 169/4978 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4978 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4978 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4978 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.96GB | 2895/4978 | `████████░░░░░░░ 58%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.74GB | 4352/4978 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.39GB | 4190/4978 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.07GB | 4206/4978 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4978 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.26GB | 3970/4978 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 45.69GB | 3381/4978 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
