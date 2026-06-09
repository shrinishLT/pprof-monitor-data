# Overview: prod
*Last updated: 2026-06-09 23:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-09T23:15 (2673 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 23,030 | avg: 13,871 | max: 84,644 | trend: INCREASING (+4.17/hr))
```
▂▁▂▃▂▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▃▂▁▁▇▃▁▅▃▂▁▅▄▁▃▂▁█
```

**Heap InUse** (current: 574.7MB | avg: 220.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▃▂▂▅▃▂▂▂▂▁▁▁▃▂▁▂▁▂▁▁▁▂▂▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▁▁▁▃▄▄▂▂▂▇▃▁▅▄▂▁▆▅▁▃▄▁█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 27%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 23,030 | 14,237 | +8793 | 13,871 | 84,644 | INCREASING (+4.17/hr) |
| Heap InUse | 574.7MB | 244.3MB | +330.4MB | 220.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3316.8MB | 3332.2MB | -15.4MB | 2512.8MB | 6883.9MB | |
| Heap Objects | 2,595,073 | 1,243,623 | +1351450 | 964,006 | 17,165,538 | |

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
| 2026-06-09 | 280 | 16,174 | 305.6MB | 1487.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `bytes.growSlice` | 50.26MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewWriterSize` | 26.13MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 22.6MB |
| 6 | `bufio.NewReaderSize` | 21.6MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 5.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 112.12GB |
| 2 | `reflect.growslice` | 105.1GB |
| 3 | `jackskj/carta.getUniqueId` | 94.06GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.25GB |
| 5 | `reflect.unsafe_New` | 83.31GB |
| 6 | `fmt.Sprintf` | 75.3GB |
| 7 | `fmt.(*buffer).writeString` | 67.44GB |
| 8 | `carta/value.NewCell` | 59.41GB |
| 9 | `reflect.unsafe_NewArray` | 57.31GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.14GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.59GB | 5.58GB | 5.40GB | 0B |
| `evaluation.mergeMetadata` | 2.94GB | 2.93GB | 2.84GB | 0B |
| `local.(*Client).EvaluateV2` | 8.53GB | 8.52GB | 8.24GB | 0B |
| `local.topologicalSort` | 1.19GB | 1.18GB | 1.15GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.12GB | 8.11GB | 7.84GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.19GB | 1.19GB | 1.15GB | 0B |
| `localEvaluation.getMapOfValue` | 8.12GB | 8.11GB | 7.84GB | 0B |
| `utils.ParseFeatureFlag` | 8.14GB | 8.12GB | 7.86GB | 0B |

**Total FF alloc (current snapshot):** 43.82GB  |  **24h avg:** 42.32GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2673 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 60.51MB | 71/2673 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2324/2673 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2673 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.14MB | 2324/2673 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2673 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.35MB | 1770/2673 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2673 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2673 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `crypto/tls.Client` | 10.64MB | 73/2673 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2673 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2673 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2673 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2673 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2673 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 41.78GB | 1190/2673 | `█████░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 32.86GB | 2047/2673 | `███░░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 31.31GB | 1885/2673 | `███░░░░░░░░░░░░ 25%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2673 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 27.07GB | 1901/2673 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
