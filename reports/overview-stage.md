# Overview: stage
*Last updated: 2026-05-20 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T06:00 (221 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,427 | avg: 14,338 | max: 28,205 | trend: INCREASING (+3.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 369.4MB | avg: 166.0MB | max: 732.9MB | trend: INCREASING (+0.57MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▂▁▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 20%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,427 | 14,067 | +360 | 14,338 | 28,205 | INCREASING (+3.58/hr) |
| Heap InUse | 369.4MB | 195.9MB | +173.5MB | 166.0MB | 732.9MB | INCREASING (+0.57MB/hr) |
| Heap Sys | 1780.2MB | 1779.9MB | +0.3MB | 1184.5MB | 1780.2MB | |
| Heap Objects | 1,146,340 | 1,300,392 | -154052 | 862,722 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 13 | 14,122 | 192.4MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 28.53MB |
| 3 | `runtime.mallocgc` | 18.01MB |
| 4 | `database/sql.convertAssignRows` | 16.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.53MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 4.37MB |
| 10 | `bytes.growSlice` | 3.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 181.44GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 116.09GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 115.4GB |
| 4 | `internal/evaluation.mergeMetadata` | 112.32GB |
| 5 | `reflect.unsafe_NewArray` | 78.4GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 65.19GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 58.71GB |
| 8 | `experiment/local.topologicalSort` | 57.43GB |
| 9 | `reflect.MakeSlice` | 43.72GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 28.44GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 219/221 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.77MB | 3/221 | `████████░░░░░░░ 53%` |
| 3 | `runtime.mallocgc` | 13.67MB | 215/221 | `█████░░░░░░░░░░ 37%` |
| 4 | `bytes.growSlice` | 12.66MB | 30/221 | `█████░░░░░░░░░░ 34%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/221 | `████░░░░░░░░░░░ 32%` |
| 6 | `database/sql.convertAssignRows` | 11.17MB | 3/221 | `████░░░░░░░░░░░ 30%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/221 | `████░░░░░░░░░░░ 27%` |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 218/221 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 210/221 | `███░░░░░░░░░░░░ 24%` |
| 10 | `bufio.NewReaderSize` | 8.94MB | 19/221 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.0GB | 212/221 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 52.26GB | 214/221 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 52.02GB | 213/221 | `████████░░░░░░░ 57%` |
| 4 | `internal/evaluation.mergeMetadata` | 51.86GB | 208/221 | `████████░░░░░░░ 57%` |
| 5 | `reflect.unsafe_NewArray` | 38.91GB | 212/221 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.7GB | 197/221 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 26.68GB | 210/221 | `████░░░░░░░░░░░ 29%` |
| 8 | `experiment/local.topologicalSort` | 26.4GB | 209/221 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 21.83GB | 210/221 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 16.85GB | 197/221 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
