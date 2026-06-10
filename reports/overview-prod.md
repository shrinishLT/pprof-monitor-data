# Overview: prod
*Last updated: 2026-06-10 20:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T20:30 (2927 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,904 | avg: 14,109 | max: 84,644 | trend: INCREASING (+4.06/hr))
```
▃▃▃▂▁▁▂▂▂▃▂▂▁▁▁▁▄▇█▇▆▂▁▁▁▂▂▂▂▁▂▁▁▃▂▁▂▂▁▂▂▂▁▁▁▂▂▂▂▁▁▁▂▅▂▁▁▁▁▁▁▁▃▄▁▂▃▃▃▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▁▁▁▆▁▃▄▃▃
```

**Heap InUse** (current: 302.6MB | avg: 228.3MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▄▃▅▂▂▂▃▄▅▃▃▄▁▁▁▆█▆▆▆▆▃▄▂▃▂▃▃▂▆▂▂▃▃▄▃▂▂▃▂▂▂▁▃▄▃▅▂▃▂▃▄▅▄▂▁▃▁▃▁▁▃▅▂▂▄▆▅▄▄▄▂▃▂▂▂▄▅▄▄▅▂▁▃▅▃▄▃▁▆▃▄▄▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,904 | 16,311 | -407 | 14,109 | 84,644 | INCREASING (+4.06/hr) |
| Heap InUse | 302.6MB | 298.1MB | +4.5MB | 228.3MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3341.4MB | 3342.4MB | -1.0MB | 2583.3MB | 6883.9MB | |
| Heap Objects | 1,035,400 | 633,766 | +401634 | 987,688 | 17,165,538 | |

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
| 2026-06-10 | 246 | 16,643 | 309.3MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 16.12MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 141.35GB |
| 2 | `reflect.growslice` | 138.66GB |
| 3 | `jackskj/carta.getUniqueId` | 124.21GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.82GB |
| 5 | `reflect.unsafe_New` | 109.91GB |
| 6 | `fmt.Sprintf` | 97.07GB |
| 7 | `fmt.(*buffer).writeString` | 87.44GB |
| 8 | `carta/value.NewCell` | 78.56GB |
| 9 | `reflect.unsafe_NewArray` | 72.23GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 58.96GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.35GB | 7.35GB | 7.16GB | 0B |
| `evaluation.mergeMetadata` | 3.86GB | 3.85GB | 3.76GB | 0B |
| `local.(*Client).EvaluateV2` | 11.21GB | 11.20GB | 10.91GB | 0B |
| `local.topologicalSort` | 1.56GB | 1.56GB | 1.52GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.68GB | 10.67GB | 10.41GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.55GB | 1.55GB | 1.50GB | 0B |
| `localEvaluation.getMapOfValue` | 10.68GB | 10.67GB | 10.41GB | 0B |
| `utils.ParseFeatureFlag` | 10.69GB | 10.68GB | 10.43GB | 0B |

**Total FF alloc (current snapshot):** 57.57GB  |  **24h avg:** 56.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 66.73MB | 52/2927 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2927 | `████████████░░░ 81%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2578/2927 | `████████░░░░░░░ 54%` |
| 4 | `runtime.mallocgc` | 29.44MB | 2578/2927 | `██████░░░░░░░░░ 44%` |
| 5 | `database/sql.convertAssignRows` | 28.37MB | 101/2927 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2927 | `████░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 15.69MB | 1986/2927 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2927 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2927 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2927 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2927 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2927 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2927 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 52.54GB | 1444/2927 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2927 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2927 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 43.22GB | 2301/2927 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 42.34GB | 2139/2927 | `█████░░░░░░░░░░ 33%` |
| 9 | `jackskj/carta.getUniqueId` | 36.94GB | 2155/2927 | `████░░░░░░░░░░░ 29%` |
| 10 | `reflect.unsafe_New` | 36.32GB | 1919/2927 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
