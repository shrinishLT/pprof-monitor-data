# Overview: stage
*Last updated: 2026-05-20 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T14:32 (238 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,132 | avg: 14,323 | max: 28,205 | trend: INCREASING (+2.17/hr))
```
▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.5MB | avg: 166.5MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,132 | 14,068 | +64 | 14,323 | 28,205 | INCREASING (+2.17/hr) |
| Heap InUse | 172.5MB | 199.1MB | -26.6MB | 166.5MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1783.0MB | 1782.1MB | +0.9MB | 1227.1MB | 1783.0MB | |
| Heap Objects | 752,280 | 1,343,928 | -591648 | 862,429 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 30 | 14,128 | 181.1MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 196.73GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 122.33GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 121.6GB |
| 4 | `internal/evaluation.mergeMetadata` | 118.39GB |
| 5 | `reflect.unsafe_NewArray` | 84.94GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.09GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 61.67GB |
| 8 | `experiment/local.topologicalSort` | 60.53GB |
| 9 | `reflect.MakeSlice` | 47.39GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.56GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 236/238 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/238 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.98MB | 232/238 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/238 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/238 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/238 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 235/238 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/238 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 227/238 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/238 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.39GB | 229/238 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 57.25GB | 231/238 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 57.0GB | 230/238 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 56.72GB | 225/238 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 42.09GB | 229/238 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.69GB | 214/238 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.21GB | 227/238 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 28.89GB | 226/238 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.62GB | 227/238 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.15GB | 214/238 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
