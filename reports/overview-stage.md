# Overview: stage
*Last updated: 2026-05-21 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:32 (295 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,235 | avg: 14,288 | max: 28,205 | trend: stable (+0.01/hr))
```
▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁▁▃
```

**Heap InUse** (current: 160.2MB | avg: 167.4MB | max: 732.9MB | trend: stable (+0.28MB/hr))
```
▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,235 | 14,069 | +166 | 14,288 | 28,205 | stable (+0.01/hr) |
| Heap InUse | 160.2MB | 152.4MB | +7.8MB | 167.4MB | 732.9MB | stable (+0.28MB/hr) |
| Heap Sys | 443.6MB | 209.8MB | +233.8MB | 1320.8MB | 1793.6MB | |
| Heap Objects | 977,754 | 1,100,647 | -122893 | 863,522 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 39 | 14,139 | 170.0MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.81MB |
| 3 | `database/sql.convertAssignRows` | 12.0MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 8.12MB |
| 6 | `runtime.mallocgc` | 6.01MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bytes.growSlice` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 833.07MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 710.7MB |
| 3 | `reflect.unsafe_NewArray` | 377.9MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 338.68MB |
| 5 | `reflect.MakeSlice` | 221.51MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 114.0MB |
| 7 | `database/sql.convertAssignRows` | 108.0MB |
| 8 | `segmentio/kafka-go.makeLayout` | 98.23MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 57.79MB |
| 10 | `compress/flate.NewWriter` | 52.89MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 293/295 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.87MB | 6/295 | `███████░░░░░░░░ 48%` |
| 3 | `runtime.mallocgc` | 14.65MB | 289/295 | `█████░░░░░░░░░░ 39%` |
| 4 | `bytes.growSlice` | 10.59MB | 38/295 | `████░░░░░░░░░░░ 28%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/295 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/295 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 292/295 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.93MB | 284/295 | `███░░░░░░░░░░░░ 24%` |
| 9 | `database/sql.convertAssignRows` | 8.75MB | 6/295 | `███░░░░░░░░░░░░ 23%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/295 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 119.48GB | 286/295 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/295 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/295 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/295 | `████████░░░░░░░ 59%` |
| 5 | `reflect.unsafe_NewArray` | 51.61GB | 286/295 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.66GB | 271/295 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/295 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/295 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.94GB | 284/295 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.62GB | 271/295 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
