# Overview: stage
*Last updated: 2026-05-20 20:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T20:02 (249 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,263 | avg: 14,316 | max: 28,205 | trend: INCREASING (+1.57/hr))
```
▃▃▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆▅▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▆▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▂▁▁▁▁▂▅▂▄
```

**Heap InUse** (current: 152.8MB | avg: 167.2MB | max: 732.9MB | trend: stable (+0.45MB/hr))
```
▁▁▁▂▃▁▁▂▁▃▁▁▁▂▁▁▃▁▂▅▅▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▂▂▃▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,263 | 14,153 | +110 | 14,316 | 28,205 | INCREASING (+1.57/hr) |
| Heap InUse | 152.8MB | 199.6MB | -46.8MB | 167.2MB | 732.9MB | stable (+0.45MB/hr) |
| Heap Sys | 1787.8MB | 1788.0MB | -0.2MB | 1251.8MB | 1788.0MB | |
| Heap Objects | 559,457 | 1,262,515 | -703058 | 868,224 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 41 | 14,137 | 181.4MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 2.16MB |
| 9 | `bufio.NewReaderSize` | 2.02MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 206.71GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 127.4GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 126.59GB |
| 4 | `internal/evaluation.mergeMetadata` | 123.24GB |
| 5 | `reflect.unsafe_NewArray` | 89.14GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 64.24GB |
| 8 | `experiment/local.topologicalSort` | 63.03GB |
| 9 | `reflect.MakeSlice` | 49.79GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 247/249 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/249 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.17MB | 243/249 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.03MB | 32/249 | `████░░░░░░░░░░░ 32%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/249 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/249 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 246/249 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/249 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 238/249 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/249 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.19GB | 240/249 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 60.31GB | 242/249 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 60.05GB | 241/249 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 59.7GB | 236/249 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 44.16GB | 240/249 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.49GB | 225/249 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.77GB | 238/249 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 30.41GB | 237/249 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.78GB | 238/249 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.93GB | 225/249 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
