# Overview: prod
*Last updated: 2026-05-21 02:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T02:30 (262 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,977 | avg: 15,697 | max: 84,644 | trend: INCREASING (+10.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 501.2MB | avg: 236.7MB | max: 1896.6MB | trend: stable (+0.34MB/hr))
```
▁▁▁▁▁▁▂▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,977 | 15,212 | +2765 | 15,697 | 84,644 | INCREASING (+10.73/hr) |
| Heap InUse | 501.2MB | 227.4MB | +273.8MB | 236.7MB | 1896.6MB | stable (+0.34MB/hr) |
| Heap Sys | 5103.4MB | 4861.8MB | +241.6MB | 4316.8MB | 6579.6MB | |
| Heap Objects | 1,718,114 | 694,623 | +1023491 | 995,492 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 6 | 15,520 | 289.4MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 37.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 32.19MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 24.01MB |
| 5 | `database/sql.convertAssignRows` | 19.0MB |
| 6 | `bufio.NewWriterSize` | 11.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.04MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 10 | `bufio.NewReaderSize` | 7.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 142.7GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 85.79GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 85.71GB |
| 4 | `experiment/local.topologicalSort` | 56.91GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.22GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 27.25GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 20.41GB |
| 8 | `fmt.Sprintf` | 13.55GB |
| 9 | `reflect.growslice` | 11.0GB |
| 10 | `jackskj/carta.getUniqueId` | 10.23GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/262 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.44MB | 13/262 | `██████████░░░░░ 69%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 260/262 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.87MB | 15/262 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 24.43MB | 260/262 | `█████░░░░░░░░░░ 39%` |
| 6 | `bytes.growSlice` | 13.92MB | 175/262 | `███░░░░░░░░░░░░ 22%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/262 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 13.61MB | 5/262 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/262 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.63MB | 36/262 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 117.61GB | 251/262 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.68GB | 257/262 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.63GB | 257/262 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 59.41GB | 242/262 | `███████░░░░░░░░ 50%` |
| 5 | `experiment/local.topologicalSort` | 48.8GB | 239/262 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.46GB | 207/262 | `█████░░░░░░░░░░ 36%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.57GB | 184/262 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 27.85GB | 222/262 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/262 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 18.63GB | 107/262 | `██░░░░░░░░░░░░░ 15%` |

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
