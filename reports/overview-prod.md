# Overview: prod
*Last updated: 2026-05-21 16:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T16:02 (302 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,755 | avg: 15,726 | max: 84,644 | trend: INCREASING (+8.14/hr))
```
▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁
```

**Heap InUse** (current: 183.0MB | avg: 238.4MB | max: 1896.6MB | trend: stable (+0.29MB/hr))
```
▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,755 | 14,768 | -13 | 15,726 | 84,644 | INCREASING (+8.14/hr) |
| Heap InUse | 183.0MB | 224.2MB | -41.2MB | 238.4MB | 1896.6MB | stable (+0.29MB/hr) |
| Heap Sys | 4879.4MB | 4878.9MB | +0.5MB | 4231.2MB | 6579.6MB | |
| Heap Objects | 456,849 | 852,394 | -395545 | 1,004,056 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 46 | 15,864 | 254.8MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bufio.NewReaderSize` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `bufio.NewWriterSize` | 2.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.01MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 116.67GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.98GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.82GB |
| 4 | `experiment/local.topologicalSort` | 46.28GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.63GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 22.22GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 21.0GB |
| 8 | `fmt.Sprintf` | 11.67GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 9.62GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/302 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/302 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 300/302 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/302 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.36MB | 300/302 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/302 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.61MB | 211/302 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/302 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/302 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/302 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.3GB | 291/302 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.27GB | 297/302 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.25GB | 297/302 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 54.39GB | 278/302 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.75GB | 279/302 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.85GB | 247/302 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.61GB | 243/302 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.53GB | 223/302 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/302 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.82GB | 146/302 | `██░░░░░░░░░░░░░ 15%` |

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
