# Overview: prod
*Last updated: 2026-05-20 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T16:00 (241 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,522 | avg: 15,500 | max: 84,644 | trend: INCREASING (+3.11/hr))
```
▁▁▁▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 345.2MB | avg: 230.5MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▂▂▂▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,522 | 14,726 | +2796 | 15,500 | 84,644 | INCREASING (+3.11/hr) |
| Heap InUse | 345.2MB | 170.0MB | +175.2MB | 230.5MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 1360.0MB | 1359.3MB | +0.7MB | 4333.5MB | 6579.6MB | |
| Heap Objects | 1,641,990 | 640,404 | +1001586 | 977,648 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 33 | 16,172 | 230.3MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 18.09MB |
| 3 | `bufio.NewWriterSize` | 14.07MB |
| 4 | `runtime.mallocgc` | 13.1MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.05MB |
| 6 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB |
| 7 | `bufio.NewReaderSize` | 9.55MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 42.5GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 25.81GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 25.73GB |
| 4 | `experiment/local.topologicalSort` | 16.89GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 13.37GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 9.65GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 8.14GB |
| 8 | `fmt.Sprintf` | 4.75GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.39GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 4.32GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/241 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/241 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 239/241 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/241 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.32MB | 239/241 | `█████░░░░░░░░░░ 39%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 16.18MB | 3/241 | `███░░░░░░░░░░░░ 26%` |
| 7 | `bytes.growSlice` | 12.67MB | 154/241 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/241 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.05MB | 30/241 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/241 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.46GB | 230/241 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.26GB | 236/241 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.19GB | 236/241 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 62.12GB | 228/241 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 50.18GB | 218/241 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.3GB | 186/241 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.13GB | 163/241 | `███░░░░░░░░░░░░ 25%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.45GB | 216/241 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/241 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.67GB | 88/241 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
