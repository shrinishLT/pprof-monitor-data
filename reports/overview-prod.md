# Overview: prod
*Last updated: 2026-05-19 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T15:00 (191 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,439 | avg: 15,379 | max: 84,644 | trend: decreasing (-4.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁
```

**Heap InUse** (current: 200.5MB | avg: 229.1MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,439 | 15,070 | -631 | 15,379 | 84,644 | decreasing (-4.31/hr) |
| Heap InUse | 200.5MB | 251.1MB | -50.6MB | 229.1MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 4945.1MB | 4944.6MB | +0.5MB | 4480.1MB | 6579.6MB | |
| Heap Objects | 931,808 | 1,221,137 | -289329 | 982,325 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 31 | 15,200 | 222.8MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/evaluation.mergeMetadata` | 8.5MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 3.64MB |
| 7 | `internal/evaluation.(*Engine).Evaluate` | 3.64MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `reflect.unsafe_NewArray` | 3.01MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 2.58MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 96.87GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 57.95GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 57.95GB |
| 4 | `experiment/local.topologicalSort` | 38.56GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.46GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 18.37GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 14.68GB |
| 8 | `fmt.Sprintf` | 9.12GB |
| 9 | `jackskj/carta.getUniqueId` | 7.19GB |
| 10 | `reflect.growslice` | 7.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/191 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/191 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/191 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 189/191 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.1MB | 189/191 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/191 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/191 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.25MB | 18/191 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 12.09MB | 114/191 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/191 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.2GB | 180/191 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.67GB | 186/191 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.56GB | 186/191 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 67.69GB | 181/191 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 49.87GB | 168/191 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.2GB | 136/191 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.38GB | 114/191 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.69GB | 172/191 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 25.3GB | 51/191 | `███░░░░░░░░░░░░ 21%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/191 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
