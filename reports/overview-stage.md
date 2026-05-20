# Overview: stage
*Last updated: 2026-05-20 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T12:30 (234 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,524 | avg: 14,326 | max: 28,205 | trend: INCREASING (+2.47/hr))
```
▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 220.6MB | avg: 166.2MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▁▁▁▁▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,524 | 14,065 | +459 | 14,326 | 28,205 | INCREASING (+2.47/hr) |
| Heap InUse | 220.6MB | 206.5MB | +14.1MB | 166.2MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1780.7MB | 1781.2MB | -0.5MB | 1217.7MB | 1781.2MB | |
| Heap Objects | 964,999 | 1,441,544 | -476545 | 859,693 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 26 | 14,130 | 180.6MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `bufio.NewWriterSize` | 3.54MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 193.09GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 120.18GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 119.51GB |
| 4 | `internal/evaluation.mergeMetadata` | 116.29GB |
| 5 | `reflect.unsafe_NewArray` | 83.36GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.12GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.55GB |
| 8 | `experiment/local.topologicalSort` | 59.49GB |
| 9 | `reflect.MakeSlice` | 46.54GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 232/234 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/234 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.91MB | 228/234 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/234 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/234 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/234 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 231/234 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/234 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 223/234 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/234 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.65GB | 225/234 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 56.12GB | 227/234 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 55.87GB | 226/234 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 55.62GB | 221/234 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 41.34GB | 225/234 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.02GB | 210/234 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.64GB | 223/234 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 28.32GB | 222/234 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.2GB | 223/234 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86GB | 210/234 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
