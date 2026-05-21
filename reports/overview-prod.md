# Overview: prod
*Last updated: 2026-05-21 15:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:02 (298 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,698 | avg: 15,705 | max: 84,644 | trend: INCREASING (+7.64/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 207.8MB | avg: 237.3MB | max: 1896.6MB | trend: stable (+0.25MB/hr))
```
▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,698 | 14,961 | -263 | 15,705 | 84,644 | INCREASING (+7.64/hr) |
| Heap InUse | 207.8MB | 214.7MB | -6.9MB | 237.3MB | 1896.6MB | stable (+0.25MB/hr) |
| Heap Sys | 4881.4MB | 4881.7MB | -0.3MB | 4222.5MB | 6579.6MB | |
| Heap Objects | 676,932 | 604,018 | +72914 | 1,000,034 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 42 | 15,730 | 248.3MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 5.59MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.03MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.54MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewReaderSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 98.75GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 59.19GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 59.19GB |
| 4 | `experiment/local.topologicalSort` | 39.22GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.06GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 19.55GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 18.84GB |
| 8 | `fmt.Sprintf` | 9.65GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 9.02GB |
| 10 | `reflect.growslice` | 7.36GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/298 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/298 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 296/298 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/298 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.21MB | 296/298 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/298 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/298 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.54MB | 207/298 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/298 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/298 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.3GB | 287/298 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.26GB | 293/298 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.24GB | 293/298 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 54.89GB | 274/298 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.77GB | 275/298 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.94GB | 243/298 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.9GB | 239/298 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.63GB | 219/298 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/298 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/298 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
