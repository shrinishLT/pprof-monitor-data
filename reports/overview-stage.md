# Overview: stage
*Last updated: 2026-05-27 17:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T17:02 (603 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,281 | avg: 14,258 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 174.5MB | avg: 174.1MB | max: 732.9MB | trend: stable (+0.07MB/hr))
```
▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂▂▂▃▂▂▂▃▂▂▁▃▁▂▁▂▂▃▃▁▂▄▃▃▄▂▃▁▃▂▂▁▃▂▁▂▂▁▃▃▂▃▁▂▁▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,281 | 14,140 | +141 | 14,258 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 174.5MB | 179.8MB | -5.3MB | 174.1MB | 732.9MB | stable (+0.07MB/hr) |
| Heap Sys | 1307.6MB | 1307.9MB | -0.3MB | 1412.9MB | 1805.8MB | |
| Heap Objects | 1,065,660 | 1,138,587 | -72927 | 905,290 | 2,707,946 | |

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
| 2026-05-27 | 35 | 14,164 | 152.4MB | 232.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `encoding/json.typeFields` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 46.22GB |
| 2 | `reflect.unsafe_NewArray` | 19.82GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.53GB |
| 4 | `reflect.MakeSlice` | 11.3GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.37GB |
| 6 | `segmentio/kafka-go.makeLayout` | 4.97GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.8GB |
| 8 | `database/sql.convertAssignRows` | 2.49GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 2.39GB |
| 10 | `internal/reflectlite.unsafe_New` | 2.29GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 601/603 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82MB | 18/603 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/603 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.2MB | 597/603 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.97MB | 19/603 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/603 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/603 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/603 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 599/603 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/603 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.31GB | 594/603 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/603 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/603 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/603 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.32GB | 594/603 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.38GB | 578/603 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/603 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/603 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.75GB | 592/603 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.04GB | 578/603 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
