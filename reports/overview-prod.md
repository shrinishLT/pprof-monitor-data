# Overview: prod
*Last updated: 2026-05-22 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T03:31 (333 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,096 | avg: 15,782 | max: 84,644 | trend: INCREASING (+7.86/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

**Heap InUse** (current: 177.0MB | avg: 242.6MB | max: 1896.6MB | trend: stable (+0.35MB/hr))
```
▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,096 | 14,124 | -28 | 15,782 | 84,644 | INCREASING (+7.86/hr) |
| Heap InUse | 177.0MB | 165.4MB | +11.6MB | 242.6MB | 1896.6MB | stable (+0.35MB/hr) |
| Heap Sys | 4873.2MB | 4873.2MB | +0.0MB | 4291.6MB | 6579.6MB | |
| Heap Objects | 754,599 | 559,443 | +195156 | 1,013,379 | 8,100,802 | |

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
| 2026-05-22 | 9 | 15,893 | 259.3MB | 432.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 315.3GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 188.94GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 188.63GB |
| 4 | `experiment/local.topologicalSort` | 125.05GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 98.59GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.83GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 59.92GB |
| 8 | `fmt.Sprintf` | 32.83GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 28.15GB |
| 10 | `segmentio/kafka-go.makePartitions` | 23.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/333 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/333 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 331/333 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/333 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.39MB | 331/333 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.02MB | 237/333 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/333 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/333 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/333 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/333 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 124.03GB | 322/333 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 73.63GB | 328/333 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 73.63GB | 328/333 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.69GB | 309/333 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 50.98GB | 310/333 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.14GB | 278/333 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.51GB | 254/333 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.63GB | 272/333 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/333 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.36GB | 157/333 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
