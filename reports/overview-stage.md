# Overview: stage
*Last updated: 2026-05-20 00:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T00:30 (210 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,348 | max: 28,205 | trend: INCREASING (+4.81/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 127.4MB | avg: 164.3MB | max: 732.9MB | trend: INCREASING (+0.55MB/hr))
```
▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,067 | +4 | 14,348 | 28,205 | INCREASING (+4.81/hr) |
| Heap InUse | 127.4MB | 182.7MB | -55.3MB | 164.3MB | 732.9MB | INCREASING (+0.55MB/hr) |
| Heap Sys | 1780.2MB | 1779.2MB | +1.0MB | 1153.3MB | 1780.2MB | |
| Heap Objects | 360,886 | 1,111,324 | -750438 | 853,210 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 2 | 14,069 | 155.1MB | 182.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 171.56GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.49GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.8GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.79GB |
| 5 | `reflect.unsafe_NewArray` | 74.11GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.86GB |
| 8 | `experiment/local.topologicalSort` | 55.66GB |
| 9 | `reflect.MakeSlice` | 41.29GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 208/210 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/210 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.43MB | 204/210 | `█████░░░░░░░░░░ 36%` |
| 4 | `bytes.growSlice` | 13.35MB | 28/210 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/210 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/210 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 207/210 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 199/210 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/210 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/210 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 85.24GB | 201/210 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 48.87GB | 203/210 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 48.64GB | 202/210 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 48.56GB | 197/210 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 37.23GB | 186/210 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 36.85GB | 201/210 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.95GB | 199/210 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 24.71GB | 198/210 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 20.68GB | 199/210 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.21GB | 186/210 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
