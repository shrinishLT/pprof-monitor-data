# Overview: stage
*Last updated: 2026-05-26 13:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T13:31 (550 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,471 | avg: 14,267 | max: 28,205 | trend: stable (-0.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 231.5MB | avg: 176.1MB | max: 732.9MB | trend: stable (+0.14MB/hr))
```
▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▂▃▂▃▁▇█▆▂▃▂▂▂▃▂▃▃▃▂▃▁▂▃▄▃▁▂▁▃▃▆▄▁▂▁▁▂▁▁▁▃▁▁▂▁▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,471 | 14,107 | +364 | 14,267 | 28,205 | stable (-0.41/hr) |
| Heap InUse | 231.5MB | 156.2MB | +75.3MB | 176.1MB | 732.9MB | stable (+0.14MB/hr) |
| Heap Sys | 1748.3MB | 1749.7MB | -1.4MB | 1463.1MB | 1793.6MB | |
| Heap Objects | 1,386,826 | 645,500 | +741326 | 905,364 | 2,697,132 | |

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
| 2026-05-26 | 28 | 14,150 | 182.0MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.04MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `reflect.unsafe_NewArray` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 211.81GB |
| 2 | `reflect.unsafe_NewArray` | 92.14GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 87.93GB |
| 4 | `reflect.MakeSlice` | 51.29GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 39.17GB |
| 6 | `segmentio/kafka-go.makeLayout` | 22.7GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.87GB |
| 8 | `database/sql.convertAssignRows` | 11.48GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.99GB |
| 10 | `internal/reflectlite.unsafe_New` | 10.36GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 548/550 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.62MB | 12/550 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/550 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 544/550 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/550 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.78MB | 16/550 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/550 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/550 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/550 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/550 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 109.72GB | 541/550 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/550 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/550 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/550 | `█████████░░░░░░ 64%` |
| 5 | `reflect.unsafe_NewArray` | 47.54GB | 541/550 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.65GB | 526/550 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/550 | `████░░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/550 | `████░░░░░░░░░░░ 32%` |
| 9 | `reflect.MakeSlice` | 26.54GB | 539/550 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.47GB | 526/550 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
