# Overview: prod
*Last updated: 2026-06-14 11:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T11:50 (3975 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,988 | avg: 14,704 | max: 84,644 | trend: INCREASING (+2.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇▇█▄▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 243.5MB | avg: 242.8MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▂▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▂▄▃▄▆▆▆█▅▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,988 | 15,002 | -14 | 14,704 | 84,644 | INCREASING (+2.98/hr) |
| Heap InUse | 243.5MB | 224.8MB | +18.7MB | 242.8MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2246.4MB | 2246.2MB | +0.2MB | 2535.6MB | 6883.9MB | |
| Heap Objects | 958,243 | 739,108 | +219135 | 1,042,647 | 17,165,538 | |

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
| 2026-06-14 | 143 | 17,257 | 304.6MB | 1419.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `bytes.growSlice` | 4.95MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `bufio.NewWriterSize` | 3.51MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 72.09GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.47GB |
| 3 | `jackskj/carta.getUniqueId` | 66.19GB |
| 4 | `segmentio/kafka-go.makePartitions` | 65.64GB |
| 5 | `reflect.unsafe_New` | 57.63GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 50.49GB |
| 7 | `fmt.Sprintf` | 49.95GB |
| 8 | `fmt.(*buffer).writeString` | 45.01GB |
| 9 | `carta/value.NewCell` | 41.77GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 41.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.62GB | 2.61GB | 2.54GB | 0B |
| `evaluation.mergeMetadata` | 1.34GB | 1.34GB | 1.30GB | 0B |
| `local.(*Client).EvaluateV2` | 4.02GB | 4.02GB | 3.90GB | 0B |
| `local.topologicalSort` | 586.37MB | 585.87MB | 566.29MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.98GB | 3.97GB | 3.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 447.81MB | 447.81MB | 443.44MB | 0B |
| `localEvaluation.getMapOfValue` | 3.98GB | 3.97GB | 3.84GB | 0B |
| `utils.ParseFeatureFlag` | 3.99GB | 3.98GB | 3.85GB | 0B |

**Total FF alloc (current snapshot):** 20.94GB  |  **24h avg:** 20.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 45.79MB | 80/3975 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 40.88MB | 110/3975 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3626/3975 | `███████████░░░░ 79%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3626/3975 | `██████████░░░░░ 68%` |
| 5 | `database/sql.convertAssignRows` | 22.94MB | 130/3975 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3975 | `█████░░░░░░░░░░ 39%` |
| 7 | `bytes.growSlice` | 16.06MB | 2861/3975 | `█████░░░░░░░░░░ 35%` |
| 8 | `net/http.(*Transport).dialConn` | 13.32MB | 108/3975 | `████░░░░░░░░░░░ 29%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3975 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3975 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3975 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3975 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3975 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.03GB | 2164/3975 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.08GB | 3349/3975 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 58.98GB | 3187/3975 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.45GB | 3203/3975 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3975 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.76GB | 2967/3975 | `█████░░░░░░░░░░ 39%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 45.9GB | 1498/3975 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
