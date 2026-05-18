# Overview: prod
*Last updated: 2026-05-19 00:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T00:33 (162 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,637 | avg: 15,402 | max: 84,644 | trend: decreasing (-5.63/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 287.5MB | avg: 230.6MB | max: 1896.6MB | trend: stable (+0.26MB/hr))
```
▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,637 | 14,292 | +345 | 15,402 | 84,644 | decreasing (-5.63/hr) |
| Heap InUse | 287.5MB | 214.7MB | +72.8MB | 230.6MB | 1896.6MB | stable (+0.26MB/hr) |
| Heap Sys | 6573.7MB | 6573.5MB | +0.2MB | 4621.5MB | 6579.6MB | |
| Heap Objects | 1,214,436 | 709,168 | +505268 | 985,396 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 2 | 14,464 | 251.1MB | 287.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `bytes.growSlice` | 4.52MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.04MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 531.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 321.76GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 320.81GB |
| 4 | `experiment/local.topologicalSort` | 212.48GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 166.85GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 152.9GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 101.21GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 69.95GB |
| 9 | `fmt.Sprintf` | 53.13GB |
| 10 | `segmentio/kafka-go.makePartitions` | 44.4GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/162 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/162 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/162 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 160/162 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.54MB | 160/162 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/162 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/162 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.54MB | 92/162 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/162 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/162 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 120.18GB | 151/162 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 72.52GB | 155/162 | `█████████░░░░░░ 60%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 70.54GB | 157/162 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 70.41GB | 157/162 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 51.3GB | 139/162 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.81GB | 107/162 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 36.02GB | 86/162 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.69GB | 153/162 | `███░░░░░░░░░░░░ 26%` |
| 9 | `fmt.Sprintf` | 29.76GB | 36/162 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/162 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
