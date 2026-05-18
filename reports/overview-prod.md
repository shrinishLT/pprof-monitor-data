# Overview: prod
*Last updated: 2026-05-19 03:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T03:33 (168 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,855 | avg: 15,377 | max: 84,644 | trend: decreasing (-6.80/hr))
```
▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 170.1MB | avg: 230.3MB | max: 1896.6MB | trend: stable (+0.21MB/hr))
```
▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,855 | 14,390 | +465 | 15,377 | 84,644 | decreasing (-6.80/hr) |
| Heap InUse | 170.1MB | 135.7MB | +34.4MB | 230.3MB | 1896.6MB | stable (+0.21MB/hr) |
| Heap Sys | 2245.0MB | 2246.5MB | -1.5MB | 4614.0MB | 6579.6MB | |
| Heap Objects | 723,128 | 489,313 | +233815 | 983,312 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 8 | 14,634 | 230.1MB | 404.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 5 | `bytes.growSlice` | 5.03MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 7 | `bufio.NewReaderSize` | 3.01MB |
| 8 | `reflect.mapassign_faststr0` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 12.38GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 7.49GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 7.42GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 7.03GB |
| 5 | `experiment/local.topologicalSort` | 4.92GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 3.84GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 3.2GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 2.35GB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.54GB |
| 10 | `fmt.Sprintf` | 1.35GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.57MB | 4/168 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.33MB | 8/168 | `█████████░░░░░░ 66%` |
| 3 | `database/sql.convertAssignRows` | 36.83MB | 9/168 | `███████░░░░░░░░ 46%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 166/168 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 27.68MB | 166/168 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/168 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/168 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.14MB | 11/168 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `bytes.growSlice` | 12.1MB | 98/168 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.86MB | 5/168 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 126.3GB | 157/168 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 74.18GB | 163/168 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.04GB | 163/168 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 72.83GB | 161/168 | `████████░░░░░░░ 57%` |
| 5 | `experiment/local.topologicalSort` | 53.81GB | 145/168 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.78GB | 113/168 | `██████░░░░░░░░░ 41%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 37.55GB | 91/168 | `████░░░░░░░░░░░ 29%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 31.88GB | 159/168 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 30.23GB | 41/168 | `███░░░░░░░░░░░░ 23%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/168 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
