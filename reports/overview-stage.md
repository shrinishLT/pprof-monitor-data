# Overview: stage
*Last updated: 2026-05-26 00:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T00:02 (523 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,273 | max: 28,205 | trend: stable (-0.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 191.6MB | avg: 175.8MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▁▃▁▂▃▂▂▂▁▃▃▄▂▁▃▁▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█▆▂▃▂▂▂▄▂▃▃▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,098 | -34 | 14,273 | 28,205 | stable (-0.34/hr) |
| Heap InUse | 191.6MB | 215.0MB | -23.4MB | 175.8MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1750.0MB | 1750.0MB | +0.0MB | 1448.3MB | 1793.6MB | |
| Heap Objects | 1,148,835 | 1,391,584 | -242749 | 906,834 | 2,697,132 | |

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
| 2026-05-26 | 1 | 14,064 | 191.6MB | 191.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 187.4GB |
| 2 | `reflect.unsafe_NewArray` | 81.63GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 74.78GB |
| 4 | `reflect.MakeSlice` | 45.38GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 33.21GB |
| 6 | `segmentio/kafka-go.makeLayout` | 20.13GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.91GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 9.75GB |
| 9 | `database/sql.convertAssignRows` | 9.74GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.21GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 521/523 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/523 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/523 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 517/523 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/523 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/523 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/523 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.61MB | 24/523 | `███░░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/523 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/523 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 104.97GB | 514/523 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/523 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/523 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/523 | `██████████░░░░░ 67%` |
| 5 | `reflect.unsafe_NewArray` | 45.46GB | 514/523 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.74GB | 499/523 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/523 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/523 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 25.39GB | 512/523 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.6GB | 499/523 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
