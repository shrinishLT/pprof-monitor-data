# Overview: prod
*Last updated: 2026-06-10 18:09 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T18:09 (2898 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,653 | avg: 14,097 | max: 84,644 | trend: INCREASING (+4.13/hr))
```
▂▂▃▄▃▄▅▆█▇▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 316.0MB | avg: 227.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▂▂▃▄▃▆▅▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,653 | 15,241 | +412 | 14,097 | 84,644 | INCREASING (+4.13/hr) |
| Heap InUse | 316.0MB | 251.7MB | +64.3MB | 227.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3338.7MB | 3339.3MB | -0.6MB | 2575.7MB | 6883.9MB | |
| Heap Objects | 1,456,377 | 886,501 | +569876 | 985,638 | 17,165,538 | |

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
| 2026-06-10 | 217 | 16,827 | 311.8MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bufio.NewWriterSize` | 8.55MB |
| 5 | `bytes.growSlice` | 8.05MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `bufio.NewReaderSize` | 2.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 138.31GB |
| 2 | `segmentio/kafka-go.makePartitions` | 138.09GB |
| 3 | `jackskj/carta.getUniqueId` | 123.74GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.74GB |
| 5 | `reflect.unsafe_New` | 109.5GB |
| 6 | `fmt.Sprintf` | 94.65GB |
| 7 | `fmt.(*buffer).writeString` | 87.26GB |
| 8 | `carta/value.NewCell` | 78.3GB |
| 9 | `reflect.unsafe_NewArray` | 70.56GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.47GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.11GB | 7.10GB | 6.89GB | 0B |
| `evaluation.mergeMetadata` | 3.74GB | 3.73GB | 3.62GB | 0B |
| `local.(*Client).EvaluateV2` | 10.85GB | 10.83GB | 10.50GB | 0B |
| `local.topologicalSort` | 1.51GB | 1.50GB | 1.46GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.35GB | 10.33GB | 10.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.49GB | 1.49GB | 1.42GB | 0B |
| `localEvaluation.getMapOfValue` | 10.35GB | 10.33GB | 10.04GB | 0B |
| `utils.ParseFeatureFlag` | 10.37GB | 10.35GB | 10.05GB | 0B |

**Total FF alloc (current snapshot):** 55.77GB  |  **24h avg:** 54.02GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 67.8MB | 51/2898 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 55.14MB | 79/2898 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2549/2898 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.2MB | 2549/2898 | `██████░░░░░░░░░ 43%` |
| 5 | `database/sql.convertAssignRows` | 28.63MB | 100/2898 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2898 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.79MB | 1957/2898 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2898 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2898 | `███░░░░░░░░░░░░ 20%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2898 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2898 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2898 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2898 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 51.3GB | 1415/2898 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2898 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2898 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 41.99GB | 2272/2898 | `█████░░░░░░░░░░ 33%` |
| 8 | `reflect.growslice` | 41.02GB | 2110/2898 | `████░░░░░░░░░░░ 32%` |
| 9 | `jackskj/carta.getUniqueId` | 35.76GB | 2126/2898 | `████░░░░░░░░░░░ 28%` |
| 10 | `reflect.unsafe_New` | 35.19GB | 1890/2898 | `████░░░░░░░░░░░ 28%` |

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
