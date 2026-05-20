# Overview: stage
*Last updated: 2026-05-20 14:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T14:00 (237 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,324 | max: 28,205 | trend: INCREASING (+2.24/hr))
```
▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 199.1MB | avg: 166.4MB | max: 732.9MB | trend: stable (+0.48MB/hr))
```
▁▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,189 | -121 | 14,324 | 28,205 | INCREASING (+2.24/hr) |
| Heap InUse | 199.1MB | 174.1MB | +25.0MB | 166.4MB | 732.9MB | stable (+0.48MB/hr) |
| Heap Sys | 1782.1MB | 1781.8MB | +0.3MB | 1224.8MB | 1782.1MB | |
| Heap Objects | 1,343,928 | 738,249 | +605679 | 862,894 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 29 | 14,127 | 181.4MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.mapassign_faststr0` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 2.14MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 195.74GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 121.62GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 120.91GB |
| 4 | `internal/evaluation.mergeMetadata` | 117.66GB |
| 5 | `reflect.unsafe_NewArray` | 84.5GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.09GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 61.31GB |
| 8 | `experiment/local.topologicalSort` | 60.18GB |
| 9 | `reflect.MakeSlice` | 47.15GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.56GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 235/237 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/237 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.97MB | 231/237 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/237 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/237 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/237 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 234/237 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/237 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 226/237 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/237 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.95GB | 228/237 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 56.96GB | 230/237 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 56.71GB | 229/237 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 56.45GB | 224/237 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 41.91GB | 228/237 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.52GB | 213/237 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.07GB | 226/237 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 28.75GB | 225/237 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.51GB | 226/237 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.08GB | 213/237 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
