# Overview: prod
*Last updated: 2026-05-19 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T16:00 (193 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,565 | avg: 15,377 | max: 84,644 | trend: decreasing (-4.27/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁
```

**Heap InUse** (current: 203.8MB | avg: 228.8MB | max: 1896.6MB | trend: stable (+0.07MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,565 | 15,879 | -1314 | 15,377 | 84,644 | decreasing (-4.27/hr) |
| Heap InUse | 203.8MB | 182.8MB | +21.0MB | 228.8MB | 1896.6MB | stable (+0.07MB/hr) |
| Heap Sys | 4946.1MB | 4946.0MB | +0.1MB | 4485.0MB | 6579.6MB | |
| Heap Objects | 870,221 | 362,521 | +507700 | 978,532 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 33 | 15,201 | 221.0MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `encoding/json.(*decodeState).literalStore` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 114.98GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 68.92GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 68.83GB |
| 4 | `experiment/local.topologicalSort` | 45.72GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.98GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 21.79GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 20.29GB |
| 8 | `fmt.Sprintf` | 10.85GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 9.23GB |
| 10 | `jackskj/carta.getUniqueId` | 7.65GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 78.87MB | 5/193 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 47.37MB | 9/193 | `█████████░░░░░░ 60%` |
| 3 | `database/sql.convertAssignRows` | 38.7MB | 10/193 | `███████░░░░░░░░ 49%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 191/193 | `██████░░░░░░░░░ 46%` |
| 5 | `runtime.mallocgc` | 26.04MB | 191/193 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/193 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/193 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `bytes.growSlice` | 12.02MB | 116/193 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/193 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.72MB | 6/193 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.12GB | 182/193 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.63GB | 188/193 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.53GB | 188/193 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 67.16GB | 183/193 | `████████░░░░░░░ 56%` |
| 5 | `experiment/local.topologicalSort` | 49.8GB | 170/193 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 47.02GB | 138/193 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.18GB | 116/193 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.44GB | 174/193 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.Sprintf` | 24.74GB | 53/193 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/193 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
