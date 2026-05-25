# Overview: prod
*Last updated: 2026-05-25 12:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T12:02 (495 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,519 | avg: 15,585 | max: 84,644 | trend: decreasing (-1.47/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁▁▁▁
```

**Heap InUse** (current: 259.3MB | avg: 227.3MB | max: 1896.6MB | trend: stable (-0.16MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▂▇▃▃▃▂▄▁▁▁▂▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▅▂▄▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,519 | 15,557 | -1038 | 15,585 | 84,644 | decreasing (-1.47/hr) |
| Heap InUse | 259.3MB | 244.8MB | +14.5MB | 227.3MB | 1896.6MB | stable (-0.16MB/hr) |
| Heap Sys | 4831.4MB | 4829.6MB | +1.8MB | 4151.2MB | 6883.9MB | |
| Heap Objects | 1,149,831 | 655,309 | +494522 | 981,144 | 8,100,802 | |

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
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 25 | 15,131 | 195.2MB | 478.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 58.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.48GB |
| 2 | `reflect.growslice` | 23.5GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 22.28GB |
| 4 | `jackskj/carta.getUniqueId` | 19.77GB |
| 5 | `reflect.unsafe_New` | 18.06GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 15.32GB |
| 7 | `fmt.(*buffer).writeString` | 13.18GB |
| 8 | `carta/value.NewCell` | 13.16GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.33GB |
| 10 | `segmentio/kafka-go.makePartitions` | 10.23GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 47.44MB | 20/495 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 47.14MB | 13/495 | `██████████████░ 99%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 493/495 | `███████████░░░░ 77%` |
| 4 | `database/sql.convertAssignRows` | 29.69MB | 24/495 | `█████████░░░░░░ 62%` |
| 5 | `runtime.mallocgc` | 21.76MB | 493/495 | `██████░░░░░░░░░ 45%` |
| 6 | `bytes.growSlice` | 13.42MB | 322/495 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/495 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/495 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/495 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/495 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/495 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/495 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/495 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/495 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.96GB | 470/495 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/495 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/495 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 23.34GB | 427/495 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `fmt.Sprintf` | 18.14GB | 201/495 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `segmentio/kafka-go.makePartitions` | 15.35GB | 295/495 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
