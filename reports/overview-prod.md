# Overview: prod
*Last updated: 2026-05-19 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T14:01 (189 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,781 | avg: 15,386 | max: 84,644 | trend: decreasing (-4.02/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁
```

**Heap InUse** (current: 246.3MB | avg: 229.2MB | max: 1896.6MB | trend: stable (+0.10MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,781 | 14,965 | -184 | 15,386 | 84,644 | decreasing (-4.02/hr) |
| Heap InUse | 246.3MB | 180.2MB | +66.1MB | 229.2MB | 1896.6MB | stable (+0.10MB/hr) |
| Heap Sys | 4945.0MB | 4944.6MB | +0.4MB | 4475.2MB | 6579.6MB | |
| Heap Objects | 1,164,925 | 621,169 | +543756 | 981,328 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 29 | 15,230 | 222.6MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 6.5MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `bytes.growSlice` | 4.02MB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.08MB |
| 9 | `experiment/local.(*Client).EvaluateV2` | 2.67MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 77.1GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 46.1GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 46.09GB |
| 4 | `experiment/local.topologicalSort` | 30.61GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.38GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 14.56GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 12.93GB |
| 8 | `fmt.Sprintf` | 7.06GB |
| 9 | `reflect.growslice` | 6.61GB |
| 10 | `jackskj/carta.getUniqueId` | 6.48GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/189 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/189 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/189 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 187/189 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.16MB | 187/189 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/189 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/189 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.47MB | 17/189 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 12.11MB | 113/189 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/189 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.48GB | 178/189 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.82GB | 184/189 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.71GB | 184/189 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 68.28GB | 179/189 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 50.03GB | 166/189 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.47GB | 134/189 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.64GB | 112/189 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/189 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 25.97GB | 49/189 | `███░░░░░░░░░░░░ 21%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/189 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
