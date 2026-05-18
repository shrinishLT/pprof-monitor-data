# Overview: prod
*Last updated: 2026-05-18 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T14:03 (136 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,533 | avg: 15,262 | max: 84,644 | trend: decreasing (-23.97/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁
```

**Heap InUse** (current: 310.8MB | avg: 213.9MB | max: 1896.6MB | trend: decreasing (-1.30MB/hr))
```
▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,533 | 15,046 | -513 | 15,262 | 84,644 | decreasing (-23.97/hr) |
| Heap InUse | 310.8MB | 257.0MB | +53.8MB | 213.9MB | 1896.6MB | decreasing (-1.30MB/hr) |
| Heap Sys | 6171.8MB | 6170.7MB | +1.1MB | 4292.7MB | 6171.8MB | |
| Heap Objects | 1,444,898 | 785,216 | +659682 | 947,284 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 29 | 15,132 | 215.8MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bytes.growSlice` | 4.02MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewReaderSize` | 2.52MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.03MB |
| 10 | `reflect.unsafe_New` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 316.24GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 191.54GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 190.93GB |
| 4 | `experiment/local.topologicalSort` | 126.37GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 121.33GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 99.43GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 60.6GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 55.46GB |
| 9 | `reflect.growslice` | 31.44GB |
| 10 | `segmentio/kafka-go.makePartitions` | 30.25GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/136 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 134/136 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 22.21MB | 134/136 | `█████████░░░░░░ 60%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/136 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/136 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/136 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/136 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.37MB | 68/136 | `█████░░░░░░░░░░ 33%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/136 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.96MB | 35/136 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.48GB | 129/136 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 54.99GB | 125/136 | `█████████████░░ 92%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 32.44GB | 131/136 | `████████░░░░░░░ 54%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 32.44GB | 131/136 | `████████░░░░░░░ 54%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.33GB | 127/136 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/136 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 23.47GB | 81/136 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 23.25GB | 113/136 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.growslice` | 21.98GB | 44/136 | `█████░░░░░░░░░░ 36%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/136 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
