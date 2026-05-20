# Overview: stage
*Last updated: 2026-05-20 17:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T17:00 (243 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,082 | avg: 14,319 | max: 28,205 | trend: INCREASING (+1.85/hr))
```
▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 173.2MB | avg: 166.9MB | max: 732.9MB | trend: stable (+0.47MB/hr))
```
▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,082 | 14,093 | -11 | 14,319 | 28,205 | INCREASING (+1.85/hr) |
| Heap InUse | 173.2MB | 166.7MB | +6.5MB | 166.9MB | 732.9MB | stable (+0.47MB/hr) |
| Heap Sys | 1784.9MB | 1784.8MB | +0.1MB | 1238.6MB | 1784.9MB | |
| Heap Objects | 1,023,409 | 859,286 | +164123 | 868,102 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 35 | 14,127 | 182.4MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `net/http.init.func16` | 1.55MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 201.16GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 123.88GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 123.1GB |
| 4 | `internal/evaluation.mergeMetadata` | 119.85GB |
| 5 | `reflect.unsafe_NewArray` | 86.79GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 62.45GB |
| 8 | `experiment/local.topologicalSort` | 61.31GB |
| 9 | `reflect.MakeSlice` | 48.45GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 241/243 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/243 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.07MB | 237/243 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.37MB | 31/243 | `█████░░░░░░░░░░ 33%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/243 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/243 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 240/243 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/243 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 232/243 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/243 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.57GB | 234/243 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 58.65GB | 236/243 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 58.39GB | 235/243 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 58.08GB | 230/243 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 43.03GB | 234/243 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.52GB | 219/243 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 29.92GB | 232/243 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.58GB | 231/243 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.14GB | 232/243 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.51GB | 219/243 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
