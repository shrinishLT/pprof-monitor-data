# Overview: prod
*Last updated: 2026-05-21 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T16:00 (301 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,768 | avg: 15,729 | max: 84,644 | trend: INCREASING (+8.35/hr))
```
▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
```

**Heap InUse** (current: 224.2MB | avg: 238.6MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,768 | 19,780 | -5012 | 15,729 | 84,644 | INCREASING (+8.35/hr) |
| Heap InUse | 224.2MB | 470.2MB | -246.0MB | 238.6MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 4878.9MB | 4877.8MB | +1.1MB | 4229.0MB | 6579.6MB | |
| Heap Objects | 852,394 | 2,159,377 | -1306983 | 1,005,874 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 45 | 15,888 | 256.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bufio.NewReaderSize` | 4.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.51MB |
| 8 | `bytes.growSlice` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 116.45GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.85GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.7GB |
| 4 | `experiment/local.topologicalSort` | 46.2GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.56GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 22.18GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 21.0GB |
| 8 | `fmt.Sprintf` | 11.65GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 9.62GB |
| 10 | `internal/evaluation.coerceString` | 7.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/301 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/301 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 299/301 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/301 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.32MB | 299/301 | `██████░░░░░░░░░ 41%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/301 | `███░░░░░░░░░░░░ 23%` |
| 7 | `bytes.growSlice` | 13.67MB | 210/301 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/301 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.82MB | 44/301 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/301 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 113.29GB | 290/301 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 67.26GB | 296/301 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 67.24GB | 296/301 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 54.51GB | 277/301 | `███████░░░░░░░░ 48%` |
| 5 | `experiment/local.topologicalSort` | 46.75GB | 278/301 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.87GB | 246/301 | `█████░░░░░░░░░░ 36%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 26.68GB | 242/301 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 26.55GB | 222/301 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/301 | `███░░░░░░░░░░░░ 21%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.89GB | 145/301 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
