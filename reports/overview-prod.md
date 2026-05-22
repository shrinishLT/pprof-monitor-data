# Overview: prod
*Last updated: 2026-05-22 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T07:00 (341 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,439 | avg: 15,754 | max: 84,644 | trend: INCREASING (+6.34/hr))
```
▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 213.8MB | avg: 242.0MB | max: 1896.6MB | trend: stable (+0.30MB/hr))
```
▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,439 | 14,472 | -33 | 15,754 | 84,644 | INCREASING (+6.34/hr) |
| Heap InUse | 213.8MB | 185.5MB | +28.3MB | 242.0MB | 1896.6MB | stable (+0.30MB/hr) |
| Heap Sys | 5051.7MB | 5052.7MB | -1.0MB | 4307.3MB | 6579.6MB | |
| Heap Objects | 915,702 | 426,732 | +488970 | 1,012,885 | 8,100,802 | |

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
| 2026-05-22 | 17 | 15,264 | 239.8MB | 434.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `bytes.growSlice` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 368.41GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 220.95GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 220.54GB |
| 4 | `experiment/local.topologicalSort` | 146.23GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 115.24GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 112.6GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 70.05GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 48.84GB |
| 9 | `fmt.Sprintf` | 37.41GB |
| 10 | `segmentio/kafka-go.makePartitions` | 27.78GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/341 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/341 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 339/341 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/341 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.62MB | 339/341 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.96MB | 240/341 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/341 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/341 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/341 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/341 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 129.08GB | 330/341 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 76.62GB | 336/341 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 76.61GB | 336/341 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.33GB | 317/341 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 53.01GB | 318/341 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.81GB | 286/341 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.57GB | 262/341 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.9GB | 280/341 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/341 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.14GB | 165/341 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
