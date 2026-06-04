# Overview: prod
*Last updated: 2026-06-04 21:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T21:55 (1218 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,229 | avg: 11,410 | max: 84,644 | trend: decreasing (-9.95/hr))
```
▂▂▄▃▃▂▁▂▃▅▆▄▄▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁
```

**Heap InUse** (current: 225.6MB | avg: 173.4MB | max: 2823.8MB | trend: stable (-0.11MB/hr))
```
▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,229 | 19,948 | -4719 | 11,410 | 84,644 | decreasing (-9.95/hr) |
| Heap InUse | 225.6MB | 410.0MB | -184.4MB | 173.4MB | 2823.8MB | stable (-0.11MB/hr) |
| Heap Sys | 3845.0MB | 3841.3MB | +3.7MB | 2660.3MB | 6883.9MB | |
| Heap Objects | 769,133 | 1,881,817 | -1112684 | 749,612 | 14,090,816 | |

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
| 2026-06-04 | 264 | 16,693 | 269.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.01MB |
| 3 | `bytes.growSlice` | 10.2MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewWriterSize` | 6.53MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 4.54MB |
| 8 | `compress/flate.NewWriter` | 4.41MB |
| 9 | `bufio.NewReaderSize` | 4.04MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.15GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.13GB |
| 3 | `fmt.Sprintf` | 7.31GB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.65GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.03GB |
| 6 | `database/sql.convertAssignRows` | 4.45GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.24GB |
| 8 | `strconv.appendQuotedWith` | 3.65GB |
| 9 | `jackskj/carta.getUniqueId` | 3.65GB |
| 10 | `fmt.Sprint` | 3.54GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 572.88MB | 566.79MB | 356.04MB | 0B |
| `evaluation.mergeMetadata` | 295.57MB | 293.07MB | 183.68MB | 0B |
| `local.(*Client).EvaluateV2` | 893.24MB | 885.14MB | 558.29MB | 0B |
| `local.topologicalSort` | 120.90MB | 119.39MB | 78.69MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 783.37MB | 776.78MB | 494.51MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 188.28MB | 186.76MB | 114.86MB | 0B |
| `localEvaluation.getMapOfValue` | 783.37MB | 776.78MB | 494.51MB | 0B |
| `utils.ParseFeatureFlag` | 783.87MB | 777.28MB | 494.64MB | 0B |

**Total FF alloc (current snapshot):** 4.32GB  |  **24h avg:** 2.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1218 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1218 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 869/1218 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1218 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.37MB | 869/1218 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1218 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.37MB | 655/1218 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1218 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1218 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1218 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1218 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1218 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1218 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1218 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1218 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.08GB | 841/1218 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1218 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.12GB | 764/1218 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.14GB | 460/1218 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.23GB | 602/1218 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
