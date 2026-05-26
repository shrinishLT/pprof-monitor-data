# Overview: stage
*Last updated: 2026-05-26 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T22:31 (566 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,089 | avg: 14,265 | max: 28,205 | trend: stable (-0.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 129.4MB | avg: 175.5MB | max: 732.9MB | trend: stable (+0.12MB/hr))
```
▂▂▃▄▃▃▂▂▄▄▄▃▂▄▂▃▇▇▄▂▂▂▂▂▃▃▂▄▃▄▄▃▂▂▃▄▃▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂▂▂▃▂▂▂▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,089 | 14,064 | +25 | 14,265 | 28,205 | stable (-0.43/hr) |
| Heap InUse | 129.4MB | 129.9MB | -0.5MB | 175.5MB | 732.9MB | stable (+0.12MB/hr) |
| Heap Sys | 559.8MB | 559.9MB | -0.1MB | 1438.3MB | 1805.8MB | |
| Heap Objects | 696,971 | 742,283 | -45312 | 908,519 | 2,707,946 | |

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
| 2026-05-26 | 44 | 14,159 | 172.2MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `encoding/json.typeFields` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 12.6GB |
| 2 | `reflect.unsafe_NewArray` | 5.42GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 3.17GB |
| 4 | `reflect.MakeSlice` | 3.07GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1.4GB |
| 6 | `segmentio/kafka-go.makeLayout` | 1.35GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 717.01MB |
| 8 | `internal/reflectlite.unsafe_New` | 656.56MB |
| 9 | `compress/flate.NewWriter` | 562.35MB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 528.01MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 564/566 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/566 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8MB | 17/566 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.41MB | 560/566 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.0MB | 18/566 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/566 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/566 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/566 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 562/566 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.98MB | 26/566 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.12GB | 557/566 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/566 | `██████████░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/566 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/566 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.41GB | 557/566 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.59GB | 541/566 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/566 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/566 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.91GB | 555/566 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.0GB | 541/566 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
