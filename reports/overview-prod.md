# Overview: prod
*Last updated: 2026-05-23 00:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T00:30 (376 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,363 | avg: 15,843 | max: 84,644 | trend: INCREASING (+7.29/hr))
```
▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁
```

**Heap InUse** (current: 197.3MB | avg: 241.3MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,363 | 20,073 | -5710 | 15,843 | 84,644 | INCREASING (+7.29/hr) |
| Heap InUse | 197.3MB | 349.0MB | -151.7MB | 241.3MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 4142.7MB | 2853.1MB | +1289.6MB | 4264.3MB | 6579.6MB | |
| Heap Objects | 792,392 | 960,730 | -168338 | 1,002,502 | 8,100,802 | |

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
| 2026-05-23 | 2 | 17,218 | 273.1MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 19.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 5 | `internal/evaluation.mergeMetadata` | 7.0MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 4.2MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 4.0MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 3.7MB |
| 9 | `reflect.mapassign_faststr0` | 3.0MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 67.19GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 40.44GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 40.23GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 28.48GB |
| 5 | `experiment/local.topologicalSort` | 26.65GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.04GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 12.95GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.82GB |
| 9 | `segmentio/kafka-go.makePartitions` | 7.74GB |
| 10 | `fmt.Sprintf` | 7.57GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/376 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/376 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 374/376 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/376 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.77MB | 374/376 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.24MB | 270/376 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/376 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/376 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/376 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.18MB | 60/376 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 129.86GB | 365/376 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.16GB | 371/376 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.14GB | 371/376 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 53.16GB | 353/376 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.91GB | 352/376 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.49GB | 321/376 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.17GB | 297/376 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.11GB | 311/376 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/376 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.8GB | 193/376 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.3x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
