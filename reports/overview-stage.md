# Overview: stage
*Last updated: 2026-05-21 14:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:32 (296 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,226 | avg: 14,288 | max: 28,205 | trend: stable (+0.00/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁▁▃▃
```

**Heap InUse** (current: 175.2MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.27MB/hr))
```
▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁▁▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,226 | 14,235 | -9 | 14,288 | 28,205 | stable (+0.00/hr) |
| Heap InUse | 175.2MB | 160.2MB | +15.0MB | 167.5MB | 732.9MB | stable (+0.27MB/hr) |
| Heap Sys | 443.7MB | 443.6MB | +0.1MB | 1317.8MB | 1793.6MB | |
| Heap Objects | 1,203,537 | 977,754 | +225783 | 864,671 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 40 | 14,142 | 170.1MB | 252.1MB |

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
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 294/296 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/296 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.62MB | 290/296 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/296 | `████░░░░░░░░░░░ 28%` |
| 5 | `bytes.growSlice` | 10.39MB | 39/296 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/296 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 293/296 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.21MB | 7/296 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.91MB | 285/296 | `███░░░░░░░░░░░░ 24%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/296 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 119.06GB | 287/296 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/296 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/296 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/296 | `████████░░░░░░░ 59%` |
| 5 | `reflect.unsafe_NewArray` | 51.43GB | 287/296 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.48GB | 272/296 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/296 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/296 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.84GB | 285/296 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.55GB | 272/296 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
