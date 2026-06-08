# Overview: prod
*Last updated: 2026-06-08 18:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T18:25 (2327 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,411 | avg: 13,556 | max: 84,644 | trend: INCREASING (+4.44/hr))
```
█▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 304.6MB | avg: 208.6MB | max: 3154.1MB | trend: stable (+0.09MB/hr))
```
█▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▁▁▂▂▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,411 | 15,654 | -243 | 13,556 | 84,644 | INCREASING (+4.44/hr) |
| Heap InUse | 304.6MB | 286.5MB | +18.1MB | 208.6MB | 3154.1MB | stable (+0.09MB/hr) |
| Heap Sys | 3333.8MB | 3333.5MB | +0.3MB | 2391.1MB | 6883.9MB | |
| Heap Objects | 1,239,410 | 965,336 | +274074 | 923,224 | 17,165,538 | |

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
| 2026-06-08 | 222 | 16,660 | 311.4MB | 2130.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 13.06MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 3.51MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 72.67GB |
| 2 | `reflect.growslice` | 65.6GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 60.13GB |
| 4 | `jackskj/carta.getUniqueId` | 56.96GB |
| 5 | `reflect.unsafe_New` | 51.21GB |
| 6 | `fmt.(*buffer).writeString` | 40.99GB |
| 7 | `fmt.Sprintf` | 38.15GB |
| 8 | `reflect.unsafe_NewArray` | 37.12GB |
| 9 | `carta/value.NewCell` | 36.54GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 24.97GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.82GB | 2.82GB | 2.54GB | 0B |
| `evaluation.mergeMetadata` | 1.46GB | 1.46GB | 1.32GB | 0B |
| `local.(*Client).EvaluateV2` | 4.27GB | 4.26GB | 3.83GB | 0B |
| `local.topologicalSort` | 595.38MB | 594.87MB | 533.50MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.14GB | 4.13GB | 3.76GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 555.77MB | 555.26MB | 456.66MB | 0B |
| `localEvaluation.getMapOfValue` | 4.14GB | 4.13GB | 3.76GB | 0B |
| `utils.ParseFeatureFlag` | 4.14GB | 4.14GB | 3.77GB | 0B |

**Total FF alloc (current snapshot):** 22.09GB  |  **24h avg:** 19.95GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.75MB | 39/2327 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.79MB | 65/2327 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1978/2327 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 31.65MB | 88/2327 | `█████░░░░░░░░░░ 36%` |
| 5 | `runtime.mallocgc` | 23.06MB | 1978/2327 | `████░░░░░░░░░░░ 26%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2327 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 15.5MB | 1456/2327 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2327 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2327 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.Client` | 10.66MB | 64/2327 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2327 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2327 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2327 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2327 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2327 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2327 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 27.19GB | 844/2327 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2327 | `███░░░░░░░░░░░░ 21%` |
| 9 | `segmentio/kafka-go.makePartitions` | 20.74GB | 1701/2327 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `reflect.growslice` | 18.75GB | 1539/2327 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.2x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.8x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.6x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.0x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.8x avg)
