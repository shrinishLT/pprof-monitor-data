# Overview: prod
*Last updated: 2026-05-19 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T17:02 (195 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,322 | avg: 15,373 | max: 84,644 | trend: decreasing (-4.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 439.8MB | avg: 230.2MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,322 | 14,647 | +675 | 15,373 | 84,644 | decreasing (-4.39/hr) |
| Heap InUse | 439.8MB | 306.5MB | +133.3MB | 230.2MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4951.0MB | 4947.5MB | +3.5MB | 4489.7MB | 6579.6MB | |
| Heap Objects | 2,051,925 | 1,386,506 | +665419 | 986,129 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 35 | 15,189 | 229.7MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 39.63MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 20.33MB |
| 4 | `runtime.mallocgc` | 20.22MB |
| 5 | `database/sql.convertAssignRows` | 20.0MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 8 | `bytes.growSlice` | 8.54MB |
| 9 | `bufio.NewWriterSize` | 3.53MB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 129.66GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 77.66GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 77.6GB |
| 4 | `experiment/local.topologicalSort` | 51.45GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.34GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.46GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 24.53GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.68GB |
| 9 | `fmt.Sprintf` | 12.37GB |
| 10 | `segmentio/kafka-go.makePartitions` | 8.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/195 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/195 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 193/195 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/195 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.98MB | 193/195 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/195 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/195 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.91MB | 118/195 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/195 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 191/195 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.2GB | 184/195 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.7GB | 190/195 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.59GB | 190/195 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.77GB | 185/195 | `████████░░░░░░░ 56%` |
| 5 | `experiment/local.topologicalSort` | 49.81GB | 172/195 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.91GB | 140/195 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.04GB | 118/195 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.25GB | 176/195 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 24.27GB | 55/195 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/195 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
