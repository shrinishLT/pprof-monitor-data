# Overview: prod
*Last updated: 2026-05-19 09:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T09:00 (179 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,744 | avg: 15,323 | max: 84,644 | trend: decreasing (-8.99/hr))
```
▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▃▆▁▁▁▂▆▁▁▁▂▁▁▄▃▁▁▂▄▁▁▂▂▄▅▄█▁▁▂▁▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 177.9MB | avg: 227.1MB | max: 1896.6MB | trend: stable (-0.03MB/hr))
```
▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,744 | 14,211 | +533 | 15,323 | 84,644 | decreasing (-8.99/hr) |
| Heap InUse | 177.9MB | 145.6MB | +32.3MB | 227.1MB | 1896.6MB | stable (-0.03MB/hr) |
| Heap Sys | 3150.4MB | 2898.3MB | +252.1MB | 4500.7MB | 6579.6MB | |
| Heap Objects | 728,446 | 685,350 | +43096 | 969,335 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 19 | 14,562 | 199.2MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.02MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 8 | `bufio.NewReaderSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 80.92GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 51.59GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 49.02GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 48.61GB |
| 5 | `experiment/local.topologicalSort` | 32.22GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.31GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 23.64GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 15.33GB |
| 9 | `reflect.growslice` | 12.45GB |
| 10 | `jackskj/carta.getUniqueId` | 9.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/179 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/179 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/179 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 177/179 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.59MB | 177/179 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/179 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/179 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 11.66MB | 104/179 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.42MB | 13/179 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/179 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 121.87GB | 168/179 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.72GB | 174/179 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.6GB | 174/179 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 70.22GB | 172/179 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 51.67GB | 156/179 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.73GB | 124/179 | `██████░░░░░░░░░ 40%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 34.7GB | 102/179 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.77GB | 170/179 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 28.34GB | 44/179 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/179 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
