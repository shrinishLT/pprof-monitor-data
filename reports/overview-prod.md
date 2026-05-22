# Overview: prod
*Last updated: 2026-05-23 04:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T04:02 (383 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,276 | avg: 15,828 | max: 84,644 | trend: INCREASING (+6.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 165.9MB | avg: 240.3MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,276 | 14,302 | -26 | 15,828 | 84,644 | INCREASING (+6.43/hr) |
| Heap InUse | 165.9MB | 176.7MB | -10.8MB | 240.3MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 1410.8MB | 1420.2MB | -9.4MB | 4226.6MB | 6579.6MB | |
| Heap Objects | 944,765 | 1,036,837 | -92072 | 1,000,121 | 8,100,802 | |

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
| 2026-05-23 | 9 | 15,499 | 209.5MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `aws/endpoints.init` | 3.01MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 2.01MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 3.63GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 3.39GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 2.17GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 2.16GB |
| 5 | `experiment/local.topologicalSort` | 1.44GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.3GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.13GB |
| 8 | `segmentio/kafka-go.makePartitions` | 978.19MB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 701.61MB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 701.04MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/383 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/383 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 381/383 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/383 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.49MB | 381/383 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 14.13MB | 275/383 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/383 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/383 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/383 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.41MB | 61/383 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.84GB | 372/383 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.98GB | 378/383 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.96GB | 378/383 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 52.3GB | 360/383 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.05GB | 359/383 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.67GB | 328/383 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.69GB | 303/383 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.7GB | 317/383 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/383 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/383 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
