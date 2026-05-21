# Overview: prod
*Last updated: 2026-05-21 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T20:30 (315 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,963 | avg: 15,765 | max: 84,644 | trend: INCREASING (+8.62/hr))
```
▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▃▁▂█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁
```

**Heap InUse** (current: 228.5MB | avg: 241.4MB | max: 1896.6MB | trend: stable (+0.36MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▇▂▂▁▁▁▁▁▁▁▁▂▁▃▁▁▁▂▁▂▄▂▂█▁▁▂▁▁▂▂▁▄▂▁▁▂▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▂▃▁▂▁▁▂▁▁▂▂▃▁▁▃▃▁▁▁▂▂▂▁▂▂▂▃▃▃▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,963 | 15,861 | -898 | 15,765 | 84,644 | INCREASING (+8.62/hr) |
| Heap InUse | 228.5MB | 292.9MB | -64.4MB | 241.4MB | 1896.6MB | stable (+0.36MB/hr) |
| Heap Sys | 4878.8MB | 4876.6MB | +2.2MB | 4257.9MB | 6579.6MB | |
| Heap Objects | 845,959 | 1,106,416 | -260457 | 1,015,368 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 59 | 16,041 | 266.8MB | 501.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 35.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 7.0MB |
| 5 | `bytes.growSlice` | 5.53MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 9 | `bufio.NewWriterSize` | 3.03MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 215.39GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 129.22GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 128.88GB |
| 4 | `experiment/local.topologicalSort` | 85.34GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 67.33GB |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 40.95GB |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 29.87GB |
| 8 | `fmt.Sprintf` | 22.53GB |
| 9 | `internal/evaluation.coerceString` | 13.96GB |
| 10 | `segmentio/kafka-go.makePartitions` | 13.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 58.01MB | 8/315 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 46.22MB | 14/315 | `███████████░░░░ 79%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 313/315 | `█████████░░░░░░ 63%` |
| 4 | `database/sql.convertAssignRows` | 32.63MB | 16/315 | `████████░░░░░░░ 56%` |
| 5 | `runtime.mallocgc` | 24.82MB | 313/315 | `██████░░░░░░░░░ 42%` |
| 6 | `bytes.growSlice` | 13.85MB | 224/315 | `███░░░░░░░░░░░░ 23%` |
| 7 | `net/http.(*Transport).dialConn` | 13.7MB | 5/315 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.84MB | 6/315 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/315 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.66MB | 46/315 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 115.66GB | 304/315 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 68.68GB | 310/315 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 68.66GB | 310/315 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 53.18GB | 291/315 | `██████░░░░░░░░░ 45%` |
| 5 | `experiment/local.topologicalSort` | 47.63GB | 292/315 | `██████░░░░░░░░░ 41%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 41.45GB | 260/315 | `█████░░░░░░░░░░ 35%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 26.84GB | 236/315 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 25.94GB | 255/315 | `███░░░░░░░░░░░░ 22%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/315 | `███░░░░░░░░░░░░ 20%` |
| 10 | `segmentio/kafka-go.makePartitions` | 17.32GB | 158/315 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
