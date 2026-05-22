# Overview: prod
*Last updated: 2026-05-23 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T01:30 (378 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,530 | avg: 15,837 | max: 84,644 | trend: INCREASING (+7.01/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁
```

**Heap InUse** (current: 206.7MB | avg: 241.0MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▁█▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,530 | 14,105 | +1425 | 15,837 | 84,644 | INCREASING (+7.01/hr) |
| Heap InUse | 206.7MB | 187.5MB | +19.2MB | 241.0MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 818.8MB | 4143.0MB | -3324.2MB | 4254.8MB | 6579.6MB | |
| Heap Objects | 651,331 | 1,054,038 | -402707 | 1,001,710 | 8,100,802 | |

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
| 2026-05-23 | 4 | 16,018 | 235.1MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `bytes.growSlice` | 7.54MB |
| 5 | `bufio.NewReaderSize` | 7.04MB |
| 6 | `runtime.mallocgc` | 7.01MB |
| 7 | `bufio.NewWriterSize` | 4.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `reflect.mapassign_faststr0` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.9GB |
| 2 | `internal/evaluation.mergeMetadata` | 1.53GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 931.27MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 923.89MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 735.77MB |
| 6 | `experiment/local.topologicalSort` | 605.94MB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 459.59MB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 276.02MB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 236.01MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 233.79MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/378 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/378 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 376/378 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/378 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.71MB | 376/378 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.22MB | 271/378 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/378 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/378 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/378 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.18MB | 60/378 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 129.35GB | 367/378 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 76.86GB | 373/378 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 76.84GB | 373/378 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 52.94GB | 355/378 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.7GB | 354/378 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.28GB | 323/378 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.02GB | 299/378 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.99GB | 313/378 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/378 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprintf` | 18.75GB | 194/378 | `██░░░░░░░░░░░░░ 14%` |

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
