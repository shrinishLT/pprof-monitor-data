# Overview: stage
*Last updated: 2026-05-21 14:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T14:02 (293 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,056 | avg: 14,289 | max: 28,205 | trend: stable (+0.05/hr))
```
▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁
```

**Heap InUse** (current: 137.9MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.29MB/hr))
```
▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,056 | 14,243 | -187 | 14,289 | 28,205 | stable (+0.05/hr) |
| Heap InUse | 137.9MB | 198.0MB | -60.1MB | 167.5MB | 732.9MB | stable (+0.29MB/hr) |
| Heap Sys | 209.9MB | 1793.6MB | -1583.7MB | 1327.6MB | 1793.6MB | |
| Heap Objects | 915,184 | 851,380 | +63804 | 862,323 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 37 | 14,139 | 170.8MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 1.5MB |
| 8 | `aws/endpoints.init` | 1.0MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.0MB |
| 10 | `kafka-go/protocol.newPage` | 544.67kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 76.38MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 32.21MB |
| 4 | `segmentio/kafka-go.makePartitions` | 31.55MB |
| 5 | `reflect.unsafe_NewArray` | 18.54MB |
| 6 | `reflect.MakeSlice` | 14.0MB |
| 7 | `database/sql.convertAssignRows` | 13.5MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.5MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 291/293 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/293 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.71MB | 287/293 | `██████░░░░░░░░░ 40%` |
| 4 | `bytes.growSlice` | 10.81MB | 37/293 | `████░░░░░░░░░░░ 29%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/293 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/293 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 290/293 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.96MB | 282/293 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/293 | `███░░░░░░░░░░░░ 23%` |
| 10 | `database/sql.convertAssignRows` | 8.1MB | 5/293 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 120.32GB | 284/293 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/293 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/293 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/293 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 51.97GB | 284/293 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 50.03GB | 269/293 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/293 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/293 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 29.15GB | 282/293 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.78GB | 269/293 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
