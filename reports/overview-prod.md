# Overview: prod
*Last updated: 2026-06-04 12:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T12:35 (1106 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,193 | avg: 10,891 | max: 84,644 | trend: decreasing (-19.45/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 285.5MB | avg: 163.6MB | max: 2823.8MB | trend: stable (-0.27MB/hr))
```
▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,193 | 14,916 | +2277 | 10,891 | 84,644 | decreasing (-19.45/hr) |
| Heap InUse | 285.5MB | 166.0MB | +119.5MB | 163.6MB | 2823.8MB | stable (-0.27MB/hr) |
| Heap Sys | 1173.7MB | 1181.1MB | -7.4MB | 2631.9MB | 6883.9MB | |
| Heap Objects | 1,488,999 | 625,398 | +863601 | 704,005 | 14,090,816 | |

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
| 2026-06-04 | 152 | 16,810 | 269.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 20.61MB |
| 3 | `runtime.mallocgc` | 9.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 9.04MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.53MB |
| 7 | `bufio.NewWriterSize` | 6.53MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 5.0MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 10 | `reflect.growslice` | 4.48MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.17GB |
| 2 | `reflect.growslice` | 1.97GB |
| 3 | `jackskj/carta.getUniqueId` | 1.78GB |
| 4 | `reflect.unsafe_New` | 1.51GB |
| 5 | `segmentio/kafka-go.makePartitions` | 1.49GB |
| 6 | `fmt.(*buffer).writeString` | 1.11GB |
| 7 | `carta/value.NewCell` | 1.07GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 899.02MB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 795.69MB |
| 10 | `reflect.unsafe_NewArray` | 779.58MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 130.48MB | 119.74MB | 224.15MB | 0B |
| `evaluation.mergeMetadata` | 71.52MB | 65.52MB | 116.21MB | 0B |
| `local.(*Client).EvaluateV2` | 183.11MB | 167.17MB | 342.48MB | 0B |
| `local.topologicalSort` | 22.74MB | 20.71MB | 48.35MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 167.34MB | 154.46MB | 342.64MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 30.15MB | 26.05MB | 32.52MB | 0B |
| `localEvaluation.getMapOfValue` | 167.34MB | 154.46MB | 342.64MB | 0B |
| `utils.ParseFeatureFlag` | 167.34MB | 154.46MB | 343.05MB | 0B |

**Total FF alloc (current snapshot):** 940.01MB  |  **24h avg:** 1.75GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1106 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1106 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 757/1106 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1106 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.58MB | 757/1106 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1106 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 14.97MB | 544/1106 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1106 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1106 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.47MB | 343/1106 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1106 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1106 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1106 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1106 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1106 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.23GB | 730/1106 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1106 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.09GB | 661/1106 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1106 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.68GB | 491/1106 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
