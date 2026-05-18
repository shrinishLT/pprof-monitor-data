# Overview: prod
*Last updated: 2026-05-18 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T13:03 (134 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,356 | avg: 15,269 | max: 84,644 | trend: decreasing (-24.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁
```

**Heap InUse** (current: 291.7MB | avg: 212.9MB | max: 1896.6MB | trend: decreasing (-1.46MB/hr))
```
▃▃▁▂▁▂▁▂▃▁▂▂▂▁▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,356 | 20,625 | -5269 | 15,269 | 84,644 | decreasing (-24.41/hr) |
| Heap InUse | 291.7MB | 491.8MB | -200.1MB | 212.9MB | 1896.6MB | decreasing (-1.46MB/hr) |
| Heap Sys | 6169.2MB | 6167.9MB | +1.3MB | 4264.7MB | 6169.2MB | |
| Heap Objects | 889,073 | 2,001,416 | -1112343 | 944,780 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 27 | 15,158 | 210.8MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.54MB |
| 5 | `internal/evaluation.mergeMetadata` | 6.0MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 3.09MB |
| 9 | `bufio.NewWriterSize` | 3.01MB |
| 10 | `experiment/local.topologicalSort` | 2.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 301.85GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 182.95GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 182.27GB |
| 4 | `experiment/local.topologicalSort` | 120.66GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 116.0GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 94.99GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 57.87GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 53.04GB |
| 9 | `reflect.growslice` | 31.13GB |
| 10 | `segmentio/kafka-go.makePartitions` | 28.93GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/134 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 132/134 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 21.71MB | 132/134 | `████████░░░░░░░ 59%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/134 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/134 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/134 | `███████░░░░░░░░ 46%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/134 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.64MB | 66/134 | `█████░░░░░░░░░░ 34%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.72MB | 7/134 | `████░░░░░░░░░░░ 31%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.2MB | 34/134 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.51GB | 127/134 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 50.8GB | 123/134 | `█████████████░░ 86%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 30.01GB | 129/134 | `███████░░░░░░░░ 51%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 30.0GB | 129/134 | `███████░░░░░░░░ 51%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 24.85GB | 125/134 | `██████░░░░░░░░░ 42%` |
| 6 | `fmt.(*buffer).writeString` | 24.13GB | 16/134 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 21.57GB | 79/134 | `█████░░░░░░░░░░ 36%` |
| 8 | `reflect.growslice` | 21.53GB | 42/134 | `█████░░░░░░░░░░ 36%` |
| 9 | `experiment/local.topologicalSort` | 21.42GB | 111/134 | `█████░░░░░░░░░░ 36%` |
| 10 | `jackskj/carta.getUniqueId` | 17.48GB | 25/134 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
