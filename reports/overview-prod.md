# Overview: prod
*Last updated: 2026-05-22 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T06:00 (339 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,570 | avg: 15,761 | max: 84,644 | trend: INCREASING (+6.72/hr))
```
▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 434.2MB | avg: 242.3MB | max: 1896.6MB | trend: stable (+0.32MB/hr))
```
▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,570 | 14,132 | +2438 | 15,761 | 84,644 | INCREASING (+6.72/hr) |
| Heap InUse | 434.2MB | 173.7MB | +260.5MB | 242.3MB | 1896.6MB | stable (+0.32MB/hr) |
| Heap Sys | 5049.9MB | 5049.8MB | +0.1MB | 4302.9MB | 6579.6MB | |
| Heap Objects | 3,097,294 | 617,519 | +2479775 | 1,014,901 | 8,100,802 | |

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
| 2026-05-22 | 15 | 15,372 | 245.1MB | 434.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 50.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 35.36MB |
| 4 | `database/sql.convertAssignRows` | 23.0MB |
| 5 | `bytes.growSlice` | 20.61MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewWriterSize` | 8.53MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 9 | `reflect.growslice` | 6.43MB |
| 10 | `bufio.NewReaderSize` | 4.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 331.02GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 198.3GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 198.24GB |
| 4 | `experiment/local.topologicalSort` | 131.19GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 103.46GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 81.81GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 62.9GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 37.26GB |
| 9 | `fmt.Sprintf` | 34.32GB |
| 10 | `segmentio/kafka-go.makePartitions` | 26.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/339 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/339 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 337/339 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/339 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.57MB | 337/339 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.05MB | 238/339 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/339 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/339 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/339 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/339 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.63GB | 328/339 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.76GB | 334/339 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.75GB | 334/339 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.97GB | 315/339 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 52.42GB | 316/339 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.32GB | 284/339 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.26GB | 260/339 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.75GB | 278/339 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/339 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.91GB | 163/339 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
