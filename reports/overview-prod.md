# Overview: prod
*Last updated: 2026-05-18 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T20:30 (154 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,850 | avg: 15,426 | max: 84,644 | trend: decreasing (-4.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▁▁▁▁▄▁▁▁▁▁▁▃▂▁▁▁▃▁▁▁▁▃▃▃▅▁
```

**Heap InUse** (current: 256.5MB | avg: 228.3MB | max: 1896.6MB | trend: stable (+0.12MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▁▁▁▁▁▄▃▂▃▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▁▁▁▁▁▂▂▄▃▂▄▃▅▃▂▃▃▂▃▄▃▃▂▃▄▃▃▂▄▄▄▄█▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,850 | 23,165 | -8315 | 15,426 | 84,644 | decreasing (-4.58/hr) |
| Heap InUse | 256.5MB | 670.7MB | -414.2MB | 228.3MB | 1896.6MB | stable (+0.12MB/hr) |
| Heap Sys | 6560.7MB | 6557.4MB | +3.3MB | 4520.1MB | 6573.6MB | |
| Heap Objects | 894,724 | 2,919,198 | -2024474 | 985,898 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 47 | 15,720 | 262.1MB | 670.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 55.03MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 9.68MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.5MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `bufio.NewWriterSize` | 3.03MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 473.49GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 286.71GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 285.72GB |
| 4 | `experiment/local.topologicalSort` | 189.18GB |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 148.51GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 140.36GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 90.38GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 64.16GB |
| 9 | `fmt.Sprintf` | 46.9GB |
| 10 | `segmentio/kafka-go.makePartitions` | 38.91GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/154 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 152/154 | `██████████████░ 99%` |
| 3 | `runtime.mallocgc` | 26.09MB | 152/154 | `██████████░░░░░ 70%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/154 | `███████░░░░░░░░ 50%` |
| 5 | `database/sql.convertAssignRows` | 17.44MB | 8/154 | `███████░░░░░░░░ 47%` |
| 6 | `net/http.(*Transport).dialConn` | 13.17MB | 3/154 | `█████░░░░░░░░░░ 35%` |
| 7 | `bytes.growSlice` | 12.97MB | 86/154 | `█████░░░░░░░░░░ 35%` |
| 8 | `internal/evaluation.mergeMetadata` | 12.17MB | 9/154 | `████░░░░░░░░░░░ 33%` |
| 9 | `crypto/tls.Client` | 10.63MB | 4/154 | `████░░░░░░░░░░░ 28%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.7MB | 50/154 | `███░░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 98.4GB | 143/154 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 68.53GB | 147/154 | `██████████░░░░░ 69%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 57.77GB | 149/154 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 57.68GB | 149/154 | `████████░░░░░░░ 58%` |
| 5 | `experiment/local.topologicalSort` | 42.0GB | 131/154 | `██████░░░░░░░░░ 42%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 42.0GB | 99/154 | `██████░░░░░░░░░ 42%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 29.76GB | 78/154 | `████░░░░░░░░░░░ 30%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 29.75GB | 145/154 | `████░░░░░░░░░░░ 30%` |
| 9 | `fmt.(*buffer).writeString` | 24.13GB | 16/154 | `███░░░░░░░░░░░░ 24%` |
| 10 | `fmt.Sprintf` | 23.75GB | 28/154 | `███░░░░░░░░░░░░ 24%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
