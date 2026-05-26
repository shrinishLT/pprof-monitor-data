# Overview: stage
*Last updated: 2026-05-26 19:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T19:32 (560 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,316 | avg: 14,266 | max: 28,205 | trend: stable (-0.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 174.5MB | avg: 175.8MB | max: 732.9MB | trend: stable (+0.13MB/hr))
```
▄▃▄▂▂▂▂▂▃▄▃▃▂▂▄▄▄▃▂▄▂▃▇▇▄▂▂▂▂▂▃▃▂▄▃▄▄▃▂▂▃▄▃▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂▂▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,316 | 14,064 | +252 | 14,266 | 28,205 | stable (-0.42/hr) |
| Heap InUse | 174.5MB | 159.8MB | +14.7MB | 175.8MB | 732.9MB | stable (+0.13MB/hr) |
| Heap Sys | 568.3MB | 572.7MB | -4.4MB | 1447.7MB | 1805.8MB | |
| Heap Objects | 1,087,008 | 1,125,220 | -38212 | 908,601 | 2,707,946 | |

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
| 2026-05-26 | 38 | 14,160 | 176.2MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bytes.growSlice` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewWriterSize` | 1.02MB |
| 9 | `reflect.unsafe_NewArray` | 1.01MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.21GB |
| 2 | `reflect.unsafe_NewArray` | 3.13GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 2.21GB |
| 4 | `reflect.MakeSlice` | 1.77GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1001.13MB |
| 6 | `segmentio/kafka-go.makeLayout` | 783.79MB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 443.13MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 363.51MB |
| 9 | `internal/reflectlite.unsafe_New` | 363.03MB |
| 10 | `compress/flate.NewWriter` | 346.4MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 558/560 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/560 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8MB | 17/560 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.48MB | 554/560 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.0MB | 18/560 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/560 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/560 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/560 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 556/560 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.98MB | 26/560 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 108.18GB | 551/560 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/560 | `█████████░░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/560 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/560 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.87GB | 551/560 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.06GB | 535/560 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/560 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/560 | `████░░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 26.17GB | 549/560 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.21GB | 535/560 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
