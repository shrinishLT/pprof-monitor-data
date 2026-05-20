# Overview: stage
*Last updated: 2026-05-20 13:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T13:02 (235 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,325 | max: 28,205 | trend: INCREASING (+2.39/hr))
```
▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.5MB | avg: 166.3MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▁▁▁▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,524 | -451 | 14,325 | 28,205 | INCREASING (+2.39/hr) |
| Heap InUse | 193.5MB | 220.6MB | -27.1MB | 166.3MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1781.4MB | 1780.7MB | +0.7MB | 1220.1MB | 1781.4MB | |
| Heap Objects | 1,255,659 | 964,999 | +290660 | 861,377 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 27 | 14,127 | 181.1MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 193.99GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 120.51GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 119.82GB |
| 4 | `internal/evaluation.mergeMetadata` | 116.6GB |
| 5 | `reflect.unsafe_NewArray` | 83.75GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.71GB |
| 8 | `experiment/local.topologicalSort` | 59.65GB |
| 9 | `reflect.MakeSlice` | 46.75GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.39GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 233/235 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/235 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.93MB | 229/235 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/235 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/235 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/235 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 232/235 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/235 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 224/235 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/235 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.08GB | 226/235 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 56.4GB | 228/235 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 56.15GB | 227/235 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 55.9GB | 222/235 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 41.53GB | 226/235 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.19GB | 211/235 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.78GB | 224/235 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 28.46GB | 223/235 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.3GB | 224/235 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.93GB | 211/235 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
