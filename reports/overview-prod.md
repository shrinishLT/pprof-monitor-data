# Overview: prod
*Last updated: 2026-05-19 16:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T16:30 (194 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,647 | avg: 15,374 | max: 84,644 | trend: decreasing (-4.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 306.5MB | avg: 229.2MB | max: 1896.6MB | trend: stable (+0.09MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,647 | 14,565 | +82 | 15,374 | 84,644 | decreasing (-4.44/hr) |
| Heap InUse | 306.5MB | 203.8MB | +102.7MB | 229.2MB | 1896.6MB | stable (+0.09MB/hr) |
| Heap Sys | 4947.5MB | 4946.1MB | +1.4MB | 4487.3MB | 6579.6MB | |
| Heap Objects | 1,386,506 | 870,221 | +516285 | 980,635 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 34 | 15,185 | 223.6MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 35.03MB |
| 3 | `runtime.mallocgc` | 20.22MB |
| 4 | `database/sql.convertAssignRows` | 20.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.09MB |
| 8 | `bytes.growSlice` | 3.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `internal/strconv.FormatInt` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 122.44GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 73.45GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 73.25GB |
| 4 | `experiment/local.topologicalSort` | 48.66GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 38.24GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 23.19GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 22.22GB |
| 8 | `fmt.Sprintf` | 11.56GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 10.17GB |
| 10 | `segmentio/kafka-go.makePartitions` | 8.24GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/194 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.13MB | 10/194 | `████████░░░░░░░ 58%` |
| 3 | `database/sql.convertAssignRows` | 37.0MB | 11/194 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 192/194 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.01MB | 192/194 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/194 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/194 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 11.94MB | 117/194 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/194 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 190/194 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.14GB | 183/194 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.65GB | 189/194 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.55GB | 189/194 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.92GB | 184/194 | `████████░░░░░░░ 56%` |
| 5 | `experiment/local.topologicalSort` | 49.8GB | 171/194 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.96GB | 139/194 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.11GB | 117/194 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.32GB | 175/194 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 24.49GB | 54/194 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/194 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
