# Overview: prod
*Last updated: 2026-06-11 10:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T10:55 (3100 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 28,918 | avg: 14,241 | max: 84,644 | trend: INCREASING (+3.91/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█▇▃
```

**Heap InUse** (current: 944.1MB | avg: 232.9MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇▇█▅
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 34%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 28,918 | 58,486 | -29568 | 14,241 | 84,644 | INCREASING (+3.91/hr) |
| Heap InUse | 944.1MB | 1403.5MB | -459.4MB | 232.9MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3207.6MB | 3163.8MB | +43.8MB | 2625.2MB | 6883.9MB | |
| Heap Objects | 3,273,625 | 5,735,188 | -2461563 | 1,005,040 | 17,165,538 | |

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
| 2026-06-11 | 132 | 16,834 | 317.9MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 134.71MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 65.3MB |
| 3 | `bufio.NewWriterSize` | 57.77MB |
| 4 | `bufio.NewReaderSize` | 53.21MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 24.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 16.02MB |
| 9 | `net/http.(*Transport).dialConn` | 12.0MB |
| 10 | `crypto/tls.Client` | 11.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 171.14GB |
| 2 | `segmentio/kafka-go.makePartitions` | 161.28GB |
| 3 | `jackskj/carta.getUniqueId` | 154.55GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 140.87GB |
| 5 | `reflect.unsafe_New` | 136.43GB |
| 6 | `fmt.Sprintf` | 119.21GB |
| 7 | `fmt.(*buffer).writeString` | 108.12GB |
| 8 | `carta/value.NewCell` | 97.44GB |
| 9 | `reflect.unsafe_NewArray` | 82.33GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 78.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.45GB | 8.45GB | 8.31GB | 0B |
| `evaluation.mergeMetadata` | 4.41GB | 4.41GB | 4.34GB | 0B |
| `local.(*Client).EvaluateV2` | 12.87GB | 12.87GB | 12.66GB | 0B |
| `local.topologicalSort` | 1.78GB | 1.78GB | 1.75GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.32GB | 12.31GB | 12.09GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.73GB | 1.73GB | 1.72GB | 0B |
| `localEvaluation.getMapOfValue` | 12.32GB | 12.31GB | 12.09GB | 0B |
| `utils.ParseFeatureFlag` | 12.34GB | 12.33GB | 12.11GB | 0B |

**Total FF alloc (current snapshot):** 66.24GB  |  **24h avg:** 65.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3100 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3100 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2751/3100 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.76MB | 2751/3100 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3100 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3100 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.8MB | 2132/3100 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3100 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3100 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3100 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3100 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3100 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3100 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.77GB | 1617/3100 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3100 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 50.78GB | 2474/3100 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 50.3GB | 2312/3100 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 44.15GB | 2328/3100 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3100 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 43.1GB | 2092/3100 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
