# Overview: stage
*Last updated: 2026-05-20 01:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T01:00 (211 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,347 | max: 28,205 | trend: INCREASING (+4.67/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 128.0MB | avg: 164.1MB | max: 732.9MB | trend: INCREASING (+0.53MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,071 | -4 | 14,347 | 28,205 | INCREASING (+4.67/hr) |
| Heap InUse | 128.0MB | 127.4MB | +0.6MB | 164.1MB | 732.9MB | INCREASING (+0.53MB/hr) |
| Heap Sys | 1780.2MB | 1780.2MB | +0.0MB | 1156.3MB | 1780.2MB | |
| Heap Objects | 349,070 | 360,886 | -11816 | 850,821 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 3 | 14,068 | 146.0MB | 182.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.unsafe_NewArray` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 172.46GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.53GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.83GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.83GB |
| 5 | `reflect.unsafe_NewArray` | 74.52GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.88GB |
| 8 | `experiment/local.topologicalSort` | 55.68GB |
| 9 | `reflect.MakeSlice` | 41.52GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 209/211 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/211 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.45MB | 205/211 | `█████░░░░░░░░░░ 36%` |
| 4 | `bytes.growSlice` | 13.35MB | 28/211 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/211 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/211 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 208/211 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 200/211 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/211 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/211 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 85.67GB | 202/211 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 49.18GB | 204/211 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 48.95GB | 203/211 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 48.86GB | 198/211 | `████████░░░░░░░ 57%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 37.37GB | 187/211 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 37.04GB | 202/211 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 25.11GB | 200/211 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 24.87GB | 199/211 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 20.79GB | 200/211 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.27GB | 187/211 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
