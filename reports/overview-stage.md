# Overview: stage
*Last updated: 2026-05-21 15:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:02 (299 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,248 | avg: 14,288 | max: 28,205 | trend: stable (-0.02/hr))
```
▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁▁▃▃▅▁▃
```

**Heap InUse** (current: 149.9MB | avg: 167.3MB | max: 732.9MB | trend: stable (+0.26MB/hr))
```
▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁▁▁▂▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,248 | 14,082 | +166 | 14,288 | 28,205 | stable (-0.02/hr) |
| Heap InUse | 149.9MB | 163.9MB | -14.0MB | 167.3MB | 732.9MB | stable (+0.26MB/hr) |
| Heap Sys | 442.8MB | 443.8MB | -1.0MB | 1309.0MB | 1793.6MB | |
| Heap Objects | 839,823 | 1,118,779 | -278956 | 864,889 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 43 | 14,148 | 168.7MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 1.51MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `kafka-go/protocol.newPage` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.59GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 752.47MB |
| 3 | `reflect.unsafe_NewArray` | 719.44MB |
| 4 | `reflect.MakeSlice` | 444.51MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 341.73MB |
| 6 | `segmentio/kafka-go.makeLayout` | 187.7MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 117.0MB |
| 8 | `database/sql.convertAssignRows` | 110.0MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 105.64MB |
| 10 | `compress/flate.NewWriter` | 85.5MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 297/299 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/299 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.54MB | 293/299 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/299 | `████░░░░░░░░░░░ 28%` |
| 5 | `bytes.growSlice` | 10.17MB | 40/299 | `████░░░░░░░░░░░ 27%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/299 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 296/299 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.21MB | 7/299 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.87MB | 288/299 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/299 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 117.85GB | 290/299 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/299 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/299 | `█████████░░░░░░ 60%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/299 | `████████░░░░░░░ 59%` |
| 5 | `reflect.unsafe_NewArray` | 50.91GB | 290/299 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.95GB | 275/299 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/299 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/299 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.55GB | 288/299 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.31GB | 275/299 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
