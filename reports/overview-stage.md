# Overview: stage
*Last updated: 2026-05-20 19:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T19:30 (248 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,153 | avg: 14,316 | max: 28,205 | trend: INCREASING (+1.60/hr))
```
▁▃▃▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂
```

**Heap InUse** (current: 199.6MB | avg: 167.2MB | max: 732.9MB | trend: stable (+0.46MB/hr))
```
▁▁▁▁▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,153 | 14,355 | -202 | 14,316 | 28,205 | INCREASING (+1.60/hr) |
| Heap InUse | 199.6MB | 163.8MB | +35.8MB | 167.2MB | 732.9MB | stable (+0.46MB/hr) |
| Heap Sys | 1788.0MB | 1787.0MB | +1.0MB | 1249.7MB | 1788.0MB | |
| Heap Objects | 1,262,515 | 635,258 | +627257 | 869,469 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 40 | 14,134 | 182.2MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 205.72GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 127.08GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 126.27GB |
| 4 | `internal/evaluation.mergeMetadata` | 122.94GB |
| 5 | `reflect.unsafe_NewArray` | 88.71GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 64.08GB |
| 8 | `experiment/local.topologicalSort` | 62.88GB |
| 9 | `reflect.MakeSlice` | 49.55GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 246/248 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/248 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.15MB | 242/248 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.03MB | 32/248 | `████░░░░░░░░░░░ 32%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/248 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/248 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 245/248 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/248 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 237/248 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/248 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.75GB | 239/248 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 60.03GB | 241/248 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 59.77GB | 240/248 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 59.43GB | 235/248 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 43.97GB | 239/248 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.33GB | 224/248 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.63GB | 237/248 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.27GB | 236/248 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.67GB | 237/248 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.86GB | 224/248 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
