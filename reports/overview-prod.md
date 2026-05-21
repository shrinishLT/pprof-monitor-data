# Overview: prod
*Last updated: 2026-05-21 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T07:00 (272 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,216 | avg: 15,698 | max: 84,644 | trend: INCREASING (+9.61/hr))
```
▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 136.2MB | avg: 237.7MB | max: 1896.6MB | trend: stable (+0.34MB/hr))
```
▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,216 | 15,088 | -872 | 15,698 | 84,644 | INCREASING (+9.61/hr) |
| Heap InUse | 136.2MB | 219.1MB | -82.9MB | 237.7MB | 1896.6MB | stable (+0.34MB/hr) |
| Heap Sys | 3204.9MB | 2044.5MB | +1160.4MB | 4249.7MB | 6579.6MB | |
| Heap Objects | 592,250 | 1,172,190 | -579940 | 1,006,713 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 16 | 15,646 | 272.7MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `kafka-go/protocol.newPage` | 1.6MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 100.43GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 60.83GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 60.38GB |
| 4 | `experiment/local.topologicalSort` | 40.38GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 33.76GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.94GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 19.26GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.74GB |
| 9 | `reflect.growslice` | 11.0GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 8.8GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/272 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/272 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 270/272 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/272 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.09MB | 270/272 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.85MB | 184/272 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/272 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/272 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.88MB | 40/272 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/272 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.27GB | 261/272 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.93GB | 267/272 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.88GB | 267/272 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 58.02GB | 250/272 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.17GB | 249/272 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.67GB | 217/272 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.05GB | 193/272 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.55GB | 226/272 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/272 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.13GB | 112/272 | `██░░░░░░░░░░░░░ 15%` |

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
