# Overview: stage
*Last updated: 2026-05-28 23:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T23:32 (663 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,088 | avg: 14,250 | max: 28,205 | trend: stable (-0.49/hr))
```
▁▁▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁
```

**Heap InUse** (current: 137.6MB | avg: 171.8MB | max: 732.9MB | trend: stable (+0.02MB/hr))
```
▄▂▄▁▂▃▅▄▁▂▆▅▅█▂▅▂▅▂▃▂▅▃▁▄▄▁▅▅▃▄▂▃▁▅▄▄▂▅▂▂▃▅▃▃▄▂▁▂▁▁▂▃▁▃▃▅▄▃▄▄▅▂▃▃▄▃▂▂▁▁▅▃▂▃▂▅▅▅▆▂▁▃▄▂▄▂▂▇▂▃▄▄▃▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,088 | 14,065 | +23 | 14,250 | 28,205 | stable (-0.49/hr) |
| Heap InUse | 137.6MB | 105.9MB | +31.7MB | 171.8MB | 732.9MB | stable (+0.02MB/hr) |
| Heap Sys | 201.3MB | 200.2MB | +1.1MB | 1390.4MB | 1805.8MB | |
| Heap Objects | 821,391 | 488,239 | +333152 | 897,764 | 2,707,946 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 4 | `runtime.mallocgc` | 7.58MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `bufio.NewReaderSize` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 3.52GB |
| 2 | `reflect.unsafe_NewArray` | 1.54GB |
| 3 | `reflect.MakeSlice` | 825.52MB |
| 4 | `segmentio/kafka-go.makeLayout` | 379.92MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 189.18MB |
| 6 | `internal/reflectlite.unsafe_New` | 181.52MB |
| 7 | `compress/flate.NewWriter` | 136.62MB |
| 8 | `v3/newrelic.newLogEvents` | 112.52MB |
| 9 | `fmt.Sprintf` | 98.77MB |
| 10 | `reflect.mapassign_faststr0` | 94.52MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 661/663 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/663 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/663 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.9MB | 657/663 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/663 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/663 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/663 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/663 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 659/663 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/663 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.58GB | 654/663 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/663 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/663 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/663 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.69GB | 654/663 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.79GB | 632/663 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/663 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/663 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.86GB | 652/663 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 630/663 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
