# Overview: prod
*Last updated: 2026-05-18 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:03 (144 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,828 | avg: 15,290 | max: 84,644 | trend: decreasing (-17.99/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁
```

**Heap InUse** (current: 305.7MB | avg: 218.5MB | max: 1896.6MB | trend: decreasing (-0.74MB/hr))
```
▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,828 | 14,433 | +1395 | 15,290 | 84,644 | decreasing (-17.99/hr) |
| Heap InUse | 305.7MB | 208.7MB | +97.0MB | 218.5MB | 1896.6MB | decreasing (-0.74MB/hr) |
| Heap Sys | 6177.7MB | 6176.3MB | +1.4MB | 4397.3MB | 6179.8MB | |
| Heap Objects | 1,219,155 | 544,903 | +674252 | 950,256 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 37 | 15,269 | 233.2MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 9.05MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewWriterSize` | 4.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.51MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 392.2GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 237.46GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 236.84GB |
| 4 | `experiment/local.topologicalSort` | 156.75GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 122.82GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 75.0GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.9GB |
| 9 | `fmt.Sprintf` | 37.53GB |
| 10 | `segmentio/kafka-go.makePartitions` | 35.59GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/144 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 142/144 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 24.06MB | 142/144 | `█████████░░░░░░ 65%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/144 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/144 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/144 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/144 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.32MB | 76/144 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/144 | `████░░░░░░░░░░░ 33%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/144 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 73.37GB | 133/144 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 63.54GB | 137/144 | `████████████░░░ 86%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 43.14GB | 139/144 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 43.1GB | 139/144 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 31.52GB | 89/144 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 31.24GB | 121/144 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 27.32GB | 135/144 | `█████░░░░░░░░░░ 37%` |
| 8 | `fmt.(*buffer).writeString` | 24.13GB | 16/144 | `████░░░░░░░░░░░ 32%` |
| 9 | `reflect.growslice` | 22.61GB | 47/144 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.(*Engine).evaluateFlag` | 22.02GB | 68/144 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
