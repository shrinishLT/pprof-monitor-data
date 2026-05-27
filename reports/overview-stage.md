# Overview: stage
*Last updated: 2026-05-27 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T09:01 (587 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,261 | max: 28,205 | trend: stable (-0.46/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 137.3MB | avg: 174.8MB | max: 732.9MB | trend: stable (+0.09MB/hr))
```
▂▂▂▃▃▂▄▃▄▄▃▂▂▃▄▃▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂▂▂▃▂▂▂▃▂▂▁▃▁▂▁▂▂▃▃▁▂▄▃▃▄▂▃▁▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,072 | -8 | 14,261 | 28,205 | stable (-0.46/hr) |
| Heap InUse | 137.3MB | 131.3MB | +6.0MB | 174.8MB | 732.9MB | stable (+0.09MB/hr) |
| Heap Sys | 1307.3MB | 1307.3MB | +0.0MB | 1415.8MB | 1805.8MB | |
| Heap Objects | 771,900 | 723,430 | +48470 | 907,476 | 2,707,946 | |

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
| 2026-05-27 | 19 | 14,178 | 155.0MB | 232.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `encoding/json.typeFields` | 1.0MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `reflect.mapassign_faststr0` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.77GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.71GB |
| 3 | `reflect.unsafe_NewArray` | 13.61GB |
| 4 | `reflect.MakeSlice` | 7.74GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.37GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.36GB |
| 8 | `database/sql.convertAssignRows` | 2.06GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.66GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 585/587 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82MB | 18/587 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/587 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.27MB | 581/587 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.97MB | 19/587 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/587 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/587 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/587 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 583/587 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/587 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 104.05GB | 578/587 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/587 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/587 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/587 | `██████████░░░░░ 67%` |
| 5 | `reflect.unsafe_NewArray` | 45.08GB | 578/587 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.14GB | 562/587 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/587 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/587 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 25.17GB | 576/587 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.37GB | 562/587 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
