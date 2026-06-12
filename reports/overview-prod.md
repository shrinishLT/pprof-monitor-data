# Overview: prod
*Last updated: 2026-06-12 13:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T13:12 (3415 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,832 | avg: 14,431 | max: 84,644 | trend: INCREASING (+3.55/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 165.4MB | avg: 239.6MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,832 | 15,079 | -247 | 14,431 | 84,644 | INCREASING (+3.55/hr) |
| Heap InUse | 165.4MB | 154.0MB | +11.4MB | 239.6MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 400.7MB | 401.4MB | -0.7MB | 2675.4MB | 6883.9MB | |
| Heap Objects | 663,007 | 331,375 | +331632 | 1,028,043 | 17,165,538 | |

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
| 2026-06-12 | 159 | 16,577 | 300.7MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `bufio.NewReaderSize` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 2.61GB |
| 2 | `jackskj/carta.getUniqueId` | 2.59GB |
| 3 | `reflect.unsafe_New` | 2.18GB |
| 4 | `segmentio/kafka-go.makePartitions` | 1.66GB |
| 5 | `fmt.Sprintf` | 1.64GB |
| 6 | `carta/value.NewCell` | 1.57GB |
| 7 | `fmt.(*buffer).writeString` | 1.38GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.23GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 1.07GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.01GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 125.82MB | 113.14MB | 7.11GB | 0B |
| `evaluation.mergeMetadata` | 73.52MB | 65.02MB | 3.71GB | 0B |
| `local.(*Client).EvaluateV2` | 176.59MB | 161.84MB | 10.82GB | 0B |
| `local.topologicalSort` | 23.26MB | 23.26MB | 1.51GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 161.29MB | 144.96MB | 10.35GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 29.14MB | 28.64MB | 1.47GB | 0B |
| `localEvaluation.getMapOfValue` | 161.29MB | 144.96MB | 10.35GB | 0B |
| `utils.ParseFeatureFlag` | 161.79MB | 145.46MB | 10.37GB | 0B |

**Total FF alloc (current snapshot):** 912.70MB  |  **24h avg:** 55.68GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3415 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3415 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3066/3415 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.56MB | 3066/3415 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3415 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3415 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.88MB | 2409/3415 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3415 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3415 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3415 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3415 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3415 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3415 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.1GB | 1919/3415 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 65.07GB | 2627/3415 | `███████░░░░░░░░ 52%` |
| 6 | `segmentio/kafka-go.makePartitions` | 64.19GB | 2789/3415 | `███████░░░░░░░░ 51%` |
| 7 | `jackskj/carta.getUniqueId` | 57.64GB | 2643/3415 | `██████░░░░░░░░░ 46%` |
| 8 | `reflect.unsafe_New` | 55.61GB | 2407/3415 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3415 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 49.45GB | 2146/3415 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
