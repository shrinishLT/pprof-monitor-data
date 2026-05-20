# Overview: stage
*Last updated: 2026-05-20 09:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T09:02 (227 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,332 | max: 28,205 | trend: INCREASING (+3.02/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 149.9MB | avg: 166.0MB | max: 732.9MB | trend: INCREASING (+0.52MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▁▁▃▂▁▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,067 | +10 | 14,332 | 28,205 | INCREASING (+3.02/hr) |
| Heap InUse | 149.9MB | 160.3MB | -10.4MB | 166.0MB | 732.9MB | INCREASING (+0.52MB/hr) |
| Heap Sys | 1781.1MB | 1780.9MB | +0.2MB | 1200.3MB | 1781.1MB | |
| Heap Objects | 708,609 | 832,070 | -123461 | 860,469 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 19 | 14,125 | 184.0MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.unsafe_NewArray` | 3.02MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 186.84GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 119.64GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 118.95GB |
| 4 | `internal/evaluation.mergeMetadata` | 115.76GB |
| 5 | `reflect.unsafe_NewArray` | 80.67GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.12GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.28GB |
| 8 | `experiment/local.topologicalSort` | 59.24GB |
| 9 | `reflect.MakeSlice` | 45.04GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 225/227 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/227 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.78MB | 221/227 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/227 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/227 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/227 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 224/227 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/227 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 216/227 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.67MB | 20/227 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.6GB | 218/227 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 54.09GB | 220/227 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 53.85GB | 219/227 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 53.65GB | 214/227 | `████████░░░░░░░ 57%` |
| 5 | `reflect.unsafe_NewArray` | 40.03GB | 218/227 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.81GB | 203/227 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 27.61GB | 216/227 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 27.31GB | 215/227 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 22.46GB | 216/227 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.33GB | 203/227 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
