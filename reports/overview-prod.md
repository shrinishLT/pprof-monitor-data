# Overview: prod
*Last updated: 2026-06-06 14:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T14:05 (1699 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,111 | avg: 12,783 | max: 84,644 | trend: INCREASING (+3.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▇█▇▄▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 177.9MB | avg: 194.8MB | max: 3154.1MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄▆▇█▄▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,111 | 14,689 | +422 | 12,783 | 84,644 | INCREASING (+3.44/hr) |
| Heap InUse | 177.9MB | 136.8MB | +41.1MB | 194.8MB | 3154.1MB | stable (+0.07MB/hr) |
| Heap Sys | 864.8MB | 867.2MB | -2.4MB | 2423.0MB | 6883.9MB | |
| Heap Objects | 486,898 | 421,781 | +65117 | 862,551 | 17,165,538 | |

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
| 2026-06-06 | 170 | 16,920 | 269.7MB | 1932.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.08MB |
| 3 | `bytes.growSlice` | 10.05MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 6.02MB |
| 7 | `compress/flate.NewWriter` | 5.29MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 4.28MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 1.4GB |
| 2 | `jackskj/carta.getUniqueId` | 1.19GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.11GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 1.09GB |
| 5 | `reflect.unsafe_New` | 1.04GB |
| 6 | `fmt.(*buffer).writeString` | 929.54MB |
| 7 | `carta/value.NewCell` | 728.56MB |
| 8 | `reflect.unsafe_NewArray` | 592.34MB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 479.95MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 346.01MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 45.58MB | 40.55MB | 1.30GB | 0B |
| `evaluation.mergeMetadata` | 23.01MB | 21.00MB | 685.86MB | 0B |
| `local.(*Client).EvaluateV2` | 64.29MB | 56.66MB | 1.98GB | 0B |
| `local.topologicalSort` | 7.61MB | 6.59MB | 283.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 65.81MB | 58.22MB | 1.92GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 4.12MB | 3.06MB | 249.64MB | 0B |
| `localEvaluation.getMapOfValue` | 65.81MB | 58.22MB | 1.92GB | 0B |
| `utils.ParseFeatureFlag` | 65.81MB | 58.22MB | 1.92GB | 0B |

**Total FF alloc (current snapshot):** 342.03MB  |  **24h avg:** 10.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1699 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 71.33MB | 57/1699 | `███████████░░░░ 78%` |
| 3 | `database/sql.convertAssignRows` | 38.68MB | 69/1699 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1350/1699 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1699 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.46MB | 1350/1699 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.49MB | 1053/1699 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1699 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1699 | `██░░░░░░░░░░░░░ 13%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1699 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1699 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1699 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1699 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1699 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1699 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.65GB | 1113/1699 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1699 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.7GB | 936/1699 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1699 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `fmt.Sprintf` | 12.8GB | 873/1699 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
