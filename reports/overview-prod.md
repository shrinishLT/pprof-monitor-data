# Overview: prod
*Last updated: 2026-06-09 09:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T09:51 (2512 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,631 | avg: 13,673 | max: 84,644 | trend: INCREASING (+4.04/hr))
```
▅▃▃▂▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁▁▃▂▁▃▂▁▁▃▃▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂
```

**Heap InUse** (current: 255.8MB | avg: 213.6MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▆▃▃▄▃▃▂▂▂▂▃▁█▆▃▁▂▁▂▁▂▁▂▂▆▅▁▂▁▂▂▂▄▃▃▅▃▂▁▄▅▂▂▃▃▂▁▁▁▃▃▁▃▂▂▃▂▂▁▂▂▂▁▂▃▁▁▁▂▃▂▂▂▁▂▃▁▁▂▁▁▂▁▂▁▃▂▃▂▂▂▁▃▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,631 | 15,245 | +386 | 13,673 | 84,644 | INCREASING (+4.04/hr) |
| Heap InUse | 255.8MB | 243.2MB | +12.6MB | 213.6MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3342.4MB | 3343.8MB | -1.4MB | 2460.7MB | 6883.9MB | |
| Heap Objects | 805,640 | 810,682 | -5042 | 940,646 | 17,165,538 | |

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
| 2026-06-09 | 119 | 15,112 | 270.4MB | 527.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 5.76MB |
| 6 | `bufio.NewWriterSize` | 5.05MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 93.74GB |
| 2 | `reflect.growslice` | 88.86GB |
| 3 | `jackskj/carta.getUniqueId` | 78.41GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 77.77GB |
| 5 | `reflect.unsafe_New` | 69.67GB |
| 6 | `fmt.Sprintf` | 59.64GB |
| 7 | `fmt.(*buffer).writeString` | 57.12GB |
| 8 | `carta/value.NewCell` | 49.76GB |
| 9 | `reflect.unsafe_NewArray` | 47.98GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 41.2GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.08GB | 4.07GB | 3.97GB | 0B |
| `evaluation.mergeMetadata` | 2.13GB | 2.12GB | 2.07GB | 0B |
| `local.(*Client).EvaluateV2` | 6.19GB | 6.18GB | 6.03GB | 0B |
| `local.topologicalSort` | 873.95MB | 873.43MB | 852.93MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.00GB | 5.99GB | 5.83GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 788.21MB | 788.21MB | 777.40MB | 0B |
| `localEvaluation.getMapOfValue` | 6.00GB | 5.99GB | 5.83GB | 0B |
| `utils.ParseFeatureFlag` | 6.02GB | 6.00GB | 5.84GB | 0B |

**Total FF alloc (current snapshot):** 32.05GB  |  **24h avg:** 31.16GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 83.74MB | 40/2512 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 63.86MB | 66/2512 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2163/2512 | `██████░░░░░░░░░ 43%` |
| 4 | `database/sql.convertAssignRows` | 31.02MB | 90/2512 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 25.4MB | 2163/2512 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2512 | `███░░░░░░░░░░░░ 21%` |
| 7 | `bytes.growSlice` | 14.88MB | 1617/2512 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 14.36MB | 47/2512 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2512 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2512 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2512 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2512 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2512 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2512 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2512 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 34.33GB | 1029/2512 | `████░░░░░░░░░░░ 27%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2512 | `███░░░░░░░░░░░░ 22%` |
| 8 | `segmentio/kafka-go.makePartitions` | 26.87GB | 1886/2512 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2512 | `███░░░░░░░░░░░░ 21%` |
| 10 | `reflect.growslice` | 24.65GB | 1724/2512 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.7x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.5x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.9x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.7x avg)
