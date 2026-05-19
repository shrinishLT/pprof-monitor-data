# Overview: stage
*Last updated: 2026-05-19 22:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T22:30 (206 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,087 | avg: 14,354 | max: 28,205 | trend: INCREASING (+5.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 133.0MB | avg: 164.3MB | max: 732.9MB | trend: INCREASING (+0.59MB/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,087 | 14,076 | +11 | 14,354 | 28,205 | INCREASING (+5.42/hr) |
| Heap InUse | 133.0MB | 136.5MB | -3.5MB | 164.3MB | 732.9MB | INCREASING (+0.59MB/hr) |
| Heap Sys | 1779.2MB | 1779.1MB | +0.1MB | 1141.2MB | 1779.2MB | |
| Heap Objects | 458,945 | 482,124 | -23179 | 854,002 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 46 | 14,129 | 175.8MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 167.93GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.4GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.69GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.69GB |
| 5 | `reflect.unsafe_NewArray` | 72.58GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.8GB |
| 8 | `experiment/local.topologicalSort` | 55.61GB |
| 9 | `reflect.MakeSlice` | 40.4GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 204/206 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/206 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/206 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.34MB | 200/206 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/206 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/206 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 203/206 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 195/206 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/206 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/206 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 83.52GB | 197/206 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 47.59GB | 199/206 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 47.36GB | 198/206 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.mergeMetadata` | 47.31GB | 193/206 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 36.66GB | 182/206 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 36.11GB | 197/206 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.29GB | 195/206 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 24.07GB | 194/206 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 20.27GB | 195/206 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.96GB | 182/206 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
