# Overview: prod
*Last updated: 2026-06-17 10:41 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T10:41 (4821 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 48,508 | avg: 14,921 | max: 84,644 | trend: INCREASING (+2.14/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▅▃▆█▇
```

**Heap InUse** (current: 1186.4MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▃▃▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▃▄▅▄▄▆█
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 57%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 48,508 | 50,346 | -1838 | 14,921 | 84,644 | INCREASING (+2.14/hr) |
| Heap InUse | 1186.4MB | 925.8MB | +260.6MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1462.9MB | 1446.8MB | +16.1MB | 2427.1MB | 6883.9MB | |
| Heap Objects | 5,412,005 | 2,654,249 | +2757756 | 1,053,239 | 17,165,538 | |

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
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 129 | 16,665 | 245.1MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 178.39MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 86.9MB |
| 3 | `bufio.NewReaderSize` | 71.29MB |
| 4 | `bufio.NewWriterSize` | 64.25MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 34.53MB |
| 7 | `runtime.mallocgc` | 29.01MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 18.52MB |
| 9 | `net/http.(*Transport).dialConn` | 16.5MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 14.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 32.19GB |
| 2 | `segmentio/kafka-go.makePartitions` | 31.93GB |
| 3 | `jackskj/carta.getUniqueId` | 29.32GB |
| 4 | `reflect.unsafe_New` | 25.89GB |
| 5 | `fmt.Sprintf` | 23.94GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.71GB |
| 7 | `fmt.(*buffer).writeString` | 19.55GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 19.35GB |
| 9 | `carta/value.NewCell` | 18.1GB |
| 10 | `reflect.unsafe_NewArray` | 16.5GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.96GB | 1.95GB | 1.82GB | 0B |
| `evaluation.mergeMetadata` | 1.01GB | 1.01GB | 961.84MB | 0B |
| `local.(*Client).EvaluateV2` | 3.00GB | 2.99GB | 2.79GB | 0B |
| `local.topologicalSort` | 420.51MB | 419.50MB | 390.51MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.91GB | 2.90GB | 2.70GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 385.39MB | 384.89MB | 373.06MB | 0B |
| `localEvaluation.getMapOfValue` | 2.91GB | 2.90GB | 2.70GB | 0B |
| `utils.ParseFeatureFlag` | 2.92GB | 2.91GB | 2.70GB | 0B |

**Total FF alloc (current snapshot):** 15.50GB  |  **24h avg:** 14.39GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.87MB | 103/4821 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4472/4821 | `██████████████░ 96%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.73MB | 137/4821 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.28MB | 4472/4821 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 19.85MB | 161/4821 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4821 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.73MB | 3548/4821 | `██████░░░░░░░░░ 41%` |
| 8 | `net/http.(*Transport).dialConn` | 13.15MB | 135/4821 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4821 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4821 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4821 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.76GB | 2738/4821 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4821 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4821 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.48GB | 4195/4821 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.19GB | 4033/4821 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.72GB | 4049/4821 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4821 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 51.0GB | 3813/4821 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.72GB | 3224/4821 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
