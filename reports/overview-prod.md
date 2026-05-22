# Overview: prod
*Last updated: 2026-05-23 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T05:00 (385 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,254 | avg: 15,819 | max: 84,644 | trend: INCREASING (+6.06/hr))
```
▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.0MB | avg: 239.8MB | max: 1896.6MB | trend: stable (+0.15MB/hr))
```
▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,254 | 14,076 | +178 | 15,819 | 84,644 | INCREASING (+6.06/hr) |
| Heap InUse | 172.0MB | 116.5MB | +55.5MB | 239.8MB | 1896.6MB | stable (+0.15MB/hr) |
| Heap Sys | 4216.6MB | 4217.1MB | -0.5MB | 4226.5MB | 6579.6MB | |
| Heap Objects | 1,014,124 | 525,363 | +488761 | 998,924 | 8,100,802 | |

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
| 2026-05-23 | 11 | 15,256 | 197.6MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `reflect.growslice` | 11.43MB |
| 3 | `runtime.mallocgc` | 9.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `reflect.unsafe_New` | 4.5MB |
| 7 | `aws/endpoints.init` | 3.01MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.64GB |
| 2 | `internal/evaluation.mergeMetadata` | 4.7GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 3.7GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 2.84GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.81GB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.09GB |
| 7 | `experiment/local.topologicalSort` | 1.86GB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.46GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.22GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.14GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/385 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/385 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 383/385 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/385 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.41MB | 383/385 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 14.13MB | 275/385 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/385 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/385 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/385 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.41MB | 61/385 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 127.18GB | 374/385 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.6GB | 380/385 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.57GB | 380/385 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 52.02GB | 362/385 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.82GB | 361/385 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.41GB | 330/385 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.69GB | 303/385 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.57GB | 319/385 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/385 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/385 | `██░░░░░░░░░░░░░ 14%` |

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
