# Overview: prod
*Last updated: 2026-06-10 12:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T12:40 (2834 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,803 | avg: 14,072 | max: 84,644 | trend: INCREASING (+4.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 276.7MB | avg: 226.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,803 | 16,046 | -243 | 14,072 | 84,644 | INCREASING (+4.31/hr) |
| Heap InUse | 276.7MB | 305.6MB | -28.9MB | 226.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3319.7MB | 3319.2MB | +0.5MB | 2558.6MB | 6883.9MB | |
| Heap Objects | 791,006 | 975,650 | -184644 | 984,043 | 17,165,538 | |

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
| 2026-06-10 | 153 | 17,494 | 326.5MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 11.82MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 6.54MB |
| 7 | `bufio.NewWriterSize` | 5.54MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 134.05GB |
| 2 | `segmentio/kafka-go.makePartitions` | 130.5GB |
| 3 | `jackskj/carta.getUniqueId` | 119.39GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 111.15GB |
| 5 | `reflect.unsafe_New` | 105.87GB |
| 6 | `fmt.Sprintf` | 88.93GB |
| 7 | `fmt.(*buffer).writeString` | 84.77GB |
| 8 | `carta/value.NewCell` | 75.74GB |
| 9 | `reflect.unsafe_NewArray` | 66.73GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 56.25GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.47GB | 6.46GB | 6.31GB | 0B |
| `evaluation.mergeMetadata` | 3.40GB | 3.39GB | 3.31GB | 0B |
| `local.(*Client).EvaluateV2` | 9.88GB | 9.87GB | 9.62GB | 0B |
| `local.topologicalSort` | 1.38GB | 1.38GB | 1.34GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.46GB | 9.44GB | 9.21GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.33GB | 1.32GB | 1.30GB | 0B |
| `localEvaluation.getMapOfValue` | 9.46GB | 9.44GB | 9.21GB | 0B |
| `utils.ParseFeatureFlag` | 9.47GB | 9.45GB | 9.22GB | 512.56kB |

**Total FF alloc (current snapshot):** 50.84GB  |  **24h avg:** 49.52GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2834 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2834 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2485/2834 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 28.65MB | 2485/2834 | `██████░░░░░░░░░ 40%` |
| 5 | `database/sql.convertAssignRows` | 28.64MB | 99/2834 | `██████░░░░░░░░░ 40%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2834 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.92MB | 1900/2834 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2834 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2834 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2834 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2834 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2834 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2834 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2834 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 48.4GB | 1351/2834 | `█████░░░░░░░░░░ 38%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2834 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 39.31GB | 2208/2834 | `████░░░░░░░░░░░ 31%` |
| 8 | `reflect.growslice` | 38.0GB | 2046/2834 | `████░░░░░░░░░░░ 30%` |
| 9 | `jackskj/carta.getUniqueId` | 33.05GB | 2062/2834 | `███░░░░░░░░░░░░ 26%` |
| 10 | `reflect.unsafe_New` | 32.62GB | 1826/2834 | `███░░░░░░░░░░░░ 26%` |

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
