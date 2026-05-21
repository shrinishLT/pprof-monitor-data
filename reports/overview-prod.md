# Overview: prod
*Last updated: 2026-05-22 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T02:00 (330 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,018 | avg: 15,796 | max: 84,644 | trend: INCREASING (+8.59/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 432.8MB | avg: 243.0MB | max: 1896.6MB | trend: stable (+0.37MB/hr))
```
▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▁▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▁▁▂▂▂▃▃▂▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,018 | 15,043 | +4975 | 15,796 | 84,644 | INCREASING (+8.59/hr) |
| Heap InUse | 432.8MB | 257.5MB | +175.3MB | 243.0MB | 1896.6MB | stable (+0.37MB/hr) |
| Heap Sys | 4875.3MB | 4876.2MB | -0.9MB | 4286.3MB | 6579.6MB | |
| Heap Objects | 1,663,407 | 1,240,165 | +423242 | 1,014,951 | 8,100,802 | |

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
| 2026-05-22 | 6 | 16,711 | 289.7MB | 432.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 44.73MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `runtime.mallocgc` | 35.36MB |
| 4 | `internal/evaluation.mergeMetadata` | 29.51MB |
| 5 | `bufio.NewReaderSize` | 16.06MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 15.76MB |
| 7 | `bufio.NewWriterSize` | 13.58MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 9 | `internal/evaluation.(*Engine).Evaluate` | 10.68MB |
| 10 | `experiment/local.topologicalSort` | 9.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 292.37GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 175.17GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 174.93GB |
| 4 | `experiment/local.topologicalSort` | 115.9GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 91.34GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 55.57GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 52.86GB |
| 8 | `fmt.Sprintf` | 30.79GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 24.42GB |
| 10 | `segmentio/kafka-go.makePartitions` | 21.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/330 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/330 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 328/330 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/330 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 25.3MB | 328/330 | `██████░░░░░░░░░ 43%` |
| 6 | `bytes.growSlice` | 14.02MB | 237/330 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/330 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/330 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.93MB | 48/330 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/330 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 122.24GB | 319/330 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 72.58GB | 325/330 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 72.57GB | 325/330 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.64GB | 306/330 | `██████░░░░░░░░░ 43%` |
| 5 | `experiment/local.topologicalSort` | 50.26GB | 307/330 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.55GB | 275/330 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.14GB | 251/330 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.62GB | 269/330 | `███░░░░░░░░░░░░ 20%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/330 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.08GB | 154/330 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
