# Overview: prod
*Last updated: 2026-06-05 13:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T13:20 (1403 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,187 | avg: 12,063 | max: 84,644 | trend: decreasing (-1.52/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▃▄▆▆█▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 240.4MB | avg: 185.0MB | max: 3154.1MB | trend: stable (+0.01MB/hr))
```
▁▁▁▁▁▁▁▂▂▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▅▄▄▅▆▆█▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,187 | 15,761 | +426 | 12,063 | 84,644 | decreasing (-1.52/hr) |
| Heap InUse | 240.4MB | 216.5MB | +23.9MB | 185.0MB | 3154.1MB | stable (+0.01MB/hr) |
| Heap Sys | 829.2MB | 829.8MB | -0.6MB | 2679.7MB | 6883.9MB | |
| Heap Objects | 962,528 | 951,861 | +10667 | 822,146 | 17,165,538 | |

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
| 2026-06-05 | 161 | 16,560 | 267.5MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 18.1MB |
| 3 | `runtime.mallocgc` | 10.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 7 | `bufio.NewReaderSize` | 4.03MB |
| 8 | `bufio.NewWriterSize` | 3.51MB |
| 9 | `compress/flate.NewWriter` | 2.64MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 4.9GB |
| 2 | `jackskj/carta.getUniqueId` | 4.34GB |
| 3 | `reflect.unsafe_New` | 3.87GB |
| 4 | `fmt.(*buffer).writeString` | 3.17GB |
| 5 | `carta/value.NewCell` | 2.81GB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.72GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.5GB |
| 8 | `fmt.Sprintf` | 2.26GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 1.83GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 1.51GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 163.76MB | 152.04MB | 162.88MB | 0B |
| `evaluation.mergeMetadata` | 79.02MB | 75.02MB | 81.90MB | 0B |
| `local.(*Client).EvaluateV2` | 259.83MB | 242.99MB | 247.71MB | 0B |
| `local.topologicalSort` | 38.88MB | 36.86MB | 33.38MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 247.22MB | 232.43MB | 255.64MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 35.28MB | 32.71MB | 17.64MB | 0B |
| `localEvaluation.getMapOfValue` | 247.22MB | 232.43MB | 255.64MB | 0B |
| `utils.ParseFeatureFlag` | 247.22MB | 232.43MB | 255.64MB | 0B |

**Total FF alloc (current snapshot):** 1.29GB  |  **24h avg:** 1.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1403 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1403 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.77MB | 64/1403 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1054/1403 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1403 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.92MB | 1054/1403 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.35MB | 813/1403 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1403 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.06MB | 24/1403 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1403 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1403 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1403 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1403 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1403 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1403 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 32.99GB | 1025/1403 | `███░░░░░░░░░░░░ 26%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1403 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1403 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1403 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.22GB | 587/1403 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.3x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
