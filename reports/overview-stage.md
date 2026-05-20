# Overview: stage
*Last updated: 2026-05-20 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T18:02 (245 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,317 | max: 28,205 | trend: INCREASING (+1.71/hr))
```
█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 171.6MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.47MB/hr))
```
█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,119 | -46 | 14,317 | 28,205 | INCREASING (+1.71/hr) |
| Heap InUse | 171.6MB | 207.1MB | -35.5MB | 167.1MB | 732.9MB | stable (+0.47MB/hr) |
| Heap Sys | 1786.0MB | 1785.8MB | +0.2MB | 1243.1MB | 1786.0MB | |
| Heap Objects | 945,629 | 1,074,570 | -128941 | 869,262 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 37 | 14,126 | 182.7MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 203.06GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 124.79GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 123.98GB |
| 4 | `internal/evaluation.mergeMetadata` | 120.75GB |
| 5 | `reflect.unsafe_NewArray` | 87.58GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 62.89GB |
| 8 | `experiment/local.topologicalSort` | 61.74GB |
| 9 | `reflect.MakeSlice` | 48.9GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 243/245 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/245 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.1MB | 239/245 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.37MB | 31/245 | `█████░░░░░░░░░░ 33%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/245 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/245 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 242/245 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/245 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 234/245 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/245 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.44GB | 236/245 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 59.2GB | 238/245 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 58.94GB | 237/245 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 58.62GB | 232/245 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 43.41GB | 236/245 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.85GB | 221/245 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.21GB | 234/245 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.86GB | 233/245 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.35GB | 234/245 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.65GB | 221/245 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
