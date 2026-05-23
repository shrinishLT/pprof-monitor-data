# Overview: prod
*Last updated: 2026-05-23 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T05:30 (386 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,319 | avg: 15,818 | max: 84,644 | trend: INCREASING (+5.97/hr))
```
▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 155.9MB | avg: 239.6MB | max: 1896.6MB | trend: stable (+0.14MB/hr))
```
▂▁▁▂▃▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁▂▂▂▂▂▁▂▂▂▁▂▂▂▂▃▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▂▂█▁▁▁▁▁▂▁▁▂▁▂▁▂▁▁▂▁▁▁▁▁▁▂▂▁▂▂▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,319 | 14,254 | +1065 | 15,818 | 84,644 | INCREASING (+5.97/hr) |
| Heap InUse | 155.9MB | 172.0MB | -16.1MB | 239.6MB | 1896.6MB | stable (+0.14MB/hr) |
| Heap Sys | 4212.6MB | 4216.6MB | -4.0MB | 4226.5MB | 6579.6MB | |
| Heap Objects | 465,773 | 1,014,124 | -548351 | 997,543 | 8,100,802 | |

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
| 2026-05-23 | 12 | 15,262 | 194.1MB | 349.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `internal/evaluation.mergeMetadata` | 18.5MB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 9.52MB |
| 4 | `runtime.mallocgc` | 9.51MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 7.64MB |
| 6 | `experiment/local.topologicalSort` | 7.6MB |
| 7 | `bytes.growSlice` | 6.03MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 5.81MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 31.65GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 18.87GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 18.77GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 15.6GB |
| 5 | `experiment/local.topologicalSort` | 12.54GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.93GB |
| 7 | `reflect.growslice` | 8.76GB |
| 8 | `jackskj/carta.getUniqueId` | 6.47GB |
| 9 | `reflect.unsafe_New` | 6.13GB |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 6.07GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.13MB | 9/386 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.74MB | 15/386 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 384/386 | `█████████░░░░░░ 64%` |
| 4 | `database/sql.convertAssignRows` | 29.0MB | 19/386 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 24.38MB | 384/386 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 14.1MB | 276/386 | `███░░░░░░░░░░░░ 24%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/386 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/386 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/386 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.54MB | 62/386 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.93GB | 375/386 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 75.45GB | 381/386 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 75.42GB | 381/386 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.91GB | 363/386 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 50.73GB | 362/386 | `█████░░░░░░░░░░ 39%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.3GB | 331/386 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.61GB | 304/386 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.57GB | 319/386 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/386 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `fmt.Sprintf` | 18.5GB | 197/386 | `██░░░░░░░░░░░░░ 14%` |

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
