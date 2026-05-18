# Overview: prod
*Last updated: 2026-05-18 22:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T22:00 (157 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,294 | avg: 15,421 | max: 84,644 | trend: decreasing (-4.70/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂▁
```

**Heap InUse** (current: 210.7MB | avg: 229.2MB | max: 1896.6MB | trend: stable (+0.18MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,294 | 16,375 | -2081 | 15,421 | 84,644 | decreasing (-4.70/hr) |
| Heap InUse | 210.7MB | 285.0MB | -74.3MB | 229.2MB | 1896.6MB | stable (+0.18MB/hr) |
| Heap Sys | 6578.4MB | 6572.8MB | +5.6MB | 4559.3MB | 6578.4MB | |
| Heap Objects | 621,996 | 844,072 | -222076 | 985,668 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 50 | 15,686 | 263.1MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `reflect.unsafe_NewArray` | 2.02MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewWriterSize` | 1.52MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 502.01GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 303.75GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 302.86GB |
| 4 | `experiment/local.topologicalSort` | 200.6GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 157.32GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 143.0GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 95.59GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 65.34GB |
| 9 | `fmt.Sprintf` | 50.03GB |
| 10 | `segmentio/kafka-go.makePartitions` | 40.85GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/157 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 155/157 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 26.65MB | 155/157 | `██████████░░░░░ 72%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/157 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/157 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/157 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.94MB | 88/157 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/157 | `████░░░░░░░░░░░ 31%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/157 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.47MB | 52/157 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 106.52GB | 146/157 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 70.02GB | 150/157 | `█████████░░░░░░ 65%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 62.53GB | 152/157 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 62.42GB | 152/157 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 45.48GB | 134/157 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 45.32GB | 102/157 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 32.15GB | 81/157 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.47GB | 148/157 | `████░░░░░░░░░░░ 28%` |
| 9 | `fmt.Sprintf` | 26.21GB | 31/157 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/157 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
