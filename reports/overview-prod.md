# Overview: prod
*Last updated: 2026-06-04 22:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T22:55 (1230 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,760 | avg: 11,444 | max: 84,644 | trend: decreasing (-9.33/hr))
```
▄▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁▂▂▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 637.8MB | avg: 174.0MB | max: 2823.8MB | trend: stable (-0.10MB/hr))
```
▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂▁▂▂▁▁▂▁▁█
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,760 | 14,509 | +251 | 11,444 | 84,644 | decreasing (-9.33/hr) |
| Heap InUse | 637.8MB | 200.7MB | +437.1MB | 174.0MB | 2823.8MB | stable (-0.10MB/hr) |
| Heap Sys | 773.8MB | 3847.1MB | -3073.3MB | 2669.4MB | 6883.9MB | |
| Heap Objects | 4,243,165 | 1,205,461 | +3037704 | 754,499 | 14,090,816 | |

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
| 2026-06-04 | 276 | 16,615 | 268.5MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 84.64MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.48MB |
| 3 | `database/sql.convertAssignRows` | 53.5MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `runtime.mallocgc` | 6.51MB |
| 7 | `dotlapse-event-service/project.FilterProjectsByTags` | 6.11MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 6.0MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 4.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 533.0MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 293.79MB |
| 3 | `database/sql.convertAssignRows` | 88.0MB |
| 4 | `go-sql-driver/mysql.(*binaryRows).readRow` | 85.5MB |
| 5 | `segmentio/kafka-go.makePartitions` | 40.23MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 37.63MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 36.14MB |
| 8 | `go-sql-driver/mysql.parseBinaryDateTime` | 18.5MB |
| 9 | `reflect.unsafe_NewArray` | 18.11MB |
| 10 | `fmt.Sprintf` | 17.53MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.54MB | 638.29MB | 448.98MB | 0B |
| `evaluation.mergeMetadata` | 4.00MB | 330.58MB | 230.85MB | 0B |
| `local.(*Client).EvaluateV2` | 10.64MB | 994.44MB | 702.56MB | 0B |
| `local.topologicalSort` | 3.02MB | 136.07MB | 97.06MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.59MB | 876.88MB | 620.24MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.04MB | 205.15MB | 145.43MB | 0B |
| `localEvaluation.getMapOfValue` | 8.59MB | 876.88MB | 620.24MB | 0B |
| `utils.ParseFeatureFlag` | 8.59MB | 877.38MB | 620.48MB | 0B |

**Total FF alloc (current snapshot):** 51.03MB  |  **24h avg:** 3.40GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 65.38MB | 41/1230 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.62MB | 25/1230 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 881/1230 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.49MB | 53/1230 | `███████░░░░░░░░ 48%` |
| 5 | `runtime.mallocgc` | 19.26MB | 881/1230 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1230 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.26MB | 665/1230 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1230 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1230 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1230 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1230 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1230 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1230 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1230 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1230 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.74GB | 853/1230 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1230 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 16.94GB | 776/1230 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.04GB | 472/1230 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.16GB | 614/1230 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 439.8MB at 2026-05-19T17:02 (2.5x avg)
