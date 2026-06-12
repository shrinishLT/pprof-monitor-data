# Overview: prod
*Last updated: 2026-06-12 14:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T14:55 (3436 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,128 | avg: 14,434 | max: 84,644 | trend: INCREASING (+3.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 166.4MB | avg: 239.3MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,128 | 15,077 | +51 | 14,434 | 84,644 | INCREASING (+3.50/hr) |
| Heap InUse | 166.4MB | 186.1MB | -19.7MB | 239.3MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 615.1MB | 614.3MB | +0.8MB | 2662.5MB | 6883.9MB | |
| Heap Objects | 410,322 | 806,719 | -396397 | 1,027,036 | 17,165,538 | |

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
| 2026-06-12 | 180 | 16,383 | 287.6MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 8.01MB |
| 5 | `bytes.growSlice` | 4.6MB |
| 6 | `bufio.NewWriterSize` | 4.02MB |
| 7 | `bufio.NewReaderSize` | 4.02MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 4.17GB |
| 2 | `segmentio/kafka-go.makePartitions` | 4.07GB |
| 3 | `jackskj/carta.getUniqueId` | 3.99GB |
| 4 | `reflect.unsafe_New` | 3.4GB |
| 5 | `fmt.Sprintf` | 3.3GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.44GB |
| 7 | `carta/value.NewCell` | 2.4GB |
| 8 | `fmt.(*buffer).writeString` | 2.35GB |
| 9 | `reflect.unsafe_NewArray` | 2.1GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 274.61MB | 269.61MB | 2.56GB | 0B |
| `evaluation.mergeMetadata` | 145.54MB | 141.03MB | 1.33GB | 0B |
| `local.(*Client).EvaluateV2` | 421.54MB | 411.91MB | 3.89GB | 0B |
| `local.topologicalSort` | 58.71MB | 57.19MB | 555.65MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 392.96MB | 381.77MB | 3.72GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 61.40MB | 60.90MB | 540.51MB | 0B |
| `localEvaluation.getMapOfValue` | 392.96MB | 381.77MB | 3.72GB | 0B |
| `utils.ParseFeatureFlag` | 393.96MB | 382.77MB | 3.72GB | 0B |

**Total FF alloc (current snapshot):** 2.09GB  |  **24h avg:** 20.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3436 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.6MB | 93/3436 | `█████████████░░ 86%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3087/3436 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.39MB | 3087/3436 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.45MB | 115/3436 | `██████░░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3436 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.81MB | 2429/3436 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3436 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3436 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3436 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3436 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3436 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3436 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3436 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.59GB | 2648/3436 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.73GB | 2810/3436 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 57.21GB | 2664/3436 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 55.16GB | 2428/3436 | `██████░░░░░░░░░ 44%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3436 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.99GB | 2167/3436 | `█████░░░░░░░░░░ 39%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
