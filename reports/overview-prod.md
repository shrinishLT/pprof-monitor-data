# Overview: prod
*Last updated: 2026-05-21 11:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T11:02 (285 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,256 | avg: 15,711 | max: 84,644 | trend: INCREASING (+8.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁
```

**Heap InUse** (current: 253.7MB | avg: 235.9MB | max: 1896.6MB | trend: stable (+0.23MB/hr))
```
▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,256 | 17,845 | -589 | 15,711 | 84,644 | INCREASING (+8.98/hr) |
| Heap InUse | 253.7MB | 406.6MB | -152.9MB | 235.9MB | 1896.6MB | stable (+0.23MB/hr) |
| Heap Sys | 2804.8MB | 2798.5MB | +6.3MB | 4209.1MB | 6579.6MB | |
| Heap Objects | 901,289 | 1,533,432 | -632143 | 995,874 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 29 | 15,800 | 240.0MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `reflect.growslice` | 14.08MB |
| 4 | `bytes.growSlice` | 14.07MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 8 | `bufio.NewWriterSize` | 5.54MB |
| 9 | `bufio.NewReaderSize` | 5.02MB |
| 10 | `reflect.unsafe_New` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 13.13GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 7.82GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 7.78GB |
| 4 | `experiment/local.topologicalSort` | 5.2GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 4.21GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 2.49GB |
| 7 | `reflect.growslice` | 2.32GB |
| 8 | `jackskj/carta.getUniqueId` | 2.29GB |
| 9 | `reflect.unsafe_New` | 1.85GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 1.71GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/285 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/285 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 283/285 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/285 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.7MB | 283/285 | `██████░░░░░░░░░ 40%` |
| 6 | `bytes.growSlice` | 13.9MB | 194/285 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/285 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/285 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.87MB | 42/285 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/285 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.48GB | 274/285 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.51GB | 280/285 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.49GB | 280/285 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.09GB | 261/285 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 47.76GB | 262/285 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.05GB | 230/285 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.49GB | 206/285 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.05GB | 237/285 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/285 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/285 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
