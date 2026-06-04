# Overview: prod
*Last updated: 2026-06-04 19:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:02 (1183 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,107 | avg: 11,265 | max: 84,644 | trend: decreasing (-12.38/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▃▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁
```

**Heap InUse** (current: 246.1MB | avg: 171.0MB | max: 2823.8MB | trend: stable (-0.15MB/hr))
```
▂▂▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▃▂▃▃▄▄▂▂▂▂▃▃▃▂▂█▂▄▄▃▄▄▅▄▃▂▃▄▂▂▂▂▃▃▂▁▃▃▃▃▅▄▄▁▂▃▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,107 | 14,888 | +219 | 11,265 | 84,644 | decreasing (-12.38/hr) |
| Heap InUse | 246.1MB | 190.2MB | +55.9MB | 171.0MB | 2823.8MB | stable (-0.15MB/hr) |
| Heap Sys | 3860.5MB | 960.6MB | +2899.9MB | 2625.0MB | 6883.9MB | |
| Heap Objects | 1,191,221 | 794,440 | +396781 | 738,608 | 14,090,816 | |

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
| 2026-06-04 | 229 | 16,749 | 272.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.14MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 5.04MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `bufio.NewWriterSize` | 4.52MB |
| 9 | `reflect.growslice` | 3.03MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 8.57GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.08GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.39GB |
| 4 | `segmentio/kafka-go.makePartitions` | 2.72GB |
| 5 | `fmt.Sprintf` | 2.15GB |
| 6 | `database/sql.convertAssignRows` | 2.07GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.0GB |
| 8 | `reflect.unsafe_NewArray` | 1.41GB |
| 9 | `jackskj/carta.getUniqueId` | 1.38GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.13GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 255.35MB | 242.70MB | 330.53MB | 0B |
| `evaluation.mergeMetadata` | 134.03MB | 126.53MB | 171.91MB | 0B |
| `local.(*Client).EvaluateV2` | 400.23MB | 379.39MB | 511.49MB | 0B |
| `local.topologicalSort` | 60.24MB | 55.68MB | 73.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 355.46MB | 337.11MB | 472.53MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 80.67MB | 76.62MB | 84.95MB | 0B |
| `localEvaluation.getMapOfValue` | 355.46MB | 337.11MB | 472.53MB | 0B |
| `utils.ParseFeatureFlag` | 355.46MB | 337.11MB | 472.53MB | 0B |

**Total FF alloc (current snapshot):** 1.95GB  |  **24h avg:** 2.53GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1183 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1183 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 834/1183 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.63MB | 51/1183 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.7MB | 834/1183 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1183 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.33MB | 620/1183 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1183 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1183 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1183 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1183 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1183 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1183 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1183 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1183 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.25GB | 806/1183 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1183 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.73GB | 729/1183 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.69GB | 425/1183 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.57GB | 567/1183 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
