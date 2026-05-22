# Overview: prod
*Last updated: 2026-05-22 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T19:32 (366 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,386 | avg: 15,813 | max: 84,644 | trend: INCREASING (+6.90/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 194.0MB | avg: 241.6MB | max: 1896.6MB | trend: stable (+0.23MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,386 | 15,742 | -356 | 15,813 | 84,644 | INCREASING (+6.90/hr) |
| Heap InUse | 194.0MB | 168.6MB | +25.4MB | 241.6MB | 1896.6MB | stable (+0.23MB/hr) |
| Heap Sys | 2285.2MB | 2288.4MB | -3.2MB | 4298.4MB | 6579.6MB | |
| Heap Objects | 941,509 | 366,057 | +575452 | 1,008,809 | 8,100,802 | |

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
| 2026-05-22 | 42 | 16,077 | 237.8MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 9.08MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `bytes.growSlice` | 7.04MB |
| 6 | `bufio.NewWriterSize` | 5.02MB |
| 7 | `bufio.NewReaderSize` | 4.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 8.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 5.41GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 5.39GB |
| 4 | `experiment/local.topologicalSort` | 3.52GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 3.36GB |
| 6 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.87GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.61GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 1.73GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 1.27GB |
| 10 | `fmt.Sprintf` | 1.06GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/366 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/366 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 364/366 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/366 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.1MB | 364/366 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.01MB | 263/366 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/366 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/366 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/366 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.51MB | 56/366 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 132.42GB | 355/366 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 78.65GB | 361/366 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 78.62GB | 361/366 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.26GB | 343/366 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 52.96GB | 342/366 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.56GB | 311/366 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.92GB | 287/366 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.74GB | 301/366 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/366 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.31GB | 186/366 | `██░░░░░░░░░░░░░ 14%` |

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
