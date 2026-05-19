# Overview: prod
*Last updated: 2026-05-19 17:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T17:30 (196 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,248 | avg: 15,383 | max: 84,644 | trend: decreasing (-3.74/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▅▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▂▃▄▃▅▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▄▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 334.1MB | avg: 230.8MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂▃▃▃▂▃▂▂▄▁▁▁▁▁▁▂▄▁▁▁▂▁▁▂▇▂▁▂▁▅▁▁▂▂▂▁▂▃▅▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,248 | 15,322 | +1926 | 15,383 | 84,644 | decreasing (-3.74/hr) |
| Heap InUse | 334.1MB | 439.8MB | -105.7MB | 230.8MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 4949.7MB | 4951.0MB | -1.3MB | 4492.1MB | 6579.6MB | |
| Heap Objects | 1,576,498 | 2,051,925 | -475427 | 989,141 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 36 | 15,246 | 232.6MB | 661.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 25.32MB |
| 3 | `runtime.mallocgc` | 20.22MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `bufio.NewWriterSize` | 7.54MB |
| 8 | `bufio.NewReaderSize` | 5.02MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 136.23GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 81.62GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 81.59GB |
| 4 | `experiment/local.topologicalSort` | 54.09GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.46GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.31GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 25.77GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 21.79GB |
| 9 | `fmt.Sprintf` | 13.18GB |
| 10 | `segmentio/kafka-go.makePartitions` | 9.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 69.11MB | 6/196 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 45.54MB | 11/196 | `█████████░░░░░░ 65%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 194/196 | `███████░░░░░░░░ 53%` |
| 4 | `database/sql.convertAssignRows` | 35.58MB | 12/196 | `███████░░░░░░░░ 51%` |
| 5 | `runtime.mallocgc` | 25.95MB | 194/196 | `█████░░░░░░░░░░ 37%` |
| 6 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/196 | `████░░░░░░░░░░░ 26%` |
| 7 | `net/http.(*Transport).dialConn` | 13.17MB | 3/196 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `bytes.growSlice` | 12.03MB | 119/196 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 11.76MB | 19/196 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 192/196 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 118.3GB | 185/196 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.76GB | 191/196 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.66GB | 191/196 | `████████░░░░░░░ 58%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 66.66GB | 186/196 | `████████░░░░░░░ 56%` |
| 5 | `experiment/local.topologicalSort` | 49.83GB | 173/196 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 46.88GB | 141/196 | `█████░░░░░░░░░░ 39%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.99GB | 119/196 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.2GB | 177/196 | `███░░░░░░░░░░░░ 25%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/196 | `███░░░░░░░░░░░░ 20%` |
| 10 | `fmt.Sprintf` | 24.08GB | 56/196 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
