# Overview: stage
*Last updated: 2026-05-29 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T07:31 (679 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,106 | avg: 14,248 | max: 28,205 | trend: stable (-0.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁
```

**Heap InUse** (current: 145.1MB | avg: 171.4MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
▂▄▂▂▂▄▃▁▃▃▁▄▄▂▄▂▂▁▄▄▄▂▄▂▂▃▅▃▂▄▂▁▂▁▁▂▃▁▃▃▄▄▂▃▄▄▂▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆█▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,106 | 14,124 | -18 | 14,248 | 28,205 | stable (-0.49/hr) |
| Heap InUse | 145.1MB | 162.8MB | -17.7MB | 171.4MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 1322.3MB | 1322.2MB | +0.1MB | 1371.1MB | 1805.8MB | |
| Heap Objects | 839,137 | 1,079,239 | -240102 | 896,747 | 2,707,946 | |

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
| 2026-05-29 | 16 | 14,156 | 155.9MB | 258.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 3.03MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.54GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 12.67GB |
| 3 | `reflect.unsafe_NewArray` | 7.11GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.78GB |
| 5 | `reflect.MakeSlice` | 3.88GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.86GB |
| 7 | `segmentio/kafka-go.makeLayout` | 1.75GB |
| 8 | `database/sql.convertAssignRows` | 1.66GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 932.3MB |
| 10 | `internal/reflectlite.unsafe_New` | 812.07MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 677/679 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/679 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/679 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.84MB | 673/679 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/679 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/679 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/679 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/679 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 675/679 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/679 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.47GB | 670/679 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/679 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/679 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/679 | `██████████░░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.77GB | 670/679 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.59GB | 636/679 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/679 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/679 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.34GB | 668/679 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.35GB | 634/679 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
