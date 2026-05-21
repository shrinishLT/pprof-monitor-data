# Overview: stage
*Last updated: 2026-05-21 14:35 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:35 (297 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,389 | avg: 14,289 | max: 28,205 | trend: stable (+0.01/hr))
```
▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁▁▃▃▅
```

**Heap InUse** (current: 133.0MB | avg: 167.3MB | max: 732.9MB | trend: stable (+0.27MB/hr))
```
▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁▁▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,389 | 14,226 | +163 | 14,289 | 28,205 | stable (+0.01/hr) |
| Heap InUse | 133.0MB | 175.2MB | -42.2MB | 167.3MB | 732.9MB | stable (+0.27MB/hr) |
| Heap Sys | 443.5MB | 443.7MB | -0.2MB | 1314.9MB | 1793.6MB | |
| Heap Objects | 700,704 | 1,203,537 | -502833 | 864,119 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 41 | 14,148 | 169.2MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bytes.growSlice` | 1.63MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 909.17MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 750.03MB |
| 3 | `reflect.unsafe_NewArray` | 408.55MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 338.68MB |
| 5 | `reflect.MakeSlice` | 239.51MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 117.0MB |
| 7 | `database/sql.convertAssignRows` | 109.5MB |
| 8 | `segmentio/kafka-go.makeLayout` | 108.39MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 64.64MB |
| 10 | `compress/flate.NewWriter` | 59.94MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 295/297 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/297 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.59MB | 291/297 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/297 | `████░░░░░░░░░░░ 28%` |
| 5 | `bytes.growSlice` | 10.17MB | 40/297 | `████░░░░░░░░░░░ 27%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/297 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 294/297 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.21MB | 7/297 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.9MB | 286/297 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/297 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 118.65GB | 288/297 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/297 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/297 | `█████████░░░░░░ 60%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/297 | `████████░░░░░░░ 59%` |
| 5 | `reflect.unsafe_NewArray` | 51.26GB | 288/297 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.31GB | 273/297 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/297 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/297 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.74GB | 286/297 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.47GB | 273/297 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
