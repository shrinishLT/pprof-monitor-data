# Overview: prod
*Last updated: 2026-06-12 16:07 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T16:06 (3450 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,786 | avg: 14,439 | max: 84,644 | trend: INCREASING (+3.47/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▆▆█▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 214.0MB | avg: 239.2MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▂▂▂▃▄▄▃▄▇▅█▇▆▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,786 | 15,287 | +499 | 14,439 | 84,644 | INCREASING (+3.47/hr) |
| Heap InUse | 214.0MB | 186.5MB | +27.5MB | 239.2MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 692.9MB | 692.5MB | +0.4MB | 2654.3MB | 6883.9MB | |
| Heap Objects | 731,336 | 643,664 | +87672 | 1,026,392 | 17,165,538 | |

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
| 2026-06-12 | 194 | 16,343 | 282.7MB | 1418.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.47MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 5 | `runtime.mallocgc` | 8.01MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `bufio.NewReaderSize` | 3.51MB |
| 8 | `bufio.NewWriterSize` | 3.01MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.66GB |
| 2 | `fmt.Sprintf` | 4.97GB |
| 3 | `jackskj/carta.getUniqueId` | 4.64GB |
| 4 | `reflect.growslice` | 4.62GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.89GB |
| 6 | `reflect.unsafe_New` | 3.87GB |
| 7 | `reflect.unsafe_NewArray` | 2.94GB |
| 8 | `carta/value.NewCell` | 2.72GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.6GB |
| 10 | `fmt.(*buffer).writeString` | 2.56GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 399.47MB | 391.33MB | 204.31MB | 0B |
| `evaluation.mergeMetadata` | 205.05MB | 201.05MB | 109.21MB | 0B |
| `local.(*Client).EvaluateV2` | 622.31MB | 608.99MB | 310.98MB | 0B |
| `local.topologicalSort` | 92.61MB | 91.09MB | 44.17MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 579.93MB | 566.59MB | 287.98MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 90.56MB | 88.51MB | 46.42MB | 0B |
| `localEvaluation.getMapOfValue` | 579.93MB | 566.59MB | 287.98MB | 0B |
| `utils.ParseFeatureFlag` | 582.44MB | 569.09MB | 288.80MB | 0B |

**Total FF alloc (current snapshot):** 3.08GB  |  **24h avg:** 1.54GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 53.31MB | 67/3450 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.12MB | 94/3450 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3101/3450 | `██████████░░░░░ 68%` |
| 4 | `runtime.mallocgc` | 32.28MB | 3101/3450 | `█████████░░░░░░ 60%` |
| 5 | `database/sql.convertAssignRows` | 25.26MB | 116/3450 | `███████░░░░░░░░ 47%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3450 | `█████░░░░░░░░░░ 33%` |
| 7 | `bytes.growSlice` | 15.79MB | 2443/3450 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3450 | `███░░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*Transport).dialConn` | 14.04MB | 81/3450 | `███░░░░░░░░░░░░ 26%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3450 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3450 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3450 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3450 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.99GB | 1922/3450 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 64.27GB | 2662/3450 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.44GB | 2824/3450 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.94GB | 2678/3450 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 54.86GB | 2442/3450 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3450 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.69GB | 2181/3450 | `█████░░░░░░░░░░ 38%` |

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
