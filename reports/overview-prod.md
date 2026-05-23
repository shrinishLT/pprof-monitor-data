# Overview: prod
*Last updated: 2026-05-23 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T12:30 (400 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,701 | avg: 15,793 | max: 84,644 | trend: INCREASING (+4.65/hr))
```
▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 130.8MB | avg: 238.1MB | max: 1896.6MB | trend: stable (+0.08MB/hr))
```
▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,701 | 14,134 | +567 | 15,793 | 84,644 | INCREASING (+4.65/hr) |
| Heap InUse | 130.8MB | 122.8MB | +8.0MB | 238.1MB | 1896.6MB | stable (+0.08MB/hr) |
| Heap Sys | 992.5MB | 232.1MB | +760.4MB | 4222.0MB | 6883.9MB | |
| Heap Objects | 388,511 | 608,868 | -220357 | 990,638 | 8,100,802 | |

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
| 2026-05-23 | 26 | 15,176 | 195.2MB | 359.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 5 | `bufio.NewReaderSize` | 3.03MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `bytes.growSlice` | 2.54MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.9GB |
| 2 | `segmentio/kafka-go.makePartitions` | 1.01GB |
| 3 | `reflect.growslice` | 973.75MB |
| 4 | `jackskj/carta.getUniqueId` | 949.67MB |
| 5 | `reflect.unsafe_New` | 852.88MB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 724.75MB |
| 7 | `carta/value.NewCell` | 563.54MB |
| 8 | `reflect.unsafe_NewArray` | 541.7MB |
| 9 | `fmt.(*buffer).writeString` | 523.9MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 364.51MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/400 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.79MB | 16/400 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 398/400 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 20/400 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.19MB | 398/400 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.9MB | 286/400 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/400 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/400 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/400 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/400 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/400 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/400 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/400 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/400 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.0GB | 375/400 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/400 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/400 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.48GB | 332/400 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 21.49GB | 18/400 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `fmt.Sprintf` | 18.4GB | 198/400 | `██░░░░░░░░░░░░░ 14%` |

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
