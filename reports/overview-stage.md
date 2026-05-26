# Overview: stage
*Last updated: 2026-05-26 16:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T16:01 (553 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,267 | max: 28,205 | trend: stable (-0.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 142.0MB | avg: 176.2MB | max: 732.9MB | trend: stable (+0.14MB/hr))
```
▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▂▃▂▃▁▇█▆▂▃▂▂▂▃▂▃▃▃▂▃▁▂▃▄▃▁▂▁▃▃▆▄▁▂▁▁▂▁▁▁▃▁▁▂▁▄▆▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,055 | +19 | 14,267 | 28,205 | stable (-0.41/hr) |
| Heap InUse | 142.0MB | 138.7MB | +3.3MB | 176.2MB | 732.9MB | stable (+0.14MB/hr) |
| Heap Sys | 305.4MB | 165.8MB | +139.6MB | 1459.2MB | 1805.8MB | |
| Heap Objects | 918,006 | 907,061 | +10945 | 908,649 | 2,707,946 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 72 | 14,362 | 180.0MB | 556.9MB |
| 2026-05-22 | 50 | 14,165 | 186.1MB | 277.6MB |
| 2026-05-23 | 48 | 14,133 | 181.2MB | 368.1MB |
| 2026-05-24 | 48 | 14,127 | 179.7MB | 263.6MB |
| 2026-05-25 | 48 | 14,341 | 196.2MB | 338.8MB |
| 2026-05-26 | 31 | 14,157 | 182.5MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.21GB |
| 2 | `reflect.unsafe_NewArray` | 546.87MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 533.49MB |
| 4 | `reflect.MakeSlice` | 304.51MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 231.83MB |
| 6 | `segmentio/kafka-go.makeLayout` | 129.13MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 91.92MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 73.5MB |
| 9 | `compress/flate.NewWriter` | 70.51MB |
| 10 | `internal/reflectlite.unsafe_New` | 66.01MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 551/553 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/553 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/553 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.57MB | 547/553 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.06MB | 17/553 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/553 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/553 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/553 | `███░░░░░░░░░░░░ 25%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/553 | `███░░░░░░░░░░░░ 25%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 549/553 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 109.51GB | 544/553 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/553 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/553 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/553 | `█████████░░░░░░ 64%` |
| 5 | `reflect.unsafe_NewArray` | 47.45GB | 544/553 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.65GB | 528/553 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/553 | `████░░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/553 | `████░░░░░░░░░░░ 32%` |
| 9 | `reflect.MakeSlice` | 26.49GB | 542/553 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.47GB | 528/553 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
