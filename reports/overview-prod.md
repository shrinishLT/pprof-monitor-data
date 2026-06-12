# Overview: prod
*Last updated: 2026-06-12 06:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T06:35 (3336 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,968 | avg: 14,339 | max: 84,644 | trend: INCREASING (+3.47/hr))
```
▁▁▁▁▅▅▆█▆▄▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 243.0MB | avg: 237.2MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▄▄▆█▆▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▂▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂▁▁▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,968 | 15,368 | -400 | 14,339 | 84,644 | INCREASING (+3.47/hr) |
| Heap InUse | 243.0MB | 321.5MB | -78.5MB | 237.2MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3343.9MB | 3343.1MB | +0.8MB | 2674.8MB | 6883.9MB | |
| Heap Objects | 716,486 | 1,051,541 | -335055 | 1,017,927 | 17,165,538 | |

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
| 2026-06-12 | 80 | 14,889 | 261.1MB | 361.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bufio.NewWriterSize` | 7.04MB |
| 6 | `bytes.growSlice` | 5.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 193.11GB |
| 2 | `segmentio/kafka-go.makePartitions` | 188.44GB |
| 3 | `jackskj/carta.getUniqueId` | 174.02GB |
| 4 | `reflect.unsafe_New` | 153.79GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 151.78GB |
| 6 | `fmt.Sprintf` | 139.57GB |
| 7 | `fmt.(*buffer).writeString` | 120.9GB |
| 8 | `carta/value.NewCell` | 109.94GB |
| 9 | `reflect.unsafe_NewArray` | 96.09GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 86.48GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.38GB | 10.37GB | 10.27GB | 0B |
| `evaluation.mergeMetadata` | 5.41GB | 5.41GB | 5.36GB | 0B |
| `local.(*Client).EvaluateV2` | 15.81GB | 15.80GB | 15.64GB | 0B |
| `local.topologicalSort` | 2.20GB | 2.20GB | 2.18GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.09GB | 15.08GB | 14.92GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.17GB | 2.17GB | 2.16GB | 0B |
| `localEvaluation.getMapOfValue` | 15.09GB | 15.08GB | 14.92GB | 0B |
| `utils.ParseFeatureFlag` | 15.11GB | 15.11GB | 14.94GB | 0B |

**Total FF alloc (current snapshot):** 81.25GB  |  **24h avg:** 80.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 56.35MB | 63/3336 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.55MB | 91/3336 | `████████████░░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2987/3336 | `█████████░░░░░░ 65%` |
| 4 | `runtime.mallocgc` | 32.32MB | 2987/3336 | `████████░░░░░░░ 57%` |
| 5 | `database/sql.convertAssignRows` | 26.19MB | 111/3336 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3336 | `████░░░░░░░░░░░ 31%` |
| 7 | `bytes.growSlice` | 15.49MB | 2347/3336 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3336 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.92MB | 74/3336 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3336 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3336 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3336 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3336 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 70.42GB | 1853/3336 | `████████░░░░░░░ 56%` |
| 5 | `reflect.growslice` | 62.2GB | 2548/3336 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.59GB | 2710/3336 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.03GB | 2564/3336 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 53.23GB | 2328/3336 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3336 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.39GB | 2075/3336 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
