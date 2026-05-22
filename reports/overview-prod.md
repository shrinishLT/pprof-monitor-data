# Overview: prod
*Last updated: 2026-05-22 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T15:00 (357 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,270 | avg: 15,813 | max: 84,644 | trend: INCREASING (+7.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 250.6MB | avg: 242.3MB | max: 1896.6MB | trend: stable (+0.27MB/hr))
```
▄▂▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,270 | 15,296 | -26 | 15,813 | 84,644 | INCREASING (+7.41/hr) |
| Heap InUse | 250.6MB | 201.0MB | +49.6MB | 242.3MB | 1896.6MB | stable (+0.27MB/hr) |
| Heap Sys | 5061.9MB | 5062.5MB | -0.6MB | 4294.9MB | 6579.6MB | |
| Heap Objects | 1,267,963 | 977,616 | +290347 | 1,010,554 | 8,100,802 | |

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
| 2026-05-22 | 33 | 16,142 | 243.9MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 13.0MB |
| 3 | `runtime.mallocgc` | 9.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bytes.growSlice` | 6.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 5.3MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 9 | `bufio.NewReaderSize` | 4.02MB |
| 10 | `experiment/local.topologicalSort` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 84.11GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 50.55GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 50.34GB |
| 4 | `experiment/local.topologicalSort` | 33.62GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.24GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 21.25GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 16.04GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 8.06GB |
| 9 | `fmt.Sprintf` | 7.73GB |
| 10 | `reflect.growslice` | 6.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/357 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/357 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 355/357 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/357 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.47MB | 355/357 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.13MB | 254/357 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/357 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/357 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/357 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.63MB | 55/357 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 133.43GB | 346/357 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.22GB | 352/357 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.2GB | 352/357 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 54.72GB | 334/357 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 53.78GB | 333/357 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.08GB | 302/357 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.31GB | 278/357 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.27GB | 292/357 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/357 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 19.72GB | 178/357 | `██░░░░░░░░░░░░░ 14%` |

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
