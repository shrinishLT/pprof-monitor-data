# Overview: stage
*Last updated: 2026-05-20 15:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T15:30 (240 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,257 | avg: 14,322 | max: 28,205 | trend: INCREASING (+2.05/hr))
```
▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 203.7MB | avg: 166.7MB | max: 732.9MB | trend: stable (+0.47MB/hr))
```
▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,257 | 14,065 | +192 | 14,322 | 28,205 | INCREASING (+2.05/hr) |
| Heap InUse | 203.7MB | 179.8MB | +23.9MB | 166.7MB | 732.9MB | stable (+0.47MB/hr) |
| Heap Sys | 1783.5MB | 1783.2MB | +0.3MB | 1231.8MB | 1783.5MB | |
| Heap Objects | 1,256,996 | 1,104,307 | +152689 | 865,081 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 32 | 14,130 | 181.8MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 198.45GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 123.05GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 122.29GB |
| 4 | `internal/evaluation.mergeMetadata` | 119.09GB |
| 5 | `reflect.unsafe_NewArray` | 85.66GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 77.75GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 62.05GB |
| 8 | `experiment/local.topologicalSort` | 60.9GB |
| 9 | `reflect.MakeSlice` | 47.81GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.84GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 238/240 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/240 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.02MB | 234/240 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/240 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/240 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/240 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 237/240 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/240 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 229/240 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/240 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.26GB | 231/240 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 57.81GB | 233/240 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 57.56GB | 232/240 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 57.27GB | 227/240 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 42.47GB | 231/240 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.02GB | 216/240 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.5GB | 229/240 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.17GB | 228/240 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 23.83GB | 229/240 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.29GB | 216/240 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
