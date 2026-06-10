# Overview: prod
*Last updated: 2026-06-10 17:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T17:06 (2886 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,140 | avg: 14,094 | max: 84,644 | trend: INCREASING (+4.17/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 289.8MB | avg: 227.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,140 | 17,905 | -2765 | 14,094 | 84,644 | INCREASING (+4.17/hr) |
| Heap InUse | 289.8MB | 330.5MB | -40.7MB | 227.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3339.5MB | 3339.1MB | +0.4MB | 2572.5MB | 6883.9MB | |
| Heap Objects | 1,199,614 | 1,292,849 | -93235 | 985,396 | 17,165,538 | |

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
| 2026-06-10 | 205 | 16,948 | 315.4MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.58MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 5.03MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `reflect.unsafe_NewArray` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 138.18GB |
| 2 | `segmentio/kafka-go.makePartitions` | 136.66GB |
| 3 | `jackskj/carta.getUniqueId` | 123.58GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.74GB |
| 5 | `reflect.unsafe_New` | 109.36GB |
| 6 | `fmt.Sprintf` | 94.12GB |
| 7 | `fmt.(*buffer).writeString` | 87.25GB |
| 8 | `carta/value.NewCell` | 78.21GB |
| 9 | `reflect.unsafe_NewArray` | 69.84GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.35GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.02GB | 7.01GB | 6.77GB | 0B |
| `evaluation.mergeMetadata` | 3.69GB | 3.68GB | 3.55GB | 0B |
| `local.(*Client).EvaluateV2` | 10.70GB | 10.69GB | 10.32GB | 0B |
| `local.topologicalSort` | 1.49GB | 1.49GB | 1.44GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.22GB | 10.21GB | 9.88GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.46GB | 1.46GB | 1.40GB | 0B |
| `localEvaluation.getMapOfValue` | 10.22GB | 10.21GB | 9.88GB | 0B |
| `utils.ParseFeatureFlag` | 10.23GB | 10.22GB | 9.89GB | 0B |

**Total FF alloc (current snapshot):** 55.03GB  |  **24h avg:** 53.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.8MB | 51/2886 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 55.14MB | 79/2886 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2537/2886 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.1MB | 2537/2886 | `██████░░░░░░░░░ 42%` |
| 5 | `database/sql.convertAssignRows` | 28.63MB | 100/2886 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2886 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.83MB | 1948/2886 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2886 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2886 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2886 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2886 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2886 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2886 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2886 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 50.78GB | 1403/2886 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2886 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 41.48GB | 2260/2886 | `████░░░░░░░░░░░ 33%` |
| 8 | `reflect.growslice` | 40.46GB | 2098/2886 | `████░░░░░░░░░░░ 32%` |
| 9 | `jackskj/carta.getUniqueId` | 35.26GB | 2114/2886 | `████░░░░░░░░░░░ 28%` |
| 10 | `reflect.unsafe_New` | 34.72GB | 1878/2886 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
