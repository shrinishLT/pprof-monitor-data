# Overview: stage
*Last updated: 2026-05-29 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T02:00 (668 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,249 | max: 28,205 | trend: decreasing (-0.50/hr))
```
▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁
```

**Heap InUse** (current: 132.1MB | avg: 171.5MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
▃▅▄▁▃▆▅▅█▃▅▂▅▂▃▂▅▃▂▄▄▁▅▅▃▄▂▃▁▅▅▄▂▅▂▃▃▅▄▃▄▂▁▂▂▁▂▄▂▄▄▅▄▃▄▄▅▂▃▃▄▃▂▃▂▁▆▃▂▃▂▆▅▆▆▂▁▃▄▂▅▂▃▇▂▃▄▄▃▁▃▁▁▄▅▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,064 | -1 | 14,249 | 28,205 | decreasing (-0.50/hr) |
| Heap InUse | 132.1MB | 178.6MB | -46.5MB | 171.5MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 200.9MB | 200.9MB | +0.0MB | 1381.5MB | 1805.8MB | |
| Heap Objects | 829,838 | 1,339,864 | -510026 | 896,942 | 2,707,946 | |

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
| 2026-05-29 | 5 | 14,076 | 133.7MB | 178.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 4 | `runtime.mallocgc` | 7.58MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `regexp/syntax.(*compiler).inst` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 7.47GB |
| 2 | `reflect.unsafe_NewArray` | 3.22GB |
| 3 | `reflect.MakeSlice` | 1.75GB |
| 4 | `segmentio/kafka-go.makeLayout` | 797.77MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 416.5MB |
| 6 | `internal/reflectlite.unsafe_New` | 357.03MB |
| 7 | `compress/flate.NewWriter` | 255.62MB |
| 8 | `v3/newrelic.newLogEvents` | 242.23MB |
| 9 | `kafka-go/protocol.bytesToString` | 196.01MB |
| 10 | `reflect.mapassign_faststr0` | 187.05MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 666/668 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/668 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/668 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.86MB | 662/668 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/668 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/668 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/668 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/668 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 664/668 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/668 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.88GB | 659/668 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/668 | `██████████░░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/668 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/668 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 42.38GB | 659/668 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.79GB | 632/668 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/668 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/668 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.69GB | 657/668 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 630/668 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
