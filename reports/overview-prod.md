# Overview: prod
*Last updated: 2026-06-11 10:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T10:45 (3098 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 58,841 | avg: 14,222 | max: 84,644 | trend: INCREASING (+3.85/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█
```

**Heap InUse** (current: 1347.4MB | avg: 232.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇█
```

## Current Status

Goroutines: `█████████████░░░░░░░ 69%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 19%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 58,841 | 48,188 | +10653 | 14,222 | 84,644 | INCREASING (+3.85/hr) |
| Heap InUse | 1347.4MB | 1241.5MB | +105.9MB | 232.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3173.8MB | 3201.8MB | -28.0MB | 2624.8MB | 6883.9MB | |
| Heap Objects | 5,488,066 | 5,838,587 | -350521 | 1,002,781 | 17,165,538 | |

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
| 2026-06-11 | 130 | 16,420 | 304.7MB | 1347.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 203.08MB |
| 2 | `bufio.NewReaderSize` | 101.4MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 94.94MB |
| 4 | `bufio.NewWriterSize` | 85.37MB |
| 5 | `runtime.mallocgc` | 50.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 38.03MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).dialConn` | 20.5MB |
| 9 | `crypto/tls.Client` | 19.52MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 16.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 170.11GB |
| 2 | `segmentio/kafka-go.makePartitions` | 161.08GB |
| 3 | `jackskj/carta.getUniqueId` | 153.51GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 139.19GB |
| 5 | `reflect.unsafe_New` | 135.54GB |
| 6 | `fmt.Sprintf` | 118.79GB |
| 7 | `fmt.(*buffer).writeString` | 107.43GB |
| 8 | `carta/value.NewCell` | 96.76GB |
| 9 | `reflect.unsafe_NewArray` | 82.22GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 78.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.44GB | 8.44GB | 8.30GB | 0B |
| `evaluation.mergeMetadata` | 4.41GB | 4.41GB | 4.34GB | 0B |
| `local.(*Client).EvaluateV2` | 12.86GB | 12.85GB | 12.64GB | 0B |
| `local.topologicalSort` | 1.78GB | 1.78GB | 1.74GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 12.31GB | 12.30GB | 12.08GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.73GB | 1.73GB | 1.72GB | 0B |
| `localEvaluation.getMapOfValue` | 12.31GB | 12.30GB | 12.08GB | 0B |
| `utils.ParseFeatureFlag` | 12.33GB | 12.32GB | 12.09GB | 0B |

**Total FF alloc (current snapshot):** 66.18GB  |  **24h avg:** 64.99GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3098 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3098 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2749/3098 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 30.74MB | 2749/3098 | `███████░░░░░░░░ 51%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3098 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3098 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.65MB | 2130/3098 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.37MB | 67/3098 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3098 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3098 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3098 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3098 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3098 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 59.67GB | 1615/3098 | `███████░░░░░░░░ 47%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/3098 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 50.69GB | 2472/3098 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 50.19GB | 2310/3098 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 44.06GB | 2326/3098 | `█████░░░░░░░░░░ 35%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3098 | `█████░░░░░░░░░░ 34%` |
| 10 | `reflect.unsafe_New` | 43.01GB | 2090/3098 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
