# Overview: stage
*Last updated: 2026-05-18 22:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T22:00 (157 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,424 | max: 28,205 | trend: INCREASING (+19.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁
```

**Heap InUse** (current: 184.5MB | avg: 160.9MB | max: 732.9MB | trend: INCREASING (+0.98MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,093 | -25 | 14,424 | 28,205 | INCREASING (+19.18/hr) |
| Heap InUse | 184.5MB | 137.7MB | +46.8MB | 160.9MB | 732.9MB | INCREASING (+0.98MB/hr) |
| Heap Sys | 1631.8MB | 1631.7MB | +0.1MB | 957.3MB | 1631.8MB | |
| Heap Objects | 1,150,488 | 505,012 | +645476 | 841,704 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 50 | 15,040 | 191.2MB | 732.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 124.34GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 97.11GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 96.25GB |
| 4 | `internal/evaluation.mergeMetadata` | 93.78GB |
| 5 | `reflect.unsafe_NewArray` | 53.78GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 49.15GB |
| 7 | `experiment/local.topologicalSort` | 47.96GB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 47.01GB |
| 9 | `reflect.MakeSlice` | 29.82GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.45GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 155/157 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/157 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 14.17MB | 26/157 | `█████░░░░░░░░░░ 38%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/157 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 11.82MB | 151/157 | `████░░░░░░░░░░░ 32%` |
| 6 | `bufio.NewReaderSize` | 10.75MB | 15/157 | `████░░░░░░░░░░░ 29%` |
| 7 | `internal/evaluation.mergeMetadata` | 10.75MB | 4/157 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/157 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.24MB | 154/157 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.94MB | 146/157 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 62.64GB | 148/157 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.15GB | 133/157 | `██████░░░░░░░░░ 46%` |
| 3 | `internal/evaluation.mergeMetadata` | 28.9GB | 144/157 | `██████░░░░░░░░░ 46%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 28.85GB | 150/157 | `██████░░░░░░░░░ 46%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 28.68GB | 149/157 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 27.08GB | 148/157 | `██████░░░░░░░░░ 43%` |
| 7 | `reflect.MakeSlice` | 15.26GB | 146/157 | `███░░░░░░░░░░░░ 24%` |
| 8 | `experiment/local.topologicalSort` | 14.68GB | 145/157 | `███░░░░░░░░░░░░ 23%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 14.64GB | 146/157 | `███░░░░░░░░░░░░ 23%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 12.69GB | 133/157 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.6x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
