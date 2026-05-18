# Overview: stage
*Last updated: 2026-05-18 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T21:32 (156 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,093 | avg: 14,426 | max: 28,205 | trend: INCREASING (+19.73/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁
```

**Heap InUse** (current: 137.7MB | avg: 160.8MB | max: 732.9MB | trend: INCREASING (+0.99MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,093 | 14,218 | -125 | 14,426 | 28,205 | INCREASING (+19.73/hr) |
| Heap InUse | 137.7MB | 161.0MB | -23.3MB | 160.8MB | 732.9MB | INCREASING (+0.99MB/hr) |
| Heap Sys | 1631.7MB | 1629.7MB | +2.0MB | 952.9MB | 1631.7MB | |
| Heap Objects | 505,012 | 574,562 | -69550 | 839,725 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 49 | 15,060 | 191.3MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 2.05MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.NewWriter` | 1.76MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 123.5GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.04GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.18GB |
| 4 | `internal/evaluation.mergeMetadata` | 93.72GB |
| 5 | `reflect.unsafe_NewArray` | 53.43GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.12GB |
| 7 | `experiment/local.topologicalSort` | 47.93GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 29.61GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 154/156 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/156 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/156 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/156 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.78MB | 150/156 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/156 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/156 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/156 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 153/156 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 145/156 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 62.22GB | 147/156 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.01GB | 132/156 | `██████░░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 28.44GB | 143/156 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.39GB | 149/156 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.23GB | 148/156 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 26.9GB | 147/156 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.16GB | 145/156 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 14.45GB | 144/156 | `███░░░░░░░░░░░░ 23%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.4GB | 145/156 | `███░░░░░░░░░░░░ 23%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.63GB | 132/156 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
