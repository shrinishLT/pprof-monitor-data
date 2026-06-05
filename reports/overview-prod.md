# Overview: prod
*Last updated: 2026-06-05 10:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:50 (1373 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 50,527 | avg: 11,980 | max: 84,644 | trend: decreasing (-2.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆
```

**Heap InUse** (current: 1251.5MB | avg: 184.3MB | max: 3154.1MB | trend: stable (+0.01MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▄▄▅
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 59%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 50,527 | 56,714 | -6187 | 11,980 | 84,644 | decreasing (-2.36/hr) |
| Heap InUse | 1251.5MB | 1061.1MB | +190.4MB | 184.3MB | 3154.1MB | stable (+0.01MB/hr) |
| Heap Sys | 4270.5MB | 4260.6MB | +9.9MB | 2707.4MB | 6883.9MB | |
| Heap Objects | 5,563,670 | 2,802,967 | +2760703 | 817,942 | 17,165,538 | |

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
| 2026-06-05 | 131 | 16,722 | 279.1MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 191.5MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 80.37MB |
| 3 | `bufio.NewWriterSize` | 79.31MB |
| 4 | `bufio.NewReaderSize` | 70.27MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 36.53MB |
| 7 | `runtime.mallocgc` | 31.36MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 20.02MB |
| 9 | `net/http.(*Transport).dialConn` | 16.5MB |
| 10 | `reflect.growslice` | 14.45MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 11.72GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.32GB |
| 3 | `jackskj/carta.getUniqueId` | 11.11GB |
| 4 | `reflect.unsafe_New` | 9.64GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 6 | `carta/value.NewCell` | 7.03GB |
| 7 | `fmt.(*buffer).writeString` | 6.99GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.31GB |
| 9 | `fmt.Sprintf` | 4.99GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 4.43GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 295.10MB | 291.02MB | 147.86MB | 0B |
| `evaluation.mergeMetadata` | 153.04MB | 150.54MB | 75.72MB | 0B |
| `local.(*Client).EvaluateV2` | 438.86MB | 431.20MB | 219.55MB | 0B |
| `local.topologicalSort` | 55.15MB | 54.13MB | 29.69MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 461.90MB | 454.73MB | 228.32MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 23.03MB | 22.02MB | 14.42MB | 0B |
| `localEvaluation.getMapOfValue` | 461.90MB | 454.73MB | 228.32MB | 0B |
| `utils.ParseFeatureFlag` | 461.90MB | 454.73MB | 228.32MB | 0B |

**Total FF alloc (current snapshot):** 2.30GB  |  **24h avg:** 1.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1373 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1373 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1373 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1024/1373 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.05MB | 1024/1373 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1373 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.45MB | 787/1373 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1373 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1373 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1373 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1373 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1373 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1373 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1373 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1373 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.9GB | 995/1373 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1373 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1373 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.43GB | 198/1373 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.37GB | 573/1373 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
