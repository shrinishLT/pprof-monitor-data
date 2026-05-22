# Overview: prod
*Last updated: 2026-05-22 19:05 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T19:05 (365 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,742 | avg: 15,815 | max: 84,644 | trend: INCREASING (+6.99/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 168.6MB | avg: 241.8MB | max: 1896.6MB | trend: stable (+0.24MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,742 | 17,387 | -1645 | 15,815 | 84,644 | INCREASING (+6.99/hr) |
| Heap InUse | 168.6MB | 260.4MB | -91.8MB | 241.8MB | 1896.6MB | stable (+0.24MB/hr) |
| Heap Sys | 2288.4MB | 5053.6MB | -2765.2MB | 4304.0MB | 6579.6MB | |
| Heap Objects | 366,057 | 1,085,494 | -719437 | 1,008,993 | 8,100,802 | |

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
| 2026-05-22 | 41 | 16,093 | 238.8MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.05MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `runtime.mallocgc` | 9.08MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `bufio.NewWriterSize` | 4.02MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 5.4GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 3.36GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 3.32GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 3.29GB |
| 5 | `experiment/local.topologicalSort` | 2.12GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.63GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 1.52GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 1.27GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 1.06GB |
| 10 | `database/sql.convertAssignRows` | 700.56MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/365 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/365 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 363/365 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/365 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.14MB | 363/365 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.04MB | 262/365 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/365 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/365 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/365 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/365 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 132.77GB | 354/365 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 78.85GB | 360/365 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 78.83GB | 360/365 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.41GB | 342/365 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.11GB | 341/365 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.7GB | 310/365 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.02GB | 286/365 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.82GB | 300/365 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/365 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.41GB | 185/365 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
