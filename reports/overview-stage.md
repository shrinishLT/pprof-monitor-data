# Overview: stage
*Last updated: 2026-05-29 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T10:31 (685 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,247 | max: 28,205 | trend: decreasing (-0.51/hr))
```
▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 150.1MB | avg: 171.2MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
▃▁▃▃▁▄▄▂▄▂▂▁▄▄▄▂▄▂▂▃▅▃▂▄▂▁▂▁▁▂▃▁▃▃▄▄▂▃▄▄▂▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆█▃▃▂▄▄▁▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,073 | +0 | 14,247 | 28,205 | decreasing (-0.51/hr) |
| Heap InUse | 150.1MB | 150.0MB | +0.1MB | 171.2MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 1322.4MB | 1322.4MB | +0.0MB | 1370.7MB | 1805.8MB | |
| Heap Objects | 900,316 | 948,384 | -48068 | 897,061 | 2,707,946 | |

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
| 2026-05-29 | 22 | 14,132 | 154.7MB | 258.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `regexp/syntax.(*compiler).inst` | 1.0MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.01GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 12.67GB |
| 3 | `reflect.unsafe_NewArray` | 9.49GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 5.78GB |
| 5 | `reflect.MakeSlice` | 5.22GB |
| 6 | `segmentio/kafka-go.makeLayout` | 2.35GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.87GB |
| 8 | `database/sql.convertAssignRows` | 1.66GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.17GB |
| 10 | `internal/reflectlite.unsafe_New` | 1.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 683/685 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/685 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/685 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.82MB | 679/685 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/685 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/685 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/685 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/685 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 681/685 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/685 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.79GB | 676/685 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/685 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/685 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/685 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.48GB | 676/685 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.32GB | 642/685 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/685 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/685 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.18GB | 674/685 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23GB | 640/685 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
