# Overview: prod
*Last updated: 2026-05-18 11:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T11:31 (131 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,747 | avg: 15,226 | max: 84,644 | trend: decreasing (-30.10/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁
```

**Heap InUse** (current: 350.9MB | avg: 209.6MB | max: 1896.6MB | trend: decreasing (-1.87MB/hr))
```
▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃▇▅▄▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,747 | 14,525 | +222 | 15,226 | 84,644 | decreasing (-30.10/hr) |
| Heap InUse | 350.9MB | 266.6MB | +84.3MB | 209.6MB | 1896.6MB | decreasing (-1.87MB/hr) |
| Heap Sys | 6167.3MB | 4672.9MB | +1494.4MB | 4221.1MB | 6167.3MB | |
| Heap Objects | 1,680,914 | 1,080,249 | +600665 | 936,232 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 24 | 14,913 | 192.6MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `internal/evaluation.mergeMetadata` | 26.01MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 17.35MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `experiment/local.topologicalSort` | 8.1MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 6.81MB |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 5.62MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 10 | `bytes.growSlice` | 4.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 243.97GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 148.0GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 147.21GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 114.45GB |
| 5 | `experiment/local.topologicalSort` | 97.43GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 76.66GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 52.32GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 46.76GB |
| 9 | `reflect.growslice` | 27.81GB |
| 10 | `segmentio/kafka-go.makePartitions` | 26.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/131 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 129/131 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 20.93MB | 129/131 | `████████░░░░░░░ 56%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/131 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/131 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/131 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/131 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.67MB | 6/131 | `█████░░░░░░░░░░ 34%` |
| 9 | `bytes.growSlice` | 12.3MB | 63/131 | `█████░░░░░░░░░░ 33%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.44MB | 31/131 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 57.15GB | 124/131 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 45.16GB | 120/131 | `███████████░░░░ 79%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 26.75GB | 126/131 | `███████░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 26.72GB | 126/131 | `███████░░░░░░░░ 46%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 24.17GB | 122/131 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/131 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 20.83GB | 39/131 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.99GB | 76/131 | `████░░░░░░░░░░░ 33%` |
| 9 | `experiment/local.topologicalSort` | 18.94GB | 108/131 | `████░░░░░░░░░░░ 33%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/131 | `████░░░░░░░░░░░ 30%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
