# Overview: prod
*Last updated: 2026-06-05 10:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:20 (1367 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 38,661 | avg: 11,834 | max: 84,644 | trend: decreasing (-3.69/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆█
```

**Heap InUse** (current: 800.8MB | avg: 181.0MB | max: 3154.1MB | trend: stable (-0.02MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 45%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 38,661 | 31,703 | +6958 | 11,834 | 84,644 | decreasing (-3.69/hr) |
| Heap InUse | 800.8MB | 522.7MB | +278.1MB | 181.0MB | 3154.1MB | stable (-0.02MB/hr) |
| Heap Sys | 4331.0MB | 4357.9MB | -26.9MB | 2700.4MB | 6883.9MB | |
| Heap Objects | 3,293,245 | 1,419,903 | +1873342 | 806,231 | 17,165,538 | |

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
| 2026-06-05 | 125 | 15,344 | 247.3MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 125.37MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 58.77MB |
| 3 | `bufio.NewWriterSize` | 46.68MB |
| 4 | `bufio.NewReaderSize` | 44.17MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 24.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 15.51MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 15.01MB |
| 9 | `crypto/tls.Client` | 12.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 10.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 2 | `reflect.growslice` | 7.91GB |
| 3 | `jackskj/carta.getUniqueId` | 7.59GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 6.72GB |
| 5 | `reflect.unsafe_New` | 6.4GB |
| 6 | `carta/value.NewCell` | 4.67GB |
| 7 | `fmt.(*buffer).writeString` | 4.67GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.61GB |
| 9 | `fmt.Sprintf` | 3.7GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 256.71MB | 250.12MB | 150.62MB | 0B |
| `evaluation.mergeMetadata` | 128.53MB | 125.03MB | 76.52MB | 0B |
| `local.(*Client).EvaluateV2` | 381.33MB | 372.17MB | 225.20MB | 0B |
| `local.topologicalSort` | 49.56MB | 48.05MB | 31.74MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 401.75MB | 394.10MB | 230.76MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 20.01MB | 18.51MB | 17.96MB | 0B |
| `localEvaluation.getMapOfValue` | 401.75MB | 394.10MB | 230.76MB | 0B |
| `utils.ParseFeatureFlag` | 401.75MB | 394.10MB | 230.88MB | 0B |

**Total FF alloc (current snapshot):** 1.99GB  |  **24h avg:** 1.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1367 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1367 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1367 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1018/1367 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1367 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.99MB | 1018/1367 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.39MB | 781/1367 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1367 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1367 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.61MB | 18/1367 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1367 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1367 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1367 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1367 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1367 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.06GB | 989/1367 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1367 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1367 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.44GB | 192/1367 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.43GB | 567/1367 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
