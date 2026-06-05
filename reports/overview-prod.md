# Overview: prod
*Last updated: 2026-06-05 10:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:15 (1366 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 31,703 | avg: 11,814 | max: 84,644 | trend: decreasing (-3.87/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▅█
```

**Heap InUse** (current: 522.7MB | avg: 180.5MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 37%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 31,703 | 25,928 | +5775 | 11,814 | 84,644 | decreasing (-3.87/hr) |
| Heap InUse | 522.7MB | 417.6MB | +105.1MB | 180.5MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 4357.9MB | 4383.8MB | -25.9MB | 2699.2MB | 6883.9MB | |
| Heap Objects | 1,419,903 | 1,548,295 | -128392 | 804,410 | 17,165,538 | |

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
| 2026-06-05 | 124 | 15,156 | 242.8MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 98.5MB |
| 2 | `bufio.NewWriterSize` | 50.19MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 40.69MB |
| 4 | `bufio.NewReaderSize` | 40.65MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 20.17MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 14.51MB |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `crypto/tls.Client` | 9.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 2 | `reflect.growslice` | 6.77GB |
| 3 | `jackskj/carta.getUniqueId` | 6.57GB |
| 4 | `reflect.unsafe_New` | 5.54GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 4.55GB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.48GB |
| 7 | `carta/value.NewCell` | 4.02GB |
| 8 | `fmt.(*buffer).writeString` | 3.99GB |
| 9 | `fmt.Sprintf` | 3.29GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 3.26GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 250.12MB | 239.96MB | 151.12MB | 0B |
| `evaluation.mergeMetadata` | 125.03MB | 120.53MB | 76.71MB | 0B |
| `local.(*Client).EvaluateV2` | 372.17MB | 358.36MB | 226.20MB | 0B |
| `local.topologicalSort` | 48.05MB | 47.55MB | 32.05MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 394.10MB | 380.27MB | 231.30MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 18.51MB | 18.01MB | 18.48MB | 0B |
| `localEvaluation.getMapOfValue` | 394.10MB | 380.27MB | 231.30MB | 0B |
| `utils.ParseFeatureFlag` | 394.10MB | 380.27MB | 231.45MB | 0B |

**Total FF alloc (current snapshot):** 1.95GB  |  **24h avg:** 1.17GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1366 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1366 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1366 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1017/1366 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1366 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.99MB | 1017/1366 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.25MB | 780/1366 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1366 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1366 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.61MB | 18/1366 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1366 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1366 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1366 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1366 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1366 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.09GB | 988/1366 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1366 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.08GB | 911/1366 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.45GB | 191/1366 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.44GB | 566/1366 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
