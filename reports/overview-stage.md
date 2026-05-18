# Overview: stage
*Last updated: 2026-05-19 02:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T02:32 (166 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,406 | max: 28,205 | trend: INCREASING (+15.01/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 126.6MB | avg: 160.8MB | max: 732.9MB | trend: INCREASING (+0.82MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,067 | +0 | 14,406 | 28,205 | INCREASING (+15.01/hr) |
| Heap InUse | 126.6MB | 150.7MB | -24.1MB | 160.8MB | 732.9MB | INCREASING (+0.82MB/hr) |
| Heap Sys | 1633.8MB | 1633.6MB | +0.2MB | 993.9MB | 1634.4MB | |
| Heap Objects | 355,170 | 711,700 | -356530 | 836,510 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 6 | 14,076 | 155.3MB | 197.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 132.35GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 100.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 99.47GB |
| 4 | `internal/evaluation.mergeMetadata` | 96.91GB |
| 5 | `reflect.unsafe_NewArray` | 57.25GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 50.82GB |
| 7 | `experiment/local.topologicalSort` | 49.57GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 31.75GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 164/166 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/166 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/166 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/166 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.17MB | 160/166 | `████░░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/166 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/166 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/166 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 163/166 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 155/166 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 66.43GB | 157/166 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 32.77GB | 153/166 | `███████░░░░░░░░ 49%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 32.76GB | 159/166 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 32.59GB | 158/166 | `███████░░░░░░░░ 49%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.28GB | 142/166 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 28.72GB | 157/166 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.68GB | 155/166 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 16.65GB | 154/166 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.17GB | 155/166 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.18GB | 142/166 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
