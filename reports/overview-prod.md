# Overview: prod
*Last updated: 2026-05-18 18:53 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T18:53 (148 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,474 | avg: 15,302 | max: 84,644 | trend: decreasing (-15.63/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁
```

**Heap InUse** (current: 248.1MB | avg: 221.1MB | max: 1896.6MB | trend: stable (-0.48MB/hr))
```
▁▁▁▂▂▂▁▁▂▂▂▂▁▁▁▂▂▂▁▂▂▂▁▂▂▁▂▆▅▃▅▂▂▁▂▂▄▁▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂▂▁▁▁▁▁▁▁▁▁▁▁▄▆▁▁▁▁▁▃▃▅▄▃▅▄█▄▃▄▃▃▅▆▄▄▂▄▆▄▄▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,474 | 14,358 | +1116 | 15,302 | 84,644 | decreasing (-15.63/hr) |
| Heap InUse | 248.1MB | 276.5MB | -28.4MB | 221.1MB | 1896.6MB | stable (-0.48MB/hr) |
| Heap Sys | 6170.7MB | 6171.4MB | -0.7MB | 4445.2MB | 6179.8MB | |
| Heap Objects | 455,163 | 1,219,259 | -764096 | 963,762 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 41 | 15,316 | 241.1MB | 491.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 10.71MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bufio.NewWriterSize` | 4.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 9 | `bufio.NewReaderSize` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 419.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 254.13GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 253.41GB |
| 4 | `experiment/local.topologicalSort` | 167.62GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 135.37GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 131.58GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 80.22GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 61.91GB |
| 9 | `fmt.Sprintf` | 40.58GB |
| 10 | `segmentio/kafka-go.makePartitions` | 36.72GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/148 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 146/148 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 24.9MB | 146/148 | `██████████░░░░░ 67%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/148 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/148 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 17.25MB | 2/148 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 12.21MB | 80/148 | `████░░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/148 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/148 | `████░░░░░░░░░░░ 28%` |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 9.44MB | 3/148 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 83.42GB | 137/148 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 65.58GB | 141/148 | `███████████░░░░ 78%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 49.0GB | 143/148 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 48.94GB | 143/148 | `████████░░░░░░░ 58%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.8GB | 93/148 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.topologicalSort` | 35.57GB | 125/148 | `██████░░░░░░░░░ 42%` |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 28.32GB | 139/148 | `█████░░░░░░░░░░ 33%` |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 25.23GB | 72/148 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/148 | `████░░░░░░░░░░░ 28%` |
| 10 | `reflect.growslice` | 22.61GB | 47/148 | `████░░░░░░░░░░░ 27%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
