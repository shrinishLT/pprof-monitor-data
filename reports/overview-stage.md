# Overview: stage
*Last updated: 2026-05-29 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T16:32 (697 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,246 | max: 28,205 | trend: stable (-0.50/hr))
```
▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▅▁▁
```

**Heap InUse** (current: 112.4MB | avg: 170.8MB | max: 732.9MB | trend: stable (-0.00MB/hr))
```
▄▄▄▂▄▂▂▃▅▃▂▄▂▁▂▁▁▂▃▁▃▃▄▄▂▃▄▄▂▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆█▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,096 | -28 | 14,246 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 112.4MB | 179.1MB | -66.7MB | 170.8MB | 732.9MB | stable (-0.00MB/hr) |
| Heap Sys | 1322.9MB | 1322.9MB | +0.0MB | 1369.9MB | 1805.8MB | |
| Heap Objects | 422,608 | 892,379 | -469771 | 894,791 | 2,707,946 | |

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
| 2026-05-29 | 34 | 14,154 | 151.4MB | 258.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `regexp/syntax.(*compiler).inst` | 1.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 33.0GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.18GB |
| 3 | `reflect.unsafe_NewArray` | 14.1GB |
| 4 | `reflect.MakeSlice` | 7.8GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.91GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.49GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.25GB |
| 8 | `database/sql.convertAssignRows` | 1.97GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.71GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.59GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 695/697 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.78MB | 23/697 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/697 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.8MB | 691/697 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.4MB | 24/697 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/697 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/697 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/697 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 693/697 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/697 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.61GB | 688/697 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/697 | `███████████░░░░ 75%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/697 | `███████████░░░░ 75%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/697 | `███████████░░░░ 74%` |
| 5 | `reflect.unsafe_NewArray` | 40.96GB | 688/697 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.81GB | 654/697 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/697 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/697 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 22.89GB | 686/697 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.01GB | 652/697 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
