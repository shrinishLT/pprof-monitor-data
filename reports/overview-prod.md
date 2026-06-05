# Overview: prod
*Last updated: 2026-06-05 10:28 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T10:28 (1368 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 29,406 | avg: 11,847 | max: 84,644 | trend: decreasing (-3.57/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆█▅
```

**Heap InUse** (current: 693.7MB | avg: 181.3MB | max: 3154.1MB | trend: stable (-0.02MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 34%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 29,406 | 38,661 | -9255 | 11,847 | 84,644 | decreasing (-3.57/hr) |
| Heap InUse | 693.7MB | 800.8MB | -107.1MB | 181.3MB | 3154.1MB | stable (-0.02MB/hr) |
| Heap Sys | 4364.5MB | 4331.0MB | +33.5MB | 2701.6MB | 6883.9MB | |
| Heap Objects | 3,465,905 | 3,293,245 | +172660 | 808,175 | 17,165,538 | |

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
| 2026-06-05 | 126 | 15,456 | 250.8MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 78.12MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 48.22MB |
| 3 | `bufio.NewReaderSize` | 37.64MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `bufio.NewWriterSize` | 27.6MB |
| 6 | `runtime.mallocgc` | 24.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 18.52MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 8.01MB |
| 10 | `net/http.(*Transport).dialConn` | 8.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 8.64GB |
| 2 | `jackskj/carta.getUniqueId` | 8.27GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 8.18GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.36GB |
| 5 | `reflect.unsafe_New` | 7.02GB |
| 6 | `carta/value.NewCell` | 5.12GB |
| 7 | `fmt.(*buffer).writeString` | 5.1GB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.81GB |
| 9 | `fmt.Sprintf` | 3.92GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 3.3GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 270.80MB | 256.71MB | 150.27MB | 0B |
| `evaluation.mergeMetadata` | 139.03MB | 128.53MB | 76.49MB | 0B |
| `local.(*Client).EvaluateV2` | 401.18MB | 381.33MB | 224.38MB | 0B |
| `local.topologicalSort` | 51.10MB | 49.56MB | 31.42MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 421.61MB | 401.75MB | 230.44MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 21.52MB | 20.01MB | 17.42MB | 0B |
| `localEvaluation.getMapOfValue` | 421.61MB | 401.75MB | 230.44MB | 0B |
| `utils.ParseFeatureFlag` | 421.61MB | 401.75MB | 230.55MB | 0B |

**Total FF alloc (current snapshot):** 2.10GB  |  **24h avg:** 1.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1368 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1368 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1368 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1019/1368 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1368 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 18.0MB | 1019/1368 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.47MB | 782/1368 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1368 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 12.05MB | 2/1368 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.42MB | 19/1368 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1368 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1368 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1368 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1368 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1368 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 34.03GB | 990/1368 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1368 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.07GB | 912/1368 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.43GB | 193/1368 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.42GB | 568/1368 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.1x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
