# Overview: prod
*Last updated: 2026-05-18 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T21:32 (156 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,375 | avg: 15,428 | max: 84,644 | trend: decreasing (-4.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁▁▂
```

**Heap InUse** (current: 285.0MB | avg: 229.4MB | max: 1896.6MB | trend: stable (+0.19MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂▃▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,375 | 14,823 | +1552 | 15,428 | 84,644 | decreasing (-4.23/hr) |
| Heap InUse | 285.0MB | 339.4MB | -54.4MB | 229.4MB | 1896.6MB | stable (+0.19MB/hr) |
| Heap Sys | 6572.8MB | 6562.6MB | +10.2MB | 4546.3MB | 6573.6MB | |
| Heap Objects | 844,072 | 1,455,455 | -611383 | 987,999 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 49 | 15,715 | 264.2MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 15.08MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 6 | `bufio.NewWriterSize` | 5.54MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 8 | `bufio.NewReaderSize` | 4.02MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 498.09GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 301.38GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 300.55GB |
| 4 | `experiment/local.topologicalSort` | 199.05GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 156.07GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 143.0GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 94.85GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 65.34GB |
| 9 | `fmt.Sprintf` | 49.6GB |
| 10 | `segmentio/kafka-go.makePartitions` | 40.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/156 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 154/156 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 26.47MB | 154/156 | `██████████░░░░░ 72%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/156 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/156 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/156 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.94MB | 88/156 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 11.55MB | 10/156 | `████░░░░░░░░░░░ 31%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/156 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.62MB | 51/156 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 103.79GB | 145/156 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 69.53GB | 149/156 | `██████████░░░░░ 66%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 60.93GB | 151/156 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 60.83GB | 151/156 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 44.31GB | 133/156 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 44.21GB | 101/156 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 31.35GB | 80/156 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 30.24GB | 147/156 | `████░░░░░░░░░░░ 29%` |
| 9 | `fmt.Sprintf` | 25.41GB | 30/156 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.(*buffer).writeString` | 24.13GB | 16/156 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
