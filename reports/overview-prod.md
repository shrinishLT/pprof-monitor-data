# Overview: prod
*Last updated: 2026-06-04 20:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T20:15 (1198 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,896 | avg: 11,321 | max: 84,644 | trend: decreasing (-11.36/hr))
```
▁▁▁▃▅█▇▇▇▄▂▂▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▂▂▂▂▃▄
```

**Heap InUse** (current: 289.7MB | avg: 171.8MB | max: 2823.8MB | trend: stable (-0.14MB/hr))
```
▁▁▁▃▃▅▅▅▄▅▃▃▂▁▂▃▄▄▁▂▂▂▃▂▃▂▂█▂▄▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,896 | 17,204 | +692 | 11,321 | 84,644 | decreasing (-11.36/hr) |
| Heap InUse | 289.7MB | 345.5MB | -55.8MB | 171.8MB | 2823.8MB | stable (-0.14MB/hr) |
| Heap Sys | 3853.9MB | 3858.9MB | -5.0MB | 2640.4MB | 6883.9MB | |
| Heap Objects | 1,000,736 | 1,763,896 | -763160 | 743,274 | 14,090,816 | |

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
| 2026-06-04 | 244 | 16,689 | 269.9MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.29MB |
| 3 | `bufio.NewReaderSize` | 12.58MB |
| 4 | `runtime.mallocgc` | 11.51MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 9.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 10.26GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 9.11GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.41GB |
| 4 | `fmt.Sprintf` | 3.74GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 3.62GB |
| 6 | `database/sql.convertAssignRows` | 3.2GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.92GB |
| 8 | `reflect.unsafe_NewArray` | 2.26GB |
| 9 | `jackskj/carta.getUniqueId` | 2.09GB |
| 10 | `fmt.Sprint` | 1.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 386.99MB | 378.95MB | 265.74MB | 0B |
| `evaluation.mergeMetadata` | 197.55MB | 192.55MB | 138.50MB | 0B |
| `local.(*Client).EvaluateV2` | 602.49MB | 589.79MB | 413.17MB | 0B |
| `local.topologicalSort` | 83.49MB | 81.98MB | 60.20MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 533.51MB | 520.78MB | 374.47MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 123.33MB | 121.31MB | 76.90MB | 0B |
| `localEvaluation.getMapOfValue` | 533.51MB | 520.78MB | 374.47MB | 0B |
| `utils.ParseFeatureFlag` | 533.51MB | 520.78MB | 374.47MB | 0B |

**Total FF alloc (current snapshot):** 2.92GB  |  **24h avg:** 2.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1198 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1198 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 849/1198 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1198 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.55MB | 849/1198 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1198 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.28MB | 635/1198 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1198 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1198 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1198 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1198 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1198 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1198 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1198 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1198 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.69GB | 821/1198 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1198 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.45GB | 744/1198 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.39GB | 440/1198 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.39GB | 582/1198 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
