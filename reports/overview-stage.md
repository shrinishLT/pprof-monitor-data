# Overview: stage
*Last updated: 2026-05-25 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T17:03 (509 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,242 | avg: 14,258 | max: 28,205 | trend: decreasing (-0.73/hr))
```
▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃▂▁▃
```

**Heap InUse** (current: 163.8MB | avg: 174.7MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▁▂▄▃▁▃▁▂▁▂▁▂▄▃▁▄▁▂▃▂▃▂▁▃▃▄▂▁▃▁▁▃▃▂▁▁▃▃▁▂▅▃▁▂▁▁▃▃▃▂▃▃▂▃▂▁▁▁▁▃▃▂▂▁▁▃▃▄▃▁▄▁▃▇█▃▁▁▂▁▁▂▃▁▃▃▄▄▂▁▁▃▄▃▃▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,242 | 14,086 | +156 | 14,258 | 28,205 | decreasing (-0.73/hr) |
| Heap InUse | 163.8MB | 198.7MB | -34.9MB | 174.7MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1750.6MB | 1750.5MB | +0.1MB | 1440.0MB | 1793.6MB | |
| Heap Objects | 696,973 | 1,207,700 | -510727 | 898,604 | 2,697,132 | |

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
| 2026-05-25 | 35 | 14,136 | 187.0MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `reflect.unsafe_NewArray` | 2.53MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 175.01GB |
| 2 | `reflect.unsafe_NewArray` | 76.16GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 74.76GB |
| 4 | `reflect.MakeSlice` | 42.34GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 33.19GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.8GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.86GB |
| 8 | `database/sql.convertAssignRows` | 9.67GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 9.12GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 507/509 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/509 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/509 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 503/509 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/509 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/509 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/509 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/509 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/509 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/509 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.83GB | 500/509 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/509 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/509 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/509 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.52GB | 500/509 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.87GB | 485/509 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/509 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/509 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.86GB | 498/509 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB | 485/509 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
