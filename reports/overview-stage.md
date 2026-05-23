# Overview: stage
*Last updated: 2026-05-24 02:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T02:02 (431 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,281 | max: 28,205 | trend: stable (-0.45/hr))
```
▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁
```

**Heap InUse** (current: 166.7MB | avg: 173.1MB | max: 732.9MB | trend: stable (+0.19MB/hr))
```
▃▂▃▁▂▁▃▃▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▃▁▂▂▂▂▃▂▁▁▅▃▂▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃▂▃▂▁▂▃▂▁▂▁▂▁▁▁▂▃▃▁▃▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,156 | -80 | 14,281 | 28,205 | stable (-0.45/hr) |
| Heap InUse | 166.7MB | 141.9MB | +24.8MB | 173.1MB | 732.9MB | stable (+0.19MB/hr) |
| Heap Sys | 1751.7MB | 1752.6MB | -0.9MB | 1383.7MB | 1793.6MB | |
| Heap Objects | 846,204 | 356,426 | +489778 | 891,086 | 2,697,132 | |

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
| 2026-05-24 | 5 | 14,119 | 174.0MB | 216.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `kafka-go/protocol.newPage` | 1.06MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 104.76GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 45.61GB |
| 3 | `reflect.unsafe_NewArray` | 45.49GB |
| 4 | `reflect.MakeSlice` | 25.24GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.16GB |
| 6 | `segmentio/kafka-go.makeLayout` | 11.23GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.54GB |
| 8 | `database/sql.convertAssignRows` | 5.91GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.47GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 429/431 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.38MB | 11/431 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.85MB | 8/431 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 425/431 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/431 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.68MB | 11/431 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.6MB | 19/431 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/431 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/431 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/431 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.9GB | 422/431 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/431 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/431 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/431 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.47GB | 422/431 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.37GB | 407/431 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/431 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/431 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.2GB | 420/431 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.62GB | 407/431 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
