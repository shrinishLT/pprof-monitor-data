# Overview: stage
*Last updated: 2026-05-19 03:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T03:33 (168 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,062 | avg: 14,402 | max: 28,205 | trend: INCREASING (+14.20/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 156.4MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+0.80MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,062 | 14,090 | -28 | 14,402 | 28,205 | INCREASING (+14.20/hr) |
| Heap InUse | 156.4MB | 169.6MB | -13.2MB | 160.9MB | 732.9MB | INCREASING (+0.80MB/hr) |
| Heap Sys | 1634.0MB | 1633.8MB | +0.2MB | 1001.5MB | 1634.4MB | |
| Heap Objects | 782,253 | 882,392 | -100139 | 836,460 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 8 | 14,076 | 157.2MB | 197.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `reflect.mapassign_faststr0` | 3.0MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.05MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 134.16GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 100.75GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 99.88GB |
| 4 | `internal/evaluation.mergeMetadata` | 97.31GB |
| 5 | `reflect.unsafe_NewArray` | 58.02GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.02GB |
| 7 | `experiment/local.topologicalSort` | 49.77GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 32.19GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 166/168 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/168 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/168 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/168 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.24MB | 162/168 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/168 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/168 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/168 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 165/168 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 157/168 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 67.28GB | 159/168 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 33.61GB | 161/168 | `███████░░░░░░░░ 49%` |
| 3 | `internal/evaluation.mergeMetadata` | 33.6GB | 155/168 | `███████░░░░░░░░ 49%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.43GB | 160/168 | `███████░░░░░░░░ 49%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.51GB | 144/168 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 29.09GB | 159/168 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.11GB | 157/168 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 17.07GB | 156/168 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.37GB | 157/168 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.28GB | 144/168 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
