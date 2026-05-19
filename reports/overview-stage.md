# Overview: stage
*Last updated: 2026-05-19 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T06:00 (173 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,421 | avg: 14,395 | max: 28,205 | trend: INCREASING (+12.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 293.9MB | avg: 161.8MB | max: 732.9MB | trend: INCREASING (+0.79MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,421 | 14,067 | +354 | 14,395 | 28,205 | INCREASING (+12.50/hr) |
| Heap InUse | 293.9MB | 168.4MB | +125.5MB | 161.8MB | 732.9MB | INCREASING (+0.79MB/hr) |
| Heap Sys | 1750.0MB | 1634.3MB | +115.7MB | 1020.5MB | 1750.0MB | |
| Heap Objects | 1,234,562 | 933,299 | +301263 | 839,453 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 13 | 14,100 | 170.6MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `bytes.growSlice` | 2.51MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.05MB |
| 10 | `bufio.NewReaderSize` | 2.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 138.55GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 101.63GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 100.78GB |
| 4 | `internal/evaluation.mergeMetadata` | 98.21GB |
| 5 | `reflect.unsafe_NewArray` | 59.92GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.48GB |
| 7 | `experiment/local.topologicalSort` | 50.21GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 49.36GB |
| 9 | `reflect.MakeSlice` | 33.27GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.48GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 171/173 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/173 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/173 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/173 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.42MB | 167/173 | `█████░░░░░░░░░░ 33%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/173 | `████░░░░░░░░░░░ 28%` |
| 7 | `bufio.NewReaderSize` | 10.21MB | 16/173 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/173 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 170/173 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 162/173 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 69.4GB | 164/173 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 35.64GB | 166/173 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 35.61GB | 160/173 | `███████░░░░░░░░ 51%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 35.46GB | 165/173 | `███████░░░░░░░░ 51%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 31.08GB | 149/173 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.0GB | 164/173 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.17GB | 162/173 | `███░░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 18.1GB | 161/173 | `███░░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 16.88GB | 162/173 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.53GB | 149/173 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
