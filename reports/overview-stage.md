# Overview: stage
*Last updated: 2026-05-20 18:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-20T18:31 (246 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,185 | avg: 14,317 | max: 28,205 | trend: INCREASING (+1.67/hr))
```
█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 161.9MB | avg: 167.1MB | max: 732.9MB | trend: stable (+0.46MB/hr))
```
█▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▃▁▁▂▁▁▂▁▂▁▁▁▁▁▂▁▁▁▂▂▂▁▁▂▂▁▁▂▁▁▁▁▁▁▂▁▁▁▂▁▂▂▁▂▂▁▂▅▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,185 | 14,073 | +112 | 14,317 | 28,205 | INCREASING (+1.67/hr) |
| Heap InUse | 161.9MB | 171.6MB | -9.7MB | 167.1MB | 732.9MB | stable (+0.46MB/hr) |
| Heap Sys | 1786.5MB | 1786.0MB | +0.5MB | 1245.3MB | 1786.5MB | |
| Heap Objects | 761,489 | 945,629 | -184140 | 868,824 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 38 | 14,127 | 182.2MB | 369.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 3.72MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.04MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 203.97GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 125.54GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 124.75GB |
| 4 | `internal/evaluation.mergeMetadata` | 121.47GB |
| 5 | `reflect.unsafe_NewArray` | 87.96GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 78.71GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 63.29GB |
| 8 | `experiment/local.topologicalSort` | 62.13GB |
| 9 | `reflect.MakeSlice` | 49.12GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 34.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 244/246 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.95MB | 4/246 | `██████░░░░░░░░░ 43%` |
| 3 | `runtime.mallocgc` | 14.12MB | 240/246 | `█████░░░░░░░░░░ 38%` |
| 4 | `bytes.growSlice` | 12.37MB | 31/246 | `█████░░░░░░░░░░ 33%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/246 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/246 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 243/246 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.0MB | 4/246 | `███░░░░░░░░░░░░ 24%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 235/246 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/246 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.88GB | 237/246 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 59.48GB | 239/246 | `████████░░░░░░░ 58%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 59.22GB | 238/246 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 58.89GB | 233/246 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 43.6GB | 237/246 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.01GB | 222/246 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 30.35GB | 235/246 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 29.99GB | 234/246 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 24.46GB | 235/246 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.72GB | 222/246 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
