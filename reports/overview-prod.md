# Overview: prod
*Last updated: 2026-05-21 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T06:00 (269 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,109 | avg: 15,706 | max: 84,644 | trend: INCREASING (+10.31/hr))
```
▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 489.9MB | avg: 238.2MB | max: 1896.6MB | trend: stable (+0.38MB/hr))
```
▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,109 | 15,217 | +1892 | 15,706 | 84,644 | INCREASING (+10.31/hr) |
| Heap InUse | 489.9MB | 256.8MB | +233.1MB | 238.2MB | 1896.6MB | stable (+0.38MB/hr) |
| Heap Sys | 2045.6MB | 1033.2MB | +1012.4MB | 4270.0MB | 6579.6MB | |
| Heap Objects | 2,888,452 | 1,302,009 | +1586443 | 1,007,764 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 13 | 15,806 | 292.2MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 82.42MB |
| 2 | `database/sql.convertAssignRows` | 44.0MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 29.09MB |
| 5 | `bytes.growSlice` | 20.6MB |
| 6 | `bufio.NewReaderSize` | 12.05MB |
| 7 | `runtime.mallocgc` | 11.51MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.05MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `bufio.NewWriterSize` | 8.56MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 91.19GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 55.25GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 54.76GB |
| 4 | `experiment/local.topologicalSort` | 36.73GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.08GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 17.52GB |
| 7 | `reflect.growslice` | 10.92GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 8.8GB |
| 9 | `jackskj/carta.getUniqueId` | 8.59GB |
| 10 | `reflect.unsafe_New` | 7.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/269 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/269 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 267/269 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/269 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.23MB | 267/269 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.89MB | 182/269 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/269 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/269 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.88MB | 40/269 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/269 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.46GB | 258/269 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.03GB | 264/269 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.98GB | 264/269 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 58.36GB | 247/269 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.27GB | 246/269 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.82GB | 214/269 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.19GB | 190/269 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.73GB | 223/269 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/269 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.13GB | 112/269 | `██░░░░░░░░░░░░░ 15%` |

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
