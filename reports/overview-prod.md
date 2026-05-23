# Overview: prod
*Last updated: 2026-05-23 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T06:00 (387 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,870 | avg: 15,815 | max: 84,644 | trend: INCREASING (+5.85/hr))
```
▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 359.1MB | avg: 239.9MB | max: 1896.6MB | trend: stable (+0.15MB/hr))
```
▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,870 | 15,319 | -449 | 15,815 | 84,644 | INCREASING (+5.85/hr) |
| Heap InUse | 359.1MB | 155.9MB | +203.2MB | 239.9MB | 1896.6MB | stable (+0.15MB/hr) |
| Heap Sys | 4212.6MB | 4212.6MB | +0.0MB | 4226.4MB | 6579.6MB | |
| Heap Objects | 1,394,719 | 465,773 | +928946 | 998,569 | 8,100,802 | |

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
| 2026-05-23 | 13 | 15,232 | 206.8MB | 359.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 44.53MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `database/sql.convertAssignRows` | 29.0MB |
| 4 | `runtime.mallocgc` | 9.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.05MB |
| 8 | `bytes.growSlice` | 4.02MB |
| 9 | `bufio.NewWriterSize` | 3.51MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 47.94GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 28.58GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 28.48GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 26.99GB |
| 5 | `experiment/local.topologicalSort` | 19.06GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.03GB |
| 7 | `reflect.growslice` | 11.01GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 10.3GB |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 9.21GB |
| 10 | `jackskj/carta.getUniqueId` | 8.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/387 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.79MB | 16/387 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 385/387 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 20/387 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.34MB | 385/387 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 14.06MB | 277/387 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/387 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/387 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/387 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.54MB | 62/387 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.72GB | 376/387 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.32GB | 382/387 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.3GB | 382/387 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.82GB | 364/387 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.66GB | 363/387 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.22GB | 332/387 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.55GB | 305/387 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.52GB | 320/387 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/387 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/387 | `██░░░░░░░░░░░░░ 14%` |

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
