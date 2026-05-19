# Overview: prod
*Last updated: 2026-05-19 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T11:30 (184 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,644 | avg: 15,375 | max: 84,644 | trend: decreasing (-5.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁
```

**Heap InUse** (current: 220.7MB | avg: 228.8MB | max: 1896.6MB | trend: stable (+0.08MB/hr))
```
▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,644 | 14,409 | +235 | 15,375 | 84,644 | decreasing (-5.03/hr) |
| Heap InUse | 220.7MB | 158.3MB | +62.4MB | 228.8MB | 1896.6MB | stable (+0.08MB/hr) |
| Heap Sys | 4949.7MB | 2115.0MB | +2834.7MB | 4462.5MB | 6579.6MB | |
| Heap Objects | 1,009,243 | 576,180 | +433063 | 979,074 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 24 | 15,119 | 218.4MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `internal/evaluation.mergeMetadata` | 14.0MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 8.33MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 6.85MB |
| 8 | `experiment/local.topologicalSort` | 3.04MB |
| 9 | `bytes.growSlice` | 3.02MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 33.52GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 19.89GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 19.87GB |
| 4 | `experiment/local.topologicalSort` | 13.3GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.63GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 6.24GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 4.75GB |
| 8 | `reflect.growslice` | 3.55GB |
| 9 | `jackskj/carta.getUniqueId` | 3.47GB |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 3.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/184 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/184 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/184 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 182/184 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.32MB | 182/184 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/184 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/184 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.85MB | 16/184 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `bytes.growSlice` | 11.99MB | 109/184 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/184 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.05GB | 173/184 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.7GB | 179/184 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.59GB | 179/184 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 69.64GB | 175/184 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 50.79GB | 161/184 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.52GB | 129/184 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 33.6GB | 107/184 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/184 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 27.73GB | 45/184 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/184 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
