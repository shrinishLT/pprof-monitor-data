# Overview: prod
*Last updated: 2026-06-10 14:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T14:20 (2853 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,451 | avg: 14,084 | max: 84,644 | trend: INCREASING (+4.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 363.5MB | avg: 227.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,451 | 18,446 | -2995 | 14,084 | 84,644 | INCREASING (+4.27/hr) |
| Heap InUse | 363.5MB | 377.6MB | -14.1MB | 227.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3331.1MB | 3333.2MB | -2.1MB | 2563.7MB | 6883.9MB | |
| Heap Objects | 1,492,857 | 1,145,612 | +347245 | 984,763 | 17,165,538 | |

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
| 2026-06-10 | 172 | 17,325 | 324.1MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 23.67MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 6.54MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.06MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 137.41GB |
| 2 | `segmentio/kafka-go.makePartitions` | 132.82GB |
| 3 | `jackskj/carta.getUniqueId` | 122.53GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.58GB |
| 5 | `reflect.unsafe_New` | 108.58GB |
| 6 | `fmt.Sprintf` | 91.99GB |
| 7 | `fmt.(*buffer).writeString` | 86.79GB |
| 8 | `carta/value.NewCell` | 77.68GB |
| 9 | `reflect.unsafe_NewArray` | 67.93GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 57.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.67GB | 6.66GB | 6.46GB | 0B |
| `evaluation.mergeMetadata` | 3.50GB | 3.49GB | 3.39GB | 0B |
| `local.(*Client).EvaluateV2` | 10.16GB | 10.15GB | 9.85GB | 0B |
| `local.topologicalSort` | 1.41GB | 1.41GB | 1.37GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.73GB | 9.72GB | 9.43GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.36GB | 1.36GB | 1.32GB | 0B |
| `localEvaluation.getMapOfValue` | 9.73GB | 9.72GB | 9.43GB | 0B |
| `utils.ParseFeatureFlag` | 9.74GB | 9.73GB | 9.44GB | 0B |

**Total FF alloc (current snapshot):** 52.30GB  |  **24h avg:** 50.69GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2853 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2853 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2504/2853 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 28.81MB | 2504/2853 | `██████░░░░░░░░░ 40%` |
| 5 | `database/sql.convertAssignRows` | 28.64MB | 99/2853 | `██████░░░░░░░░░ 40%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2853 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.93MB | 1917/2853 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2853 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2853 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2853 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2853 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2853 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2853 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2853 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 49.28GB | 1370/2853 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2853 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 40.1GB | 2227/2853 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.growslice` | 38.91GB | 2065/2853 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 33.86GB | 2081/2853 | `████░░░░░░░░░░░ 27%` |
| 10 | `reflect.unsafe_New` | 33.39GB | 1845/2853 | `████░░░░░░░░░░░ 26%` |

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
