# Overview: prod
*Last updated: 2026-05-22 13:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T13:00 (353 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,788 | avg: 15,817 | max: 84,644 | trend: INCREASING (+7.81/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁
```

**Heap InUse** (current: 178.7MB | avg: 242.6MB | max: 1896.6MB | trend: stable (+0.29MB/hr))
```
▁▂▂▁▄▂▁▁▂▁▂▄▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,788 | 14,520 | +1268 | 15,817 | 84,644 | INCREASING (+7.81/hr) |
| Heap InUse | 178.7MB | 187.1MB | -8.4MB | 242.6MB | 1896.6MB | stable (+0.29MB/hr) |
| Heap Sys | 973.8MB | 977.4MB | -3.6MB | 4286.2MB | 6579.6MB | |
| Heap Objects | 615,130 | 1,061,876 | -446746 | 1,010,535 | 8,100,802 | |

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
| 2026-05-22 | 29 | 16,239 | 248.2MB | 962.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 11.07MB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 11.02MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 8.51MB |
| 6 | `internal/evaluation.mergeMetadata` | 8.5MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 6.93MB |
| 8 | `bufio.NewWriterSize` | 6.04MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 36.6GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 22.11GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 21.94GB |
| 4 | `experiment/local.topologicalSort` | 14.7GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 11.47GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 7.01GB |
| 7 | `reflect.growslice` | 3.44GB |
| 8 | `fmt.Sprintf` | 3.37GB |
| 9 | `jackskj/carta.getUniqueId` | 3.35GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 3.12GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/353 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/353 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 351/353 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 30.39MB | 18/353 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 25.65MB | 351/353 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 14.21MB | 250/353 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/353 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/353 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.71MB | 53/353 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/353 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 134.17GB | 342/353 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 79.65GB | 348/353 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 79.63GB | 348/353 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 55.04GB | 330/353 | `██████░░░░░░░░░ 41%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 54.25GB | 329/353 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.42GB | 298/353 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 30.56GB | 274/353 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 26.4GB | 290/353 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/353 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `fmt.Sprintf` | 20.03GB | 174/353 | `██░░░░░░░░░░░░░ 14%` |

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
