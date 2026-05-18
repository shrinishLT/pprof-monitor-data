# Overview: stage
*Last updated: 2026-05-18 21:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T21:02 (155 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,218 | avg: 14,428 | max: 28,205 | trend: INCREASING (+20.28/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁
```

**Heap InUse** (current: 161.0MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+1.02MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,218 | 14,218 | +0 | 14,428 | 28,205 | INCREASING (+20.28/hr) |
| Heap InUse | 161.0MB | 136.2MB | +24.8MB | 160.9MB | 732.9MB | INCREASING (+1.02MB/hr) |
| Heap Sys | 1629.7MB | 1629.6MB | +0.1MB | 948.6MB | 1629.7MB | |
| Heap Objects | 574,562 | 396,433 | +178129 | 841,884 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 48 | 15,080 | 192.4MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 7.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 122.66GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 95.81GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 94.94GB |
| 4 | `internal/evaluation.mergeMetadata` | 92.48GB |
| 5 | `reflect.unsafe_NewArray` | 53.03GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.47GB |
| 7 | `experiment/local.topologicalSort` | 47.31GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.0GB |
| 9 | `reflect.MakeSlice` | 29.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 153/155 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/155 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/155 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/155 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.74MB | 149/155 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/155 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/155 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/155 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 152/155 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 144/155 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 61.8GB | 146/155 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 28.87GB | 131/155 | `███████░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 27.98GB | 142/155 | `██████░░░░░░░░░ 45%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 27.92GB | 148/155 | `██████░░░░░░░░░ 45%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 27.77GB | 147/155 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 26.72GB | 146/155 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.06GB | 144/155 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 14.21GB | 143/155 | `███░░░░░░░░░░░░ 22%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.16GB | 144/155 | `███░░░░░░░░░░░░ 22%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.57GB | 131/155 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
