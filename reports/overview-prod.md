# Overview: prod
*Last updated: 2026-05-18 18:48 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:48 (147 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,358 | avg: 15,301 | max: 84,644 | trend: decreasing (-16.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁
```

**Heap InUse** (current: 276.5MB | avg: 220.9MB | max: 1896.6MB | trend: decreasing (-0.50MB/hr))
```
▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,358 | 14,329 | +29 | 15,301 | 84,644 | decreasing (-16.05/hr) |
| Heap InUse | 276.5MB | 308.4MB | -31.9MB | 220.9MB | 1896.6MB | decreasing (-0.50MB/hr) |
| Heap Sys | 6171.4MB | 6171.4MB | +0.0MB | 4433.5MB | 6179.8MB | |
| Heap Objects | 1,219,259 | 2,408,763 | -1189504 | 967,222 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 40 | 15,312 | 240.9MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bytes.growSlice` | 3.52MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.02MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 418.86GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 253.61GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 252.86GB |
| 4 | `experiment/local.topologicalSort` | 167.28GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 131.32GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 80.06GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 40.46GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/147 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 145/147 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 24.7MB | 145/147 | `██████████░░░░░ 67%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/147 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/147 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/147 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.23MB | 79/147 | `████░░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/147 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/147 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/147 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 80.94GB | 136/147 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 65.08GB | 140/147 | `████████████░░░ 80%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 47.56GB | 142/147 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 47.5GB | 142/147 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.76GB | 92/147 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 34.51GB | 124/147 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 28.07GB | 138/147 | `█████░░░░░░░░░░ 34%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 24.46GB | 71/147 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/147 | `████░░░░░░░░░░░ 29%` |
| 10 | `reflect.growslice` | 22.61GB | 47/147 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
