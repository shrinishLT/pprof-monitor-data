# Overview: prod
*Last updated: 2026-06-11 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T21:32 (3227 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,059 | avg: 14,291 | max: 84,644 | trend: INCREASING (+3.65/hr))
```
▂▁▂▂▂▂▂▃▂▁▁▁▂▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▂▃▂▁▁▂▅▇▆▅▄▇▂▃▃▄▁▁▁▂▅▇▆▆▇▆▁▁▁▂▁▁▁▁▁▁▁▁▆▆█▆▄
```

**Heap InUse** (current: 437.4MB | avg: 235.4MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▃▂▃▂▃▂▃▄▃▂▁▄▁▂▃▂▂▁▁▃▁▃▁▃▂▃▂▂▄▂▃▂▁▁▁▆▃▂▂▂▁▂▂▂▄▃▂▄▄▄▄▄▂▃▃▁▂▃▄▇▆▅▄▆▃▄▃▄▂▁▂▂▄▅▆▇█▆▁▂▂▂▂▁▁▁▁▁▁▂▅▆▆▆▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,059 | 18,990 | -1931 | 14,291 | 84,644 | INCREASING (+3.65/hr) |
| Heap InUse | 437.4MB | 427.9MB | +9.5MB | 235.4MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3331.8MB | 3329.2MB | +2.6MB | 2652.8MB | 6883.9MB | |
| Heap Objects | 1,657,264 | 1,641,329 | +15935 | 1,012,242 | 17,165,538 | |

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
| 2026-06-11 | 259 | 16,194 | 308.1MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `bytes.growSlice` | 41.4MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 19.09MB |
| 5 | `bufio.NewWriterSize` | 16.58MB |
| 6 | `bufio.NewReaderSize` | 14.57MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 10 | `crypto/tls.Client` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.42GB |
| 2 | `segmentio/kafka-go.makePartitions` | 175.85GB |
| 3 | `jackskj/carta.getUniqueId` | 161.93GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.16GB |
| 5 | `reflect.unsafe_New` | 142.66GB |
| 6 | `fmt.Sprintf` | 131.2GB |
| 7 | `fmt.(*buffer).writeString` | 112.28GB |
| 8 | `carta/value.NewCell` | 101.88GB |
| 9 | `reflect.unsafe_NewArray` | 89.75GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.73GB | 9.72GB | 9.50GB | 0B |
| `evaluation.mergeMetadata` | 5.08GB | 5.08GB | 4.96GB | 0B |
| `local.(*Client).EvaluateV2` | 14.81GB | 14.80GB | 14.47GB | 0B |
| `local.topologicalSort` | 2.05GB | 2.05GB | 2.00GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.12GB | 14.11GB | 13.81GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.05GB | 2.05GB | 1.99GB | 0B |
| `localEvaluation.getMapOfValue` | 14.12GB | 14.11GB | 13.81GB | 0B |
| `utils.ParseFeatureFlag` | 14.14GB | 14.13GB | 13.83GB | 0B |

**Total FF alloc (current snapshot):** 76.09GB  |  **24h avg:** 74.37GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3227 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3227 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2878/3227 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.63MB | 2878/3227 | `████████░░░░░░░ 53%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3227 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3227 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.62MB | 2252/3227 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3227 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.99MB | 72/3227 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3227 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3227 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3227 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3227 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 65.78GB | 1744/3227 | `███████░░░░░░░░ 52%` |
| 5 | `reflect.growslice` | 56.88GB | 2439/3227 | `██████░░░░░░░░░ 45%` |
| 6 | `segmentio/kafka-go.makePartitions` | 56.54GB | 2601/3227 | `██████░░░░░░░░░ 45%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3227 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 50.14GB | 2455/3227 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 48.71GB | 2219/3227 | `█████░░░░░░░░░░ 38%` |
| 10 | `fmt.(*buffer).writeString` | 43.7GB | 1966/3227 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
