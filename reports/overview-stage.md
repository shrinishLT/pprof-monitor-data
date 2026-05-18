# Overview: stage
*Last updated: 2026-05-19 04:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T04:01 (169 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,400 | max: 28,205 | trend: INCREASING (+13.82/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 130.0MB | avg: 160.7MB | max: 732.9MB | trend: INCREASING (+0.77MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,062 | +11 | 14,400 | 28,205 | INCREASING (+13.82/hr) |
| Heap InUse | 130.0MB | 156.4MB | -26.4MB | 160.7MB | 732.9MB | INCREASING (+0.77MB/hr) |
| Heap Sys | 1635.0MB | 1634.0MB | +1.0MB | 1005.3MB | 1635.0MB | |
| Heap Objects | 306,619 | 782,253 | -475634 | 833,325 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 9 | 14,075 | 154.2MB | 197.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 134.96GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 100.83GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 99.96GB |
| 4 | `internal/evaluation.mergeMetadata` | 97.39GB |
| 5 | `reflect.unsafe_NewArray` | 58.38GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 51.07GB |
| 7 | `experiment/local.topologicalSort` | 49.81GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 32.38GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 167/169 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/169 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/169 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/169 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.28MB | 163/169 | `█████░░░░░░░░░░ 33%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/169 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/169 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/169 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 166/169 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 158/169 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 67.7GB | 160/169 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 34.02GB | 162/169 | `███████░░░░░░░░ 50%` |
| 3 | `internal/evaluation.mergeMetadata` | 34.01GB | 156/169 | `███████░░░░░░░░ 50%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 33.84GB | 161/169 | `███████░░░░░░░░ 49%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 30.62GB | 145/169 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 29.27GB | 160/169 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 17.33GB | 158/169 | `███░░░░░░░░░░░░ 25%` |
| 8 | `experiment/local.topologicalSort` | 17.28GB | 157/169 | `███░░░░░░░░░░░░ 25%` |
| 9 | `reflect.MakeSlice` | 16.47GB | 158/169 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.33GB | 145/169 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
