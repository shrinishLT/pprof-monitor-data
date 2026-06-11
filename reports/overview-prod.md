# Overview: prod
*Last updated: 2026-06-11 22:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T22:00 (3233 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,188 | avg: 14,294 | max: 84,644 | trend: INCREASING (+3.64/hr))
```
▂▃▂▁▁▁▂▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▂▃▂▁▁▂▅▇▆▅▄▇▂▃▃▄▁▁▁▂▅▇▆▆▇▆▁▁▁▂▁▁▁▁▁▁▁▁▆▆█▆▄▂▁▁▁▃▅
```

**Heap InUse** (current: 431.3MB | avg: 235.6MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▃▄▃▂▁▄▁▂▃▂▂▁▁▃▁▃▁▃▂▃▂▂▄▂▃▂▁▁▁▆▃▂▂▂▁▂▂▂▄▃▂▄▄▄▄▄▂▃▃▁▂▃▄▇▆▅▄▆▃▄▃▄▂▁▂▂▄▅▆▇█▆▁▂▂▂▂▁▁▁▁▁▁▂▅▆▆▆▆▂▃▁▁▄▆
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,188 | 16,008 | +2180 | 14,294 | 84,644 | INCREASING (+3.64/hr) |
| Heap InUse | 431.3MB | 335.7MB | +95.6MB | 235.6MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3329.2MB | 3328.8MB | +0.4MB | 2654.1MB | 6883.9MB | |
| Heap Objects | 2,155,375 | 1,614,289 | +541086 | 1,012,968 | 17,165,538 | |

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
| 2026-06-11 | 265 | 16,180 | 308.0MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 31.76MB |
| 4 | `bufio.NewWriterSize` | 10.05MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 8.55MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.56GB |
| 2 | `segmentio/kafka-go.makePartitions` | 176.58GB |
| 3 | `jackskj/carta.getUniqueId` | 162.15GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 143.44GB |
| 5 | `reflect.unsafe_New` | 142.83GB |
| 6 | `fmt.Sprintf` | 131.66GB |
| 7 | `fmt.(*buffer).writeString` | 112.36GB |
| 8 | `carta/value.NewCell` | 102.01GB |
| 9 | `reflect.unsafe_NewArray` | 90.09GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.80GB | 9.79GB | 9.57GB | 0B |
| `evaluation.mergeMetadata` | 5.12GB | 5.11GB | 5.00GB | 0B |
| `local.(*Client).EvaluateV2` | 14.92GB | 14.90GB | 14.56GB | 0B |
| `local.topologicalSort` | 2.07GB | 2.06GB | 2.02GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 14.22GB | 14.20GB | 13.89GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.07GB | 2.06GB | 2.01GB | 0B |
| `localEvaluation.getMapOfValue` | 14.22GB | 14.20GB | 13.89GB | 0B |
| `utils.ParseFeatureFlag` | 14.24GB | 14.22GB | 13.91GB | 0B |

**Total FF alloc (current snapshot):** 76.64GB  |  **24h avg:** 74.84GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.8MB | 60/3233 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.04MB | 88/3233 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2884/3233 | `█████████░░░░░░ 62%` |
| 4 | `runtime.mallocgc` | 31.67MB | 2884/3233 | `████████░░░░░░░ 53%` |
| 5 | `database/sql.convertAssignRows` | 27.04MB | 107/3233 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3233 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.6MB | 2258/3233 | `███░░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3233 | `███░░░░░░░░░░░░ 24%` |
| 9 | `net/http.(*Transport).dialConn` | 13.99MB | 72/3233 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3233 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3233 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3233 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3233 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 66.05GB | 1750/3233 | `███████░░░░░░░░ 52%` |
| 5 | `reflect.growslice` | 57.18GB | 2445/3233 | `██████░░░░░░░░░ 45%` |
| 6 | `segmentio/kafka-go.makePartitions` | 56.81GB | 2607/3233 | `██████░░░░░░░░░ 45%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3233 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 50.42GB | 2461/3233 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 48.96GB | 2225/3233 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 43.91GB | 1972/3233 | `█████░░░░░░░░░░ 35%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
