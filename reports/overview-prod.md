# Overview: prod
*Last updated: 2026-06-05 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:31 (1369 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 36,994 | avg: 11,865 | max: 84,644 | trend: decreasing (-3.40/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆█▅▇
```

**Heap InUse** (current: 767.3MB | avg: 181.8MB | max: 3154.1MB | trend: stable (-0.01MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 43%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 36,994 | 29,406 | +7588 | 11,865 | 84,644 | decreasing (-3.40/hr) |
| Heap InUse | 767.3MB | 693.7MB | +73.6MB | 181.8MB | 3154.1MB | stable (-0.01MB/hr) |
| Heap Sys | 4340.7MB | 4364.5MB | -23.8MB | 2702.8MB | 6883.9MB | |
| Heap Objects | 3,321,574 | 3,465,905 | -144331 | 810,011 | 17,165,538 | |

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
| 2026-06-05 | 127 | 15,626 | 254.9MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 102.07MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 62.29MB |
| 3 | `bufio.NewReaderSize` | 59.23MB |
| 4 | `bufio.NewWriterSize` | 56.72MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 24.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 22.52MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 11.01MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `net/http.(*Transport).dialConn` | 9.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 9.01GB |
| 2 | `jackskj/carta.getUniqueId` | 8.61GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.72GB |
| 5 | `reflect.unsafe_New` | 7.32GB |
| 6 | `carta/value.NewCell` | 5.37GB |
| 7 | `fmt.(*buffer).writeString` | 5.33GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.88GB |
| 9 | `fmt.Sprintf` | 4.03GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.43GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 274.86MB | 270.80MB | 149.80MB | 0B |
| `evaluation.mergeMetadata` | 141.54MB | 139.03MB | 76.35MB | 0B |
| `local.(*Client).EvaluateV2` | 408.33MB | 401.18MB | 223.47MB | 0B |
| `local.topologicalSort` | 52.11MB | 51.10MB | 31.12MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 429.79MB | 421.61MB | 230.06MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 21.52MB | 21.52MB | 16.85MB | 0B |
| `localEvaluation.getMapOfValue` | 429.79MB | 421.61MB | 230.06MB | 0B |
| `utils.ParseFeatureFlag` | 429.79MB | 421.61MB | 230.14MB | 0B |

**Total FF alloc (current snapshot):** 2.14GB  |  **24h avg:** 1.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1369 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1369 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1369 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1020/1369 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.0MB | 1020/1369 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1369 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.59MB | 783/1369 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1369 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1369 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.3MB | 20/1369 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1369 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1369 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1369 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1369 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1369 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.01GB | 991/1369 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1369 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1369 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.42GB | 194/1369 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.41GB | 569/1369 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
