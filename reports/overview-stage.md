# Overview: stage
*Last updated: 2026-05-24 21:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T21:02 (469 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,124 | avg: 14,269 | max: 28,205 | trend: decreasing (-0.63/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▂▁▄▁▁▇▅▁▁▂▁▁▁▁▂▁▁▁▂▁▁▂▂▁▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 140.7MB | avg: 173.8MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃▃▂▃▃▂▃▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,124 | 14,065 | +59 | 14,269 | 28,205 | decreasing (-0.63/hr) |
| Heap InUse | 140.7MB | 160.7MB | -20.0MB | 173.8MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1751.6MB | 1751.7MB | -0.1MB | 1413.5MB | 1793.6MB | |
| Heap Objects | 433,589 | 767,878 | -334289 | 893,180 | 2,697,132 | |

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
| 2026-05-24 | 43 | 14,134 | 181.2MB | 263.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.mapassign_faststr0` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 138.96GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.54GB |
| 3 | `reflect.unsafe_NewArray` | 60.47GB |
| 4 | `reflect.MakeSlice` | 33.49GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 26.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 14.92GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.72GB |
| 8 | `database/sql.convertAssignRows` | 7.81GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.26GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 467/469 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 13/469 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.19MB | 10/469 | `███████░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.58MB | 463/469 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/469 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.54MB | 13/469 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.22MB | 20/469 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/469 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/469 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/469 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.08GB | 460/469 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/469 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/469 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/469 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.43GB | 460/469 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.75GB | 445/469 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/469 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/469 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.71GB | 458/469 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.25GB | 445/469 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
