# Overview: prod
*Last updated: 2026-06-05 00:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T00:10 (1245 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,675 | avg: 11,488 | max: 84,644 | trend: decreasing (-8.58/hr))
```
▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▂▂▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▄▂▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 208.0MB | avg: 174.3MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▁▂▃▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▂▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▂▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█▁▁▁▁▁▃▂▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,675 | 15,002 | -327 | 11,488 | 84,644 | decreasing (-8.58/hr) |
| Heap InUse | 208.0MB | 195.8MB | +12.2MB | 174.3MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 799.4MB | 799.2MB | +0.2MB | 2646.9MB | 6883.9MB | |
| Heap Objects | 1,047,195 | 830,134 | +217061 | 757,935 | 14,090,816 | |

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
| 2026-06-05 | 3 | 14,643 | 195.2MB | 208.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `bufio.NewReaderSize` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.01MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 3.78GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.55GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 1.53GB |
| 4 | `fmt.Sprintf` | 1.13GB |
| 5 | `jackskj/carta.getUniqueId` | 1.05GB |
| 6 | `reflect.growslice` | 893.42MB |
| 7 | `reflect.unsafe_NewArray` | 810.86MB |
| 8 | `reflect.unsafe_New` | 781.34MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 714.02MB |
| 10 | `fmt.(*buffer).writeString` | 592.34MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 112.95MB | 106.35MB | 370.72MB | 0B |
| `evaluation.mergeMetadata` | 61.02MB | 59.01MB | 191.52MB | 0B |
| `local.(*Client).EvaluateV2` | 154.81MB | 147.70MB | 576.57MB | 0B |
| `local.topologicalSort` | 20.70MB | 20.18MB | 78.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 141.54MB | 133.39MB | 508.21MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 24.55MB | 23.53MB | 118.85MB | 0B |
| `localEvaluation.getMapOfValue` | 141.54MB | 133.39MB | 508.21MB | 0B |
| `utils.ParseFeatureFlag` | 141.54MB | 133.39MB | 508.45MB | 0B |

**Total FF alloc (current snapshot):** 798.62MB  |  **24h avg:** 2.79GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1245 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1245 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 896/1245 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1245 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.1MB | 896/1245 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1245 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.11MB | 678/1245 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1245 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1245 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1245 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1245 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1245 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1245 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1245 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1245 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.12GB | 868/1245 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1245 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.64GB | 791/1245 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 10.81GB | 483/1245 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 9.94GB | 629/1245 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.8x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
