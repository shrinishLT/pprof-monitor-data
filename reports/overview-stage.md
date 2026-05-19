# Overview: stage
*Last updated: 2026-05-20 03:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T03:02 (215 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,343 | max: 28,205 | trend: INCREASING (+4.21/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 190.1MB | avg: 164.5MB | max: 732.9MB | trend: INCREASING (+0.53MB/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,089 | -25 | 14,343 | 28,205 | INCREASING (+4.21/hr) |
| Heap InUse | 190.1MB | 204.5MB | -14.4MB | 164.5MB | 732.9MB | INCREASING (+0.53MB/hr) |
| Heap Sys | 1779.8MB | 1779.4MB | +0.4MB | 1167.9MB | 1780.2MB | |
| Heap Objects | 1,193,094 | 1,320,252 | -127158 | 855,377 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 7 | 14,116 | 169.7MB | 204.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 176.18GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 115.43GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 114.76GB |
| 4 | `internal/evaluation.mergeMetadata` | 111.67GB |
| 5 | `reflect.unsafe_NewArray` | 76.11GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.38GB |
| 8 | `experiment/local.topologicalSort` | 57.09GB |
| 9 | `reflect.MakeSlice` | 42.43GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 213/215 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/215 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.54MB | 209/215 | `█████░░░░░░░░░░ 36%` |
| 4 | `bytes.growSlice` | 12.98MB | 29/215 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/215 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/215 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 212/215 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 204/215 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/215 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/215 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 87.4GB | 206/215 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 50.43GB | 208/215 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 50.19GB | 207/215 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 50.08GB | 202/215 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 37.92GB | 191/215 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 37.79GB | 206/215 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.74GB | 204/215 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 25.49GB | 203/215 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 21.2GB | 204/215 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.51GB | 191/215 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
