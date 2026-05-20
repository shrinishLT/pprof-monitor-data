# Overview: stage
*Last updated: 2026-05-20 11:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T11:01 (231 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,121 | avg: 14,328 | max: 28,205 | trend: INCREASING (+2.64/hr))
```
▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.4MB | avg: 165.9MB | max: 732.9MB | trend: stable (+0.49MB/hr))
```
▁▁▁▁▁▁▁▂▂▂▁▁▆▁█▅▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,121 | 14,067 | +54 | 14,328 | 28,205 | INCREASING (+2.64/hr) |
| Heap InUse | 160.4MB | 135.2MB | +25.2MB | 165.9MB | 732.9MB | stable (+0.49MB/hr) |
| Heap Sys | 1781.2MB | 1781.2MB | +0.0MB | 1210.3MB | 1781.2MB | |
| Heap Objects | 732,075 | 494,393 | +237682 | 858,501 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 23 | 14,118 | 179.8MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `reflect.unsafe_NewArray` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `internal/sync.runtime_SemacquireMutex` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 190.34GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 119.83GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 119.15GB |
| 4 | `internal/evaluation.mergeMetadata` | 115.94GB |
| 5 | `reflect.unsafe_NewArray` | 82.21GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 76.12GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 60.37GB |
| 8 | `experiment/local.topologicalSort` | 59.33GB |
| 9 | `reflect.MakeSlice` | 45.9GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.13GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 229/231 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/231 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.86MB | 225/231 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/231 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/231 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/231 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 228/231 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/231 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 220/231 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.67MB | 20/231 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.34GB | 222/231 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 55.26GB | 224/231 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 55.02GB | 223/231 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 54.79GB | 218/231 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 40.78GB | 222/231 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.51GB | 207/231 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 28.21GB | 220/231 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 27.9GB | 219/231 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 22.88GB | 220/231 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.64GB | 207/231 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
