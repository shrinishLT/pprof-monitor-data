# Overview: stage
*Last updated: 2026-05-19 23:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T23:00 (207 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,352 | max: 28,205 | trend: INCREASING (+5.26/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 138.8MB | avg: 164.2MB | max: 732.9MB | trend: INCREASING (+0.57MB/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,087 | -11 | 14,352 | 28,205 | INCREASING (+5.26/hr) |
| Heap InUse | 138.8MB | 133.0MB | +5.8MB | 164.2MB | 732.9MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1779.2MB | 1779.2MB | +0.0MB | 1144.3MB | 1779.2MB | |
| Heap Objects | 539,644 | 458,945 | +80699 | 852,484 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 47 | 14,128 | 175.0MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `aws/endpoints.init` | 2.0MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.unsafe_New` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 168.79GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 112.43GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 111.73GB |
| 4 | `internal/evaluation.mergeMetadata` | 108.73GB |
| 5 | `reflect.unsafe_NewArray` | 72.94GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.41GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 56.82GB |
| 8 | `experiment/local.topologicalSort` | 55.63GB |
| 9 | `reflect.MakeSlice` | 40.63GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 205/207 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/207 | `██████░░░░░░░░░ 42%` |
| 3 | `runtime.mallocgc` | 13.36MB | 201/207 | `█████░░░░░░░░░░ 36%` |
| 4 | `bytes.growSlice` | 13.35MB | 28/207 | `█████░░░░░░░░░░ 36%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/207 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/207 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 204/207 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 196/207 | `███░░░░░░░░░░░░ 24%` |
| 9 | `bufio.NewReaderSize` | 8.94MB | 19/207 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/207 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 83.95GB | 198/207 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 47.91GB | 200/207 | `████████░░░░░░░ 57%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 47.68GB | 199/207 | `████████░░░░░░░ 56%` |
| 4 | `internal/evaluation.mergeMetadata` | 47.63GB | 194/207 | `████████░░░░░░░ 56%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 36.8GB | 183/207 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 36.29GB | 198/207 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 24.46GB | 196/207 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 24.24GB | 195/207 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 20.37GB | 196/207 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.02GB | 183/207 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
