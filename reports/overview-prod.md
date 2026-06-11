# Overview: prod
*Last updated: 2026-06-11 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T05:31 (3035 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,572 | avg: 14,143 | max: 84,644 | trend: INCREASING (+3.77/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 266.9MB | avg: 230.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂▁▁▁▂▂▁▁▂▁▂▂▃▂▅▃▂▂▂▂▂▁▁▂▃▁▂▁▂▂▂▂▃▁▂▂▂▃▃▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,572 | 16,235 | -663 | 14,143 | 84,644 | INCREASING (+3.77/hr) |
| Heap InUse | 266.9MB | 396.3MB | -129.4MB | 230.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3344.2MB | 3342.9MB | +1.3MB | 2610.1MB | 6883.9MB | |
| Heap Objects | 876,432 | 1,894,827 | -1018395 | 993,234 | 17,165,538 | |

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
| 2026-06-11 | 67 | 14,933 | 271.7MB | 428.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bufio.NewWriterSize` | 7.06MB |
| 6 | `bytes.growSlice` | 7.04MB |
| 7 | `bufio.NewReaderSize` | 5.05MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 155.8GB |
| 2 | `segmentio/kafka-go.makePartitions` | 153.76GB |
| 3 | `jackskj/carta.getUniqueId` | 140.67GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 125.51GB |
| 5 | `reflect.unsafe_New` | 124.17GB |
| 6 | `fmt.Sprintf` | 113.16GB |
| 7 | `fmt.(*buffer).writeString` | 98.71GB |
| 8 | `carta/value.NewCell` | 88.58GB |
| 9 | `reflect.unsafe_NewArray` | 78.59GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 73.72GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.11GB | 8.10GB | 7.96GB | 0B |
| `evaluation.mergeMetadata` | 4.24GB | 4.24GB | 4.16GB | 0B |
| `local.(*Client).EvaluateV2` | 12.35GB | 12.34GB | 12.13GB | 0B |
| `local.topologicalSort` | 1.70GB | 1.70GB | 1.68GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.78GB | 11.77GB | 11.56GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.70GB | 1.69GB | 1.68GB | 0B |
| `localEvaluation.getMapOfValue` | 11.78GB | 11.77GB | 11.56GB | 0B |
| `utils.ParseFeatureFlag` | 11.80GB | 11.79GB | 11.58GB | 0B |

**Total FF alloc (current snapshot):** 63.45GB  |  **24h avg:** 62.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/3035 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.2MB | 84/3035 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2686/3035 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 30.28MB | 2686/3035 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3035 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3035 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.37MB | 2084/3035 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.4MB | 61/3035 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3035 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3035 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3035 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3035 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3035 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 56.83GB | 1552/3035 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3035 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 47.9GB | 2409/3035 | `█████░░░░░░░░░░ 38%` |
| 7 | `reflect.growslice` | 47.1GB | 2247/3035 | `█████░░░░░░░░░░ 37%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3035 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 41.26GB | 2263/3035 | `████░░░░░░░░░░░ 32%` |
| 10 | `reflect.unsafe_New` | 40.38GB | 2027/3035 | `████░░░░░░░░░░░ 32%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
