# Overview: prod
*Last updated: 2026-06-05 10:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:45 (1372 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 56,714 | avg: 11,952 | max: 84,644 | trend: decreasing (-2.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█
```

**Heap InUse** (current: 1061.1MB | avg: 183.5MB | max: 3154.1MB | trend: stable (+0.00MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▄▄
```

## Current Status

Goroutines: `█████████████░░░░░░░ 67%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 56,714 | 49,983 | +6731 | 11,952 | 84,644 | decreasing (-2.61/hr) |
| Heap InUse | 1061.1MB | 1051.8MB | +9.3MB | 183.5MB | 3154.1MB | stable (+0.00MB/hr) |
| Heap Sys | 4260.6MB | 4283.0MB | -22.4MB | 2706.3MB | 6883.9MB | |
| Heap Objects | 2,802,967 | 3,963,189 | -1160222 | 814,483 | 17,165,538 | |

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
| 2026-06-05 | 130 | 16,462 | 271.6MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 198.53MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 96.94MB |
| 3 | `bufio.NewReaderSize` | 88.33MB |
| 4 | `bufio.NewWriterSize` | 76.8MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 39.53MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `runtime.mallocgc` | 29.02MB |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 20.51MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 19.02MB |
| 10 | `net/http.(*Transport).dialConn` | 16.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 11.11GB |
| 2 | `jackskj/carta.getUniqueId` | 10.44GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.38GB |
| 4 | `reflect.unsafe_New` | 9.08GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 6 | `fmt.(*buffer).writeString` | 6.63GB |
| 7 | `carta/value.NewCell` | 6.6GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.2GB |
| 9 | `fmt.Sprintf` | 4.74GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 4.19GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 291.02MB | 286.48MB | 148.39MB | 0B |
| `evaluation.mergeMetadata` | 150.54MB | 149.04MB | 75.89MB | 0B |
| `local.(*Client).EvaluateV2` | 431.20MB | 423.57MB | 220.54MB | 0B |
| `local.topologicalSort` | 54.13MB | 53.12MB | 30.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 454.73MB | 445.56MB | 228.75MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.02MB | 22.02MB | 15.04MB | 0B |
| `localEvaluation.getMapOfValue` | 454.73MB | 445.56MB | 228.75MB | 0B |
| `utils.ParseFeatureFlag` | 454.73MB | 445.56MB | 228.77MB | 0B |

**Total FF alloc (current snapshot):** 2.26GB  |  **24h avg:** 1.15GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1372 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1372 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1372 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1023/1372 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.03MB | 1023/1372 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1372 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.23MB | 786/1372 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1372 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1372 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.87MB | 23/1372 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1372 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1372 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1372 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1372 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1372 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.93GB | 994/1372 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1372 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1372 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.42GB | 197/1372 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.38GB | 572/1372 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
