# Overview: prod
*Last updated: 2026-06-16 17:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T17:41 (4617 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,175 | avg: 14,857 | max: 84,644 | trend: INCREASING (+2.26/hr))
```
▁▁▁▁▁▁▃▃▄▃▄▄▅▆█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 156.8MB | avg: 245.5MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▂▂▃▃▅▃▄▅▅▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,175 | 14,394 | -219 | 14,857 | 84,644 | INCREASING (+2.26/hr) |
| Heap InUse | 156.8MB | 195.9MB | -39.1MB | 245.5MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1011.4MB | 1011.4MB | +0.0MB | 2489.1MB | 6883.9MB | |
| Heap Objects | 850,954 | 1,173,166 | -322212 | 1,052,609 | 17,165,538 | |

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
| 2026-06-16 | 211 | 16,252 | 259.7MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 4.41MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `bytes.growSlice` | 3.88MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.59GB |
| 2 | `reflect.growslice` | 6.41GB |
| 3 | `jackskj/carta.getUniqueId` | 6.28GB |
| 4 | `fmt.Sprintf` | 5.83GB |
| 5 | `reflect.unsafe_New` | 5.36GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 4.68GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.54GB |
| 8 | `reflect.unsafe_NewArray` | 4.5GB |
| 9 | `carta/value.NewCell` | 3.78GB |
| 10 | `fmt.(*buffer).writeString` | 3.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 669.29MB | 659.09MB | 430.35MB | 0B |
| `evaluation.mergeMetadata` | 342.08MB | 335.58MB | 221.40MB | 0B |
| `local.(*Client).EvaluateV2` | 1.00GB | 1009.14MB | 660.77MB | 0B |
| `local.topologicalSort` | 137.04MB | 134.52MB | 88.37MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 968.42MB | 953.55MB | 629.57MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 161.08MB | 159.03MB | 100.80MB | 0B |
| `localEvaluation.getMapOfValue` | 968.42MB | 953.55MB | 629.57MB | 0B |
| `utils.ParseFeatureFlag` | 970.93MB | 956.05MB | 631.23MB | 0B |

**Total FF alloc (current snapshot):** 5.12GB  |  **24h avg:** 3.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.08MB | 99/4617 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4268/4617 | `██████████████░ 93%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 36.07MB | 131/4617 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 31.01MB | 4268/4617 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.56MB | 154/4617 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4617 | `██████░░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.75MB | 3367/4617 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4617 | `█████░░░░░░░░░░ 33%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4617 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4617 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4617 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4617 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4617 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4617 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.77GB | 3829/4617 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.58GB | 3991/4617 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.97GB | 3845/4617 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 53.28GB | 3609/4617 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4617 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.48GB | 3153/4617 | `█████░░░░░░░░░░ 37%` |

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
