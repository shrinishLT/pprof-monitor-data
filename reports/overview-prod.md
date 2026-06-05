# Overview: prod
*Last updated: 2026-06-05 10:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:40 (1371 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 49,983 | avg: 11,920 | max: 84,644 | trend: decreasing (-2.90/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▅▃▅▇█
```

**Heap InUse** (current: 1051.8MB | avg: 182.9MB | max: 3154.1MB | trend: stable (-0.00MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▄
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 59%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 49,983 | 48,858 | +1125 | 11,920 | 84,644 | decreasing (-2.90/hr) |
| Heap InUse | 1051.8MB | 824.5MB | +227.3MB | 182.9MB | 3154.1MB | stable (-0.00MB/hr) |
| Heap Sys | 4283.0MB | 4294.2MB | -11.2MB | 2705.1MB | 6883.9MB | |
| Heap Objects | 3,963,189 | 1,799,415 | +2163774 | 813,032 | 17,165,538 | |

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
| 2026-06-05 | 129 | 16,149 | 265.5MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 184.97MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 89.41MB |
| 3 | `bufio.NewWriterSize` | 78.8MB |
| 4 | `bufio.NewReaderSize` | 72.78MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 30.53MB |
| 7 | `runtime.mallocgc` | 29.02MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 21.52MB |
| 9 | `net/http.(*Transport).dialConn` | 20.0MB |
| 10 | `crypto/tls.Client` | 19.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 10.39GB |
| 2 | `jackskj/carta.getUniqueId` | 9.81GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.34GB |
| 4 | `reflect.unsafe_New` | 8.47GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 6 | `fmt.(*buffer).writeString` | 6.18GB |
| 7 | `carta/value.NewCell` | 6.17GB |
| 8 | `segmentio/kafka-go.makePartitions` | 5.09GB |
| 9 | `fmt.Sprintf` | 4.47GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 286.48MB | 283.96MB | 148.92MB | 0B |
| `evaluation.mergeMetadata` | 149.04MB | 147.04MB | 76.11MB | 0B |
| `local.(*Client).EvaluateV2` | 423.57MB | 418.96MB | 221.55MB | 0B |
| `local.topologicalSort` | 53.12MB | 52.61MB | 30.41MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 445.56MB | 440.44MB | 229.18MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 22.02MB | 22.02MB | 15.67MB | 0B |
| `localEvaluation.getMapOfValue` | 445.56MB | 440.44MB | 229.18MB | 0B |
| `utils.ParseFeatureFlag` | 445.56MB | 440.44MB | 229.22MB | 0B |

**Total FF alloc (current snapshot):** 2.22GB  |  **24h avg:** 1.15GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1371 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1371 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1371 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1022/1371 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.02MB | 1022/1371 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1371 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.0MB | 785/1371 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1371 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1371 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.68MB | 22/1371 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1371 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1371 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1371 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1371 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1371 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 33.96GB | 993/1371 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1371 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1371 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.41GB | 196/1371 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.39GB | 571/1371 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
