# Overview: prod
*Last updated: 2026-06-10 15:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T15:40 (2869 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,122 | avg: 14,089 | max: 84,644 | trend: INCREASING (+4.22/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 255.0MB | avg: 227.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,122 | 15,042 | +80 | 14,089 | 84,644 | INCREASING (+4.22/hr) |
| Heap InUse | 255.0MB | 262.5MB | -7.5MB | 227.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3338.1MB | 3337.4MB | +0.7MB | 2568.0MB | 6883.9MB | |
| Heap Objects | 844,719 | 1,113,192 | -268473 | 984,853 | 17,165,538 | |

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
| 2026-06-10 | 188 | 17,121 | 319.3MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.91MB |
| 6 | `bufio.NewReaderSize` | 5.54MB |
| 7 | `compress/flate.NewWriter` | 5.29MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 137.94GB |
| 2 | `segmentio/kafka-go.makePartitions` | 134.64GB |
| 3 | `jackskj/carta.getUniqueId` | 123.21GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.68GB |
| 5 | `reflect.unsafe_New` | 109.07GB |
| 6 | `fmt.Sprintf` | 93.1GB |
| 7 | `fmt.(*buffer).writeString` | 87.06GB |
| 8 | `carta/value.NewCell` | 78.02GB |
| 9 | `reflect.unsafe_NewArray` | 68.83GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.08GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.83GB | 6.82GB | 6.60GB | 0B |
| `evaluation.mergeMetadata` | 3.58GB | 3.58GB | 3.46GB | 0B |
| `local.(*Client).EvaluateV2` | 10.41GB | 10.39GB | 10.07GB | 0B |
| `local.topologicalSort` | 1.45GB | 1.45GB | 1.40GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.96GB | 9.94GB | 9.63GB | 512.01kB |
| `localEvaluation.GetFeatureFlagPayload` | 1.41GB | 1.40GB | 1.36GB | 0B |
| `localEvaluation.getMapOfValue` | 9.96GB | 9.94GB | 9.63GB | 512.01kB |
| `utils.ParseFeatureFlag` | 9.98GB | 9.96GB | 9.65GB | 512.01kB |

**Total FF alloc (current snapshot):** 53.58GB  |  **24h avg:** 51.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 50/2869 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 55.14MB | 79/2869 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2520/2869 | `███████░░░░░░░░ 53%` |
| 4 | `runtime.mallocgc` | 28.95MB | 2520/2869 | `██████░░░░░░░░░ 41%` |
| 5 | `database/sql.convertAssignRows` | 28.63MB | 100/2869 | `██████░░░░░░░░░ 41%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2869 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.87MB | 1931/2869 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2869 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2869 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2869 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2869 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2869 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2869 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2869 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 50.02GB | 1386/2869 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2869 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 40.77GB | 2243/2869 | `████░░░░░░░░░░░ 32%` |
| 8 | `reflect.growslice` | 39.67GB | 2081/2869 | `████░░░░░░░░░░░ 31%` |
| 9 | `jackskj/carta.getUniqueId` | 34.54GB | 2097/2869 | `████░░░░░░░░░░░ 27%` |
| 10 | `reflect.unsafe_New` | 34.04GB | 1861/2869 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
