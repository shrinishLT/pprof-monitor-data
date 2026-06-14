# Overview: prod
*Last updated: 2026-06-14 21:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T21:26 (4090 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,145 | avg: 14,699 | max: 84,644 | trend: INCREASING (+2.72/hr))
```
▂▂▅▂▁▁▂▂▁▁▃▁▂▄▂▁▃▆▅▂▂▅█▄▂▂▁▃▂▁▁▃▁▁▁▂▁▃▁▆▂▁▃▃▁▁▁▁▆▆▅▇▁▁▁▄▂▂▁▃▇▃▁▁▁▁▃▁▁▁▁▃▂▁▁▁▁▁▁▄▂▁▁▁▂▂▂▂▁▃▂▂▁▁▁▇
```

**Heap InUse** (current: 316.7MB | avg: 242.5MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▃▂▃▂▃▃▁▃▄▁▂▄▂▃▅▅▂▅▅▅▃▄▅▃▃▄▅▂▄▄▂▃▅▂▄▅▃▄▄▇▃▁▄▃▂▅▅▃▄▅▄▄▃▅▃▅▂▃▂▃▃▃▃▃▃▁▁▄▅▄▁▃▃▂▄▁▂▃▁▄▃▁▄▂▂▆▃▂▃█▂▄▃▁▁▇
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,145 | 14,144 | +1001 | 14,699 | 84,644 | INCREASING (+2.72/hr) |
| Heap InUse | 316.7MB | 170.5MB | +146.2MB | 242.5MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 2408.9MB | 2409.3MB | -0.4MB | 2531.2MB | 6883.9MB | |
| Heap Objects | 1,126,075 | 516,170 | +609905 | 1,041,938 | 17,165,538 | |

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
| 2026-06-14 | 258 | 16,040 | 271.2MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 10.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 6.16MB |
| 7 | `bufio.NewWriterSize` | 5.54MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.27GB |
| 2 | `segmentio/kafka-go.makePartitions` | 78.75GB |
| 3 | `reflect.growslice` | 78.32GB |
| 4 | `jackskj/carta.getUniqueId` | 71.94GB |
| 5 | `reflect.unsafe_New` | 62.47GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 59.37GB |
| 7 | `fmt.Sprintf` | 54.82GB |
| 8 | `fmt.(*buffer).writeString` | 48.85GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 48.81GB |
| 10 | `carta/value.NewCell` | 45.26GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.97GB | 2.97GB | 2.91GB | 0B |
| `evaluation.mergeMetadata` | 1.52GB | 1.52GB | 1.49GB | 0B |
| `local.(*Client).EvaluateV2` | 4.58GB | 4.58GB | 4.47GB | 0B |
| `local.topologicalSort` | 669.87MB | 667.86MB | 654.18MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.50GB | 4.50GB | 4.41GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 545.89MB | 541.29MB | 516.72MB | 0B |
| `localEvaluation.getMapOfValue` | 4.50GB | 4.50GB | 4.41GB | 0B |
| `utils.ParseFeatureFlag` | 4.51GB | 4.50GB | 4.42GB | 0B |

**Total FF alloc (current snapshot):** 23.77GB  |  **24h avg:** 23.25GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 44.35MB | 83/4090 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.05MB | 113/4090 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3741/4090 | `████████████░░░ 82%` |
| 4 | `runtime.mallocgc` | 31.26MB | 3741/4090 | `██████████░░░░░ 70%` |
| 5 | `database/sql.convertAssignRows` | 22.4MB | 134/4090 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4090 | `██████░░░░░░░░░ 40%` |
| 7 | `bytes.growSlice` | 15.8MB | 2935/4090 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/4090 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4090 | `████░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4090 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4090 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4090 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4090 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.03GB | 2279/4090 | `████████░░░░░░░ 55%` |
| 5 | `reflect.growslice` | 59.62GB | 3302/4090 | `███████░░░░░░░░ 47%` |
| 6 | `segmentio/kafka-go.makePartitions` | 59.52GB | 3464/4090 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 53.1GB | 3318/4090 | `██████░░░░░░░░░ 42%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4090 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.21GB | 3082/4090 | `██████░░░░░░░░░ 40%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/4090 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
