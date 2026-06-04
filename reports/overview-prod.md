# Overview: prod
*Last updated: 2026-06-04 16:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T16:20 (1151 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,875 | avg: 11,140 | max: 84,644 | trend: decreasing (-14.77/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 268.3MB | avg: 169.4MB | max: 2823.8MB | trend: stable (-0.18MB/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂▂▂▁▂▂▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,875 | 14,408 | +2467 | 11,140 | 84,644 | decreasing (-14.77/hr) |
| Heap InUse | 268.3MB | 164.0MB | +104.3MB | 169.4MB | 2823.8MB | stable (-0.18MB/hr) |
| Heap Sys | 4150.6MB | 4153.0MB | -2.4MB | 2652.7MB | 6883.9MB | |
| Heap Objects | 1,154,304 | 638,196 | +516108 | 730,261 | 14,090,816 | |

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
| 2026-06-04 | 197 | 16,913 | 279.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.36MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 6 | `bufio.NewReaderSize` | 7.53MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 8 | `bufio.NewWriterSize` | 4.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.02MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 21.9GB |
| 2 | `fmt.Sprintf` | 9.48GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 8.67GB |
| 4 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.79GB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.59GB |
| 6 | `reflect.growslice` | 6.35GB |
| 7 | `jackskj/carta.getUniqueId` | 6.25GB |
| 8 | `reflect.unsafe_New` | 5.29GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.79GB |
| 10 | `fmt.Sprint` | 4.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 613.95MB | 597.78MB | 358.04MB | 0B |
| `evaluation.mergeMetadata` | 315.58MB | 307.58MB | 186.94MB | 0B |
| `local.(*Client).EvaluateV2` | 950.87MB | 925.88MB | 546.62MB | 0B |
| `local.topologicalSort` | 134.62MB | 130.57MB | 76.34MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 883.47MB | 861.52MB | 509.20MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 146.75MB | 143.20MB | 86.41MB | 0B |
| `localEvaluation.getMapOfValue` | 883.47MB | 861.52MB | 509.20MB | 0B |
| `utils.ParseFeatureFlag` | 883.47MB | 861.52MB | 509.20MB | 0B |

**Total FF alloc (current snapshot):** 4.70GB  |  **24h avg:** 2.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1151 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1151 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 802/1151 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1151 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.05MB | 802/1151 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1151 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.49MB | 589/1151 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1151 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1151 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1151 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1151 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1151 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1151 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1151 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1151 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.55GB | 775/1151 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1151 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.38GB | 699/1151 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.38GB | 394/1151 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.04GB | 536/1151 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
