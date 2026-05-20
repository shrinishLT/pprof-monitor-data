# Overview: stage
*Last updated: 2026-05-20 15:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T15:02 (239 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,322 | max: 28,205 | trend: INCREASING (+2.09/hr))
```
▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 179.8MB | avg: 166.5MB | max: 732.9MB | trend: stable (+0.47MB/hr))
```
▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,132 | -67 | 14,322 | 28,205 | INCREASING (+2.09/hr) |
| Heap InUse | 179.8MB | 172.5MB | +7.3MB | 166.5MB | 732.9MB | stable (+0.47MB/hr) |
| Heap Sys | 1783.2MB | 1783.0MB | +0.2MB | 1229.5MB | 1783.2MB | |
| Heap Objects | 1,104,307 | 752,280 | +352027 | 863,441 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 31 | 14,126 | 181.1MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 197.6GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 122.49GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 121.78GB |
| 4 | `internal/evaluation.mergeMetadata` | 118.54GB |
| 5 | `reflect.unsafe_NewArray` | 85.3GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.75GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 61.74GB |
| 8 | `experiment/local.topologicalSort` | 60.62GB |
| 9 | `reflect.MakeSlice` | 47.6GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.84GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 237/239 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/239 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.0MB | 233/239 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/239 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/239 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/239 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 236/239 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/239 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 228/239 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/239 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.82GB | 230/239 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 57.53GB | 232/239 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 57.28GB | 231/239 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 57.0GB | 226/239 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 42.28GB | 230/239 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.86GB | 215/239 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.36GB | 228/239 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.03GB | 227/239 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.72GB | 228/239 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.22GB | 215/239 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
