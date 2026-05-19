# Overview: stage
*Last updated: 2026-05-19 18:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T18:30 (198 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,191 | avg: 14,362 | max: 28,205 | trend: INCREASING (+6.60/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 213.0MB | avg: 164.4MB | max: 732.9MB | trend: INCREASING (+0.67MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,191 | 14,234 | -43 | 14,362 | 28,205 | INCREASING (+6.60/hr) |
| Heap InUse | 213.0MB | 188.2MB | +24.8MB | 164.4MB | 732.9MB | INCREASING (+0.67MB/hr) |
| Heap Sys | 1776.4MB | 1774.1MB | +2.3MB | 1115.4MB | 1776.4MB | |
| Heap Objects | 1,302,780 | 943,446 | +359334 | 857,971 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 38 | 14,122 | 178.6MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `internal/evaluation.mergeMetadata` | 3.0MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `experiment/local.topologicalSort` | 2.04MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 160.83GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 109.45GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 108.69GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.78GB |
| 5 | `reflect.unsafe_NewArray` | 69.5GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.4GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 55.25GB |
| 8 | `experiment/local.topologicalSort` | 54.1GB |
| 9 | `reflect.MakeSlice` | 38.62GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 196/198 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/198 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/198 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.15MB | 192/198 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/198 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/198 | `████░░░░░░░░░░░ 27%` |
| 7 | `bufio.NewReaderSize` | 9.33MB | 18/198 | `███░░░░░░░░░░░░ 25%` |
| 8 | `internal/evaluation.mergeMetadata` | 9.25MB | 6/198 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 195/198 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 187/198 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 80.07GB | 189/198 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 44.92GB | 191/198 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.mergeMetadata` | 44.71GB | 185/198 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 44.7GB | 190/198 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.43GB | 174/198 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.62GB | 189/198 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.93GB | 187/198 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 22.74GB | 186/198 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.44GB | 187/198 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.42GB | 174/198 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
