# Overview: prod
*Last updated: 2026-06-10 13:28 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T13:28 (2842 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,222 | avg: 14,075 | max: 84,644 | trend: INCREASING (+4.29/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 275.0MB | avg: 226.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,222 | 16,223 | -1001 | 14,075 | 84,644 | INCREASING (+4.29/hr) |
| Heap InUse | 275.0MB | 336.5MB | -61.5MB | 226.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3320.4MB | 3319.9MB | +0.5MB | 2560.7MB | 6883.9MB | |
| Heap Objects | 1,042,505 | 1,206,196 | -163691 | 984,510 | 17,165,538 | |

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
| 2026-06-10 | 161 | 17,381 | 324.6MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.56MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 4.53MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 137.1GB |
| 2 | `segmentio/kafka-go.makePartitions` | 131.58GB |
| 3 | `jackskj/carta.getUniqueId` | 122.08GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.22GB |
| 5 | `reflect.unsafe_New` | 108.27GB |
| 6 | `fmt.Sprintf` | 90.38GB |
| 7 | `fmt.(*buffer).writeString` | 86.62GB |
| 8 | `carta/value.NewCell` | 77.47GB |
| 9 | `reflect.unsafe_NewArray` | 67.29GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 57.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.58GB | 6.57GB | 6.37GB | 0B |
| `evaluation.mergeMetadata` | 3.45GB | 3.45GB | 3.34GB | 0B |
| `local.(*Client).EvaluateV2` | 10.04GB | 10.02GB | 9.71GB | 0B |
| `local.topologicalSort` | 1.40GB | 1.40GB | 1.35GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.60GB | 9.59GB | 9.30GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.35GB | 1.35GB | 1.31GB | 0B |
| `localEvaluation.getMapOfValue` | 9.60GB | 9.59GB | 9.30GB | 0B |
| `utils.ParseFeatureFlag` | 9.61GB | 9.60GB | 9.31GB | 0B |

**Total FF alloc (current snapshot):** 51.62GB  |  **24h avg:** 49.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2842 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2842 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2493/2842 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 28.72MB | 2493/2842 | `██████░░░░░░░░░ 40%` |
| 5 | `database/sql.convertAssignRows` | 28.64MB | 99/2842 | `██████░░░░░░░░░ 40%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2842 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.9MB | 1908/2842 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2842 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2842 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2842 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2842 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2842 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2842 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2842 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.77GB | 1359/2842 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2842 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 39.64GB | 2216/2842 | `████░░░░░░░░░░░ 31%` |
| 8 | `reflect.growslice` | 38.38GB | 2054/2842 | `████░░░░░░░░░░░ 30%` |
| 9 | `jackskj/carta.getUniqueId` | 33.39GB | 2070/2842 | `████░░░░░░░░░░░ 26%` |
| 10 | `reflect.unsafe_New` | 32.94GB | 1834/2842 | `███░░░░░░░░░░░░ 26%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
