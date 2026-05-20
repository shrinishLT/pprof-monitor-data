# Overview: prod
*Last updated: 2026-05-20 17:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T17:32 (244 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,028 | avg: 15,514 | max: 84,644 | trend: INCREASING (+3.69/hr))
```
▁▂▂▂▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▄█▁▁▁▁▁▁▁▁▁▁▂▁▃▁
```

**Heap InUse** (current: 234.5MB | avg: 231.3MB | max: 1896.6MB | trend: stable (+0.13MB/hr))
```
▃▃▃▂▅▂▂▂▁▂▂▂▁▂▂▁▃▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▅▁▁▁▁▃▁▁▂▂▁▁▁▂▃▂▁▁▁▂▂▁▂▁▁▁▁▂▁▁▁▁▆▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█▂▂▁▁▁▁▁▁▁▁▂▁▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,028 | 19,980 | -4952 | 15,514 | 84,644 | INCREASING (+3.69/hr) |
| Heap InUse | 234.5MB | 438.9MB | -204.4MB | 231.3MB | 1896.6MB | stable (+0.13MB/hr) |
| Heap Sys | 4972.4MB | 4968.7MB | +3.7MB | 4326.5MB | 6579.6MB | |
| Heap Objects | 1,035,264 | 2,281,833 | -1246569 | 983,654 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 36 | 16,212 | 235.7MB | 958.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 10.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `experiment/local.topologicalSort` | 7.61MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 7.3MB |
| 7 | `bytes.growSlice` | 6.03MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 9 | `segmentio/kafka-go.makePartitions` | 4.54MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 81.03GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 48.99GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 48.71GB |
| 4 | `experiment/local.topologicalSort` | 32.31GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.61GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 15.5GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 15.16GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 9.04GB |
| 9 | `fmt.Sprintf` | 8.88GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 6.81GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.14MB | 7/244 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.05MB | 12/244 | `██████████░░░░░ 72%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 242/244 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 32.79MB | 14/244 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 24.2MB | 242/244 | `█████░░░░░░░░░░ 38%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 13.01MB | 4/244 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 12.74MB | 157/244 | `███░░░░░░░░░░░░ 20%` |
| 8 | `net/http.(*Transport).dialConn` | 12.62MB | 4/244 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.03MB | 31/244 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/244 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.8GB | 233/244 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.89GB | 239/244 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.82GB | 239/244 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 61.49GB | 231/244 | `███████░░░░░░░░ 51%` |
| 5 | `experiment/local.topologicalSort` | 49.87GB | 221/244 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.93GB | 189/244 | `█████░░░░░░░░░░ 37%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.82GB | 166/244 | `███░░░░░░░░░░░░ 24%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 28.25GB | 218/244 | `███░░░░░░░░░░░░ 23%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/244 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 20.24GB | 91/244 | `██░░░░░░░░░░░░░ 16%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.2x avg)
