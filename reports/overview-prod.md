# Overview: prod
*Last updated: 2026-05-19 02:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T02:01 (165 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,368 | avg: 15,391 | max: 84,644 | trend: decreasing (-6.09/hr))
```
▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 404.4MB | avg: 231.7MB | max: 1896.6MB | trend: stable (+0.33MB/hr))
```
▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,368 | 14,557 | +811 | 15,391 | 84,644 | decreasing (-6.09/hr) |
| Heap InUse | 404.4MB | 217.4MB | +187.0MB | 231.7MB | 1896.6MB | stable (+0.33MB/hr) |
| Heap Sys | 6573.2MB | 6572.2MB | +1.0MB | 4656.9MB | 6579.6MB | |
| Heap Objects | 1,946,449 | 606,214 | +1340235 | 989,629 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 5 | 14,674 | 276.1MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 18.0MB |
| 4 | `bytes.growSlice` | 13.07MB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 11.1MB |
| 6 | `experiment/local.topologicalSort` | 10.64MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `experiment/local.(*Client).EvaluateV2` | 8.95MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 6.2MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 566.4GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 342.62GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 341.62GB |
| 4 | `experiment/local.topologicalSort` | 226.15GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 177.85GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 158.61GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 107.83GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 72.6GB |
| 9 | `fmt.Sprintf` | 56.38GB |
| 10 | `segmentio/kafka-go.makePartitions` | 46.41GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/165 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/165 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/165 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 163/165 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 28.05MB | 163/165 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/165 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/165 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.38MB | 95/165 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/165 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/165 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 128.6GB | 154/165 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 75.48GB | 160/165 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 75.33GB | 160/165 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 74.12GB | 158/165 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 54.88GB | 142/165 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.15GB | 110/165 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 38.35GB | 89/165 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 32.45GB | 156/165 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 31.72GB | 39/165 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/165 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
