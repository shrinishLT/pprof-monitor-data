# Overview: prod
*Last updated: 2026-06-04 20:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T20:05 (1196 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,026 | avg: 11,311 | max: 84,644 | trend: decreasing (-11.52/hr))
```
▁▁▁▁▁▃▅█▇▇▇▄▂▂▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▂▂▂▂
```

**Heap InUse** (current: 221.4MB | avg: 171.5MB | max: 2823.8MB | trend: stable (-0.14MB/hr))
```
▁▁▁▁▁▃▃▅▅▅▄▅▃▃▂▁▂▃▄▄▁▂▂▂▃▂▃▂▂█▂▄▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,026 | 15,466 | +560 | 11,311 | 84,644 | decreasing (-11.52/hr) |
| Heap InUse | 221.4MB | 196.6MB | +24.8MB | 171.5MB | 2823.8MB | stable (-0.14MB/hr) |
| Heap Sys | 3860.2MB | 3861.1MB | -0.9MB | 2638.4MB | 6883.9MB | |
| Heap Objects | 956,586 | 632,368 | +324218 | 742,206 | 14,090,816 | |

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
| 2026-06-04 | 242 | 16,682 | 269.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.84MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 6.55MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `bufio.NewWriterSize` | 5.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.53MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `crypto/tls.Client` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.88GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 9.07GB |
| 3 | `segmentio/kafka-go.makePartitions` | 4.18GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 3.6GB |
| 5 | `fmt.Sprintf` | 3.28GB |
| 6 | `database/sql.convertAssignRows` | 3.1GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.81GB |
| 8 | `reflect.unsafe_NewArray` | 2.15GB |
| 9 | `jackskj/carta.getUniqueId` | 1.75GB |
| 10 | `strconv.appendQuotedWith` | 1.65GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 368.29MB | 360.27MB | 274.60MB | 0B |
| `evaluation.mergeMetadata` | 188.55MB | 183.04MB | 143.15MB | 0B |
| `local.(*Client).EvaluateV2` | 571.81MB | 559.09MB | 426.76MB | 0B |
| `local.topologicalSort` | 79.95MB | 78.44MB | 62.16MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 504.35MB | 492.13MB | 388.27MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 118.72MB | 117.20MB | 77.76MB | 0B |
| `localEvaluation.getMapOfValue` | 504.35MB | 492.13MB | 388.27MB | 0B |
| `utils.ParseFeatureFlag` | 504.35MB | 492.13MB | 388.27MB | 0B |

**Total FF alloc (current snapshot):** 2.77GB  |  **24h avg:** 2.10GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1196 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1196 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 847/1196 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1196 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.57MB | 847/1196 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1196 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.24MB | 633/1196 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1196 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1196 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1196 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1196 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1196 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1196 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1196 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1196 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.77GB | 819/1196 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1196 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.49GB | 742/1196 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.43GB | 438/1196 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.41GB | 580/1196 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
