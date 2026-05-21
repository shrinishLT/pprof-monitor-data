# Overview: prod
*Last updated: 2026-05-21 10:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T10:02 (282 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,983 | avg: 15,675 | max: 84,644 | trend: INCREASING (+7.72/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 351.6MB | avg: 235.1MB | max: 1896.6MB | trend: stable (+0.20MB/hr))
```
▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 24%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,983 | 15,005 | +5978 | 15,675 | 84,644 | INCREASING (+7.72/hr) |
| Heap InUse | 351.6MB | 161.0MB | +190.6MB | 235.1MB | 1896.6MB | stable (+0.20MB/hr) |
| Heap Sys | 3757.2MB | 3770.3MB | -13.1MB | 4220.7MB | 6579.6MB | |
| Heap Objects | 1,603,104 | 571,637 | +1031467 | 995,462 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 26 | 15,419 | 231.3MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 29.65MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 18.08MB |
| 4 | `bufio.NewWriterSize` | 15.56MB |
| 5 | `internal/evaluation.mergeMetadata` | 14.5MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 13.19MB |
| 7 | `runtime.mallocgc` | 13.01MB |
| 8 | `bufio.NewReaderSize` | 11.54MB |
| 9 | `internal/evaluation.(*Engine).Evaluate` | 9.94MB |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 156.82GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 94.61GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 94.27GB |
| 4 | `experiment/local.topologicalSort` | 62.89GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.76GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.53GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.06GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96GB |
| 9 | `reflect.growslice` | 15.83GB |
| 10 | `jackskj/carta.getUniqueId` | 13.51GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/282 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/282 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 280/282 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/282 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 23.65MB | 280/282 | `██████░░░░░░░░░ 40%` |
| 6 | `net/http.(*Transport).dialConn` | 13.7MB | 5/282 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/282 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bytes.growSlice` | 13.59MB | 191/282 | `███░░░░░░░░░░░░ 23%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.87MB | 42/282 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/282 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 116.1GB | 271/282 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.87GB | 277/282 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.84GB | 277/282 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 57.16GB | 260/282 | `███████░░░░░░░░ 49%` |
| 5 | `experiment/local.topologicalSort` | 48.04GB | 259/282 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.35GB | 227/282 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 27.73GB | 203/282 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.09GB | 236/282 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/282 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 17.98GB | 114/282 | `██░░░░░░░░░░░░░ 15%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
