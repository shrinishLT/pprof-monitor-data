# Overview: prod
*Last updated: 2026-06-04 20:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T20:40 (1203 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,891 | avg: 11,344 | max: 84,644 | trend: decreasing (-10.99/hr))
```
█▇▇▇▄▂▂▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▂▂▂▂▃▄▄▃▂▂▃
```

**Heap InUse** (current: 271.0MB | avg: 172.3MB | max: 2823.8MB | trend: stable (-0.13MB/hr))
```
▅▅▅▄▅▃▃▂▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,891 | 15,465 | +1426 | 11,344 | 84,644 | decreasing (-10.99/hr) |
| Heap InUse | 271.0MB | 259.8MB | +11.2MB | 172.3MB | 2823.8MB | stable (-0.13MB/hr) |
| Heap Sys | 3852.0MB | 3853.7MB | -1.7MB | 2645.5MB | 6883.9MB | |
| Heap Objects | 1,339,726 | 1,235,263 | +104463 | 745,409 | 14,090,816 | |

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
| 2026-06-04 | 249 | 16,692 | 270.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 21.26MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.04MB |
| 6 | `bufio.NewReaderSize` | 7.05MB |
| 7 | `bufio.NewWriterSize` | 7.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 4.01MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.2GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 9.11GB |
| 3 | `fmt.Sprintf` | 5.11GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.96GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 3.62GB |
| 6 | `database/sql.convertAssignRows` | 3.46GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.22GB |
| 8 | `jackskj/carta.getUniqueId` | 3.07GB |
| 9 | `reflect.unsafe_NewArray` | 2.55GB |
| 10 | `strconv.appendQuotedWith` | 2.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 431.19MB | 424.58MB | 242.32MB | 0B |
| `evaluation.mergeMetadata` | 219.55MB | 216.55MB | 126.35MB | 0B |
| `local.(*Client).EvaluateV2` | 673.23MB | 664.56MB | 377.56MB | 0B |
| `local.topologicalSort` | 91.05MB | 90.55MB | 54.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 599.52MB | 590.34MB | 339.01MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 134.74MB | 134.22MB | 74.45MB | 0B |
| `localEvaluation.getMapOfValue` | 599.52MB | 590.34MB | 339.01MB | 0B |
| `utils.ParseFeatureFlag` | 599.52MB | 590.34MB | 339.01MB | 0B |

**Total FF alloc (current snapshot):** 3.27GB  |  **24h avg:** 1.85GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1203 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1203 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 854/1203 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1203 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.5MB | 854/1203 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1203 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.31MB | 640/1203 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1203 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1203 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1203 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1203 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1203 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1203 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1203 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1203 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.52GB | 826/1203 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1203 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.36GB | 749/1203 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.32GB | 445/1203 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.34GB | 587/1203 | `█░░░░░░░░░░░░░░ 8%` |

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
