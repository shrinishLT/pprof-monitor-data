# Overview: prod
*Last updated: 2026-05-19 19:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T19:03 (199 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,991 | avg: 15,381 | max: 84,644 | trend: decreasing (-3.67/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂▁▁▂
```

**Heap InUse** (current: 230.6MB | avg: 230.5MB | max: 1896.6MB | trend: stable (+0.16MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,991 | 14,709 | +1282 | 15,381 | 84,644 | decreasing (-3.67/hr) |
| Heap InUse | 230.6MB | 191.4MB | +39.2MB | 230.5MB | 1896.6MB | stable (+0.16MB/hr) |
| Heap Sys | 4940.2MB | 4939.8MB | +0.4MB | 4498.8MB | 6579.6MB | |
| Heap Objects | 712,520 | 801,561 | -89041 | 985,388 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 39 | 15,248 | 230.9MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 20.22MB |
| 3 | `bytes.growSlice` | 11.07MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `bufio.NewReaderSize` | 8.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 8 | `bufio.NewWriterSize` | 4.02MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 171.47GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 102.85GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 102.83GB |
| 4 | `experiment/local.topologicalSort` | 68.25GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 56.56GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.29GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.47GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.95GB |
| 9 | `fmt.Sprintf` | 17.05GB |
| 10 | `segmentio/kafka-go.makePartitions` | 11.75GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/199 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/199 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 197/199 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/199 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.86MB | 197/199 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/199 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/199 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 11.91MB | 122/199 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/199 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 195/199 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 119.04GB | 188/199 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.21GB | 194/199 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.11GB | 194/199 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.42GB | 189/199 | `████████░░░░░░░ 55%` |
| 5 | `experiment/local.topologicalSort` | 50.1GB | 176/199 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.97GB | 144/199 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.97GB | 122/199 | `████░░░░░░░░░░░ 26%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.09GB | 180/199 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/199 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 23.68GB | 59/199 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
