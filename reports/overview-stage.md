# Overview: stage
*Last updated: 2026-05-29 06:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T06:02 (676 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,410 | avg: 14,248 | max: 28,205 | trend: stable (-0.50/hr))
```
▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄
```

**Heap InUse** (current: 221.5MB | avg: 171.3MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
█▃▅▂▅▂▃▂▅▃▂▄▄▁▅▅▃▄▂▃▁▅▅▄▂▅▂▃▃▅▄▃▄▂▁▂▂▁▂▄▂▄▄▅▄▃▄▄▅▂▃▃▄▃▂▃▂▁▆▃▂▃▂▆▅▆▆▂▁▃▄▂▅▂▃▇▂▃▄▄▃▁▃▁▁▄▅▂▅▃▁▂▃▃▅▇
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,410 | 14,063 | +347 | 14,248 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 221.5MB | 178.2MB | +43.3MB | 171.3MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 1324.8MB | 405.3MB | +919.5MB | 1371.3MB | 1805.8MB | |
| Heap Objects | 951,960 | 1,291,327 | -339367 | 896,539 | 2,707,946 | |

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
| 2026-05-26 | 46 | 14,155 | 171.1MB | 299.9MB |
| 2026-05-27 | 47 | 14,177 | 151.2MB | 232.3MB |
| 2026-05-28 | 48 | 14,161 | 148.6MB | 218.1MB |
| 2026-05-29 | 13 | 14,143 | 148.3MB | 221.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bufio.NewWriterSize` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bytes.growSlice` | 2.01MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 10 | `encoding/json.(*decodeState).literalStore` | 1.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 13.93GB |
| 2 | `reflect.unsafe_NewArray` | 6.03GB |
| 3 | `reflect.MakeSlice` | 3.25GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.52GB |
| 5 | `segmentio/kafka-go.makeLayout` | 1.48GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.16GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 804.8MB |
| 8 | `internal/reflectlite.unsafe_New` | 681.06MB |
| 9 | `compress/flate.NewWriter` | 520.93MB |
| 10 | `fmt.Sprintf` | 460.39MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 674/676 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/676 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/676 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.84MB | 670/676 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/676 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/676 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/676 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/676 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 672/676 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/676 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.84GB | 667/676 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/676 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/676 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/676 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 41.93GB | 667/676 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.73GB | 633/676 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/676 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/676 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.43GB | 665/676 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.41GB | 631/676 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
