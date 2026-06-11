# Overview: prod
*Last updated: 2026-06-11 15:56 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T15:55 (3160 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,611 | avg: 14,254 | max: 84,644 | trend: INCREASING (+3.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▃▄▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 273.4MB | avg: 233.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▃▃▅▇▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,611 | 15,563 | +48 | 14,254 | 84,644 | INCREASING (+3.74/hr) |
| Heap InUse | 273.4MB | 260.9MB | +12.5MB | 233.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.9MB | 3343.4MB | +0.5MB | 2638.3MB | 6883.9MB | |
| Heap Objects | 655,756 | 528,459 | +127297 | 1,007,217 | 17,165,538 | |

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
| 2026-06-11 | 192 | 16,238 | 304.9MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 12.06MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `bufio.NewWriterSize` | 4.56MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 177.52GB |
| 2 | `segmentio/kafka-go.makePartitions` | 168.17GB |
| 3 | `jackskj/carta.getUniqueId` | 160.74GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.51GB |
| 5 | `reflect.unsafe_New` | 141.68GB |
| 6 | `fmt.Sprintf` | 123.7GB |
| 7 | `fmt.(*buffer).writeString` | 111.76GB |
| 8 | `carta/value.NewCell` | 101.25GB |
| 9 | `reflect.unsafe_NewArray` | 85.88GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 80.94GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.03GB | 9.03GB | 8.79GB | 0B |
| `evaluation.mergeMetadata` | 4.72GB | 4.72GB | 4.59GB | 0B |
| `local.(*Client).EvaluateV2` | 13.75GB | 13.75GB | 13.39GB | 0B |
| `local.topologicalSort` | 1.91GB | 1.91GB | 1.86GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.15GB | 13.14GB | 12.80GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.87GB | 1.87GB | 1.81GB | 0B |
| `localEvaluation.getMapOfValue` | 13.15GB | 13.14GB | 12.80GB | 0B |
| `utils.ParseFeatureFlag` | 13.16GB | 13.16GB | 12.82GB | 0B |

**Total FF alloc (current snapshot):** 70.74GB  |  **24h avg:** 68.86GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3160 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 51.07MB | 86/3160 | `████████████░░░ 85%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2811/3160 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 31.18MB | 2811/3160 | `███████░░░░░░░░ 52%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3160 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3160 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.62MB | 2186/3160 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3160 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3160 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3160 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3160 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3160 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3160 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 62.71GB | 1677/3160 | `███████░░░░░░░░ 50%` |
| 5 | `segmentio/kafka-go.makePartitions` | 53.48GB | 2534/3160 | `██████░░░░░░░░░ 42%` |
| 6 | `reflect.growslice` | 53.46GB | 2372/3160 | `██████░░░░░░░░░ 42%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3160 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 47.02GB | 2388/3160 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.unsafe_New` | 45.8GB | 2152/3160 | `█████░░░░░░░░░░ 36%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3160 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
