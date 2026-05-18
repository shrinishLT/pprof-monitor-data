# Overview: stage
*Last updated: 2026-05-18 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T22:30 (158 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,271 | avg: 14,423 | max: 28,205 | trend: INCREASING (+18.75/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁
```

**Heap InUse** (current: 214.5MB | avg: 161.3MB | max: 732.9MB | trend: INCREASING (+0.99MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,271 | 14,068 | +203 | 14,423 | 28,205 | INCREASING (+18.75/hr) |
| Heap InUse | 214.5MB | 184.5MB | +30.0MB | 161.3MB | 732.9MB | INCREASING (+0.99MB/hr) |
| Heap Sys | 1633.0MB | 1631.8MB | +1.2MB | 961.5MB | 1633.0MB | |
| Heap Objects | 1,024,088 | 1,150,488 | -126400 | 842,859 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 51 | 15,025 | 191.6MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `internal/evaluation.mergeMetadata` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 7 | `experiment/local.(*Client).EvaluateV2` | 4.84MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 3.78MB |
| 9 | `reflect.mapassign_faststr0` | 2.5MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 125.25GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.68GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.83GB |
| 4 | `internal/evaluation.mergeMetadata` | 94.33GB |
| 5 | `reflect.unsafe_NewArray` | 54.16GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.47GB |
| 7 | `experiment/local.topologicalSort` | 48.25GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 30.04GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 156/158 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/158 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/158 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/158 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.87MB | 152/158 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/158 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/158 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/158 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 155/158 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 147/158 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 63.06GB | 149/158 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 29.35GB | 145/158 | `██████░░░░░░░░░ 46%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 29.3GB | 151/158 | `██████░░░░░░░░░ 46%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 29.28GB | 134/158 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 29.14GB | 150/158 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 27.26GB | 149/158 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.36GB | 147/158 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 14.91GB | 146/158 | `███░░░░░░░░░░░░ 23%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.88GB | 147/158 | `███░░░░░░░░░░░░ 23%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.75GB | 134/158 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
