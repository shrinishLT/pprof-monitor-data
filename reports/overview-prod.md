# Overview: prod
*Last updated: 2026-05-23 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T04:31 (384 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 15,823 | max: 84,644 | trend: INCREASING (+6.24/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 116.5MB | avg: 240.0MB | max: 1896.6MB | trend: stable (+0.15MB/hr))
```
▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 1%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,276 | -200 | 15,823 | 84,644 | INCREASING (+6.24/hr) |
| Heap InUse | 116.5MB | 165.9MB | -49.4MB | 240.0MB | 1896.6MB | stable (+0.15MB/hr) |
| Heap Sys | 4217.1MB | 1410.8MB | +2806.3MB | 4226.5MB | 6579.6MB | |
| Heap Objects | 525,363 | 944,765 | -419402 | 998,885 | 8,100,802 | |

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
| 2026-05-23 | 10 | 15,357 | 200.2MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 4 | `compress/flate.NewWriter` | 5.29MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `aws/endpoints.init` | 3.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.6GB |
| 2 | `internal/evaluation.mergeMetadata` | 4.31GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.67GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 2.6GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.57GB |
| 6 | `experiment/local.topologicalSort` | 1.71GB |
| 7 | `segmentio/kafka-go.makePartitions` | 1.49GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.32GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.21GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.14GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/384 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/384 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 382/384 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/384 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.45MB | 382/384 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 14.13MB | 275/384 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/384 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/384 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/384 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.41MB | 61/384 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.51GB | 373/384 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.79GB | 379/384 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.77GB | 379/384 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 52.16GB | 361/384 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.94GB | 360/384 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.54GB | 329/384 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.69GB | 303/384 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.63GB | 318/384 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/384 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/384 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
