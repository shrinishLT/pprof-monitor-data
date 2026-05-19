# Overview: stage
*Last updated: 2026-05-19 22:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T22:00 (205 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,355 | max: 28,205 | trend: INCREASING (+5.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 136.5MB | avg: 164.5MB | max: 732.9MB | trend: INCREASING (+0.61MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,191 | -115 | 14,355 | 28,205 | INCREASING (+5.58/hr) |
| Heap InUse | 136.5MB | 174.6MB | -38.1MB | 164.5MB | 732.9MB | INCREASING (+0.61MB/hr) |
| Heap Sys | 1779.1MB | 1778.9MB | +0.2MB | 1138.1MB | 1779.1MB | |
| Heap Objects | 482,124 | 729,022 | -246898 | 855,929 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 45 | 14,130 | 176.8MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 167.07GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.62GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.62GB |
| 5 | `reflect.unsafe_NewArray` | 72.23GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.77GB |
| 8 | `experiment/local.topologicalSort` | 55.58GB |
| 9 | `reflect.MakeSlice` | 40.19GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 203/205 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/205 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/205 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.32MB | 199/205 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/205 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/205 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 202/205 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 194/205 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/205 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/205 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 83.09GB | 196/205 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 47.26GB | 198/205 | `████████░░░░░░░ 56%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 47.03GB | 197/205 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.mergeMetadata` | 46.99GB | 192/205 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 36.51GB | 181/205 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 35.92GB | 196/205 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.13GB | 194/205 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 23.91GB | 193/205 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 20.16GB | 194/205 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.89GB | 181/205 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
