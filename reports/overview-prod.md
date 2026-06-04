# Overview: prod
*Last updated: 2026-06-04 15:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T15:05 (1136 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,685 | avg: 11,070 | max: 84,644 | trend: decreasing (-16.11/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 364.6MB | avg: 167.9MB | max: 2823.8MB | trend: stable (-0.20MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,685 | 18,267 | +418 | 11,070 | 84,644 | decreasing (-16.11/hr) |
| Heap InUse | 364.6MB | 354.4MB | +10.2MB | 167.9MB | 2823.8MB | stable (-0.20MB/hr) |
| Heap Sys | 3413.7MB | 3413.6MB | +0.1MB | 2632.9MB | 6883.9MB | |
| Heap Objects | 1,844,112 | 1,752,405 | +91707 | 723,725 | 14,090,816 | |

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
| 2026-06-04 | 182 | 16,951 | 279.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 30.15MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 8.03MB |
| 7 | `bufio.NewReaderSize` | 7.53MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 9 | `crypto/tls.Client` | 4.5MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 14.15GB |
| 2 | `fmt.Sprintf` | 7.25GB |
| 3 | `reflect.growslice` | 5.96GB |
| 4 | `jackskj/carta.getUniqueId` | 5.71GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 5.61GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.97GB |
| 7 | `segmentio/kafka-go.makePartitions` | 4.89GB |
| 8 | `reflect.unsafe_New` | 4.88GB |
| 9 | `fmt.Sprint` | 3.53GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.5GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 450.56MB | 438.95MB | 233.57MB | 0B |
| `evaluation.mergeMetadata` | 229.56MB | 224.06MB | 123.62MB | 0B |
| `local.(*Client).EvaluateV2` | 693.07MB | 672.74MB | 352.63MB | 0B |
| `local.topologicalSort` | 98.65MB | 94.10MB | 48.54MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 648.15MB | 629.33MB | 333.49MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 107.85MB | 105.82MB | 51.54MB | 0B |
| `localEvaluation.getMapOfValue` | 648.15MB | 629.33MB | 333.49MB | 0B |
| `utils.ParseFeatureFlag` | 648.15MB | 629.33MB | 333.57MB | 0B |

**Total FF alloc (current snapshot):** 3.44GB  |  **24h avg:** 1.77GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1136 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1136 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 787/1136 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1136 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.21MB | 787/1136 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1136 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.43MB | 574/1136 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1136 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1136 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.45MB | 372/1136 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1136 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1136 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1136 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1136 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1136 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.93GB | 760/1136 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1136 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.6GB | 684/1136 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.52GB | 379/1136 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.19GB | 521/1136 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
