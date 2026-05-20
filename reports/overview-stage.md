# Overview: stage
*Last updated: 2026-05-20 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T06:31 (222 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,355 | avg: 14,338 | max: 28,205 | trend: INCREASING (+3.53/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 220.8MB | avg: 166.2MB | max: 732.9MB | trend: INCREASING (+0.57MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▁▁▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,355 | 14,427 | -72 | 14,338 | 28,205 | INCREASING (+3.53/hr) |
| Heap InUse | 220.8MB | 369.4MB | -148.6MB | 166.2MB | 732.9MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1780.6MB | 1780.2MB | +0.4MB | 1187.2MB | 1780.6MB | |
| Heap Objects | 904,842 | 1,146,340 | -241498 | 862,912 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 14 | 14,139 | 194.5MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 4.5MB |
| 6 | `bufio.NewReaderSize` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 2.54MB |
| 8 | `database/sql.convertAssignRows` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 182.35GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 118.97GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 118.31GB |
| 4 | `internal/evaluation.mergeMetadata` | 115.09GB |
| 5 | `reflect.unsafe_NewArray` | 78.79GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 75.82GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 59.97GB |
| 8 | `experiment/local.topologicalSort` | 58.93GB |
| 9 | `reflect.MakeSlice` | 43.94GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 33.0GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 220/222 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/222 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 13.69MB | 216/222 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/222 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/222 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/222 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 219/222 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/222 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 211/222 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.67MB | 20/222 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.43GB | 213/222 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 52.57GB | 215/222 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 52.33GB | 214/222 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 52.17GB | 209/222 | `████████░░░░░░░ 57%` |
| 5 | `reflect.unsafe_NewArray` | 39.09GB | 213/222 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.89GB | 198/222 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.84GB | 211/222 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 26.56GB | 210/222 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 21.94GB | 211/222 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.93GB | 198/222 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
