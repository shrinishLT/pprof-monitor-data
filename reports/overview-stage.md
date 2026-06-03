# Overview: stage
*Last updated: 2026-06-03 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T19:31 (943 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,165 | avg: 14,227 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁
```

**Heap InUse** (current: 145.1MB | avg: 166.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▆▃▃▃▄▆▆▂▃▄▄▄▃▃▄▅▁▃▅▁▆▆▃▄▄▄▁▄▆▁▂▁▂▂▅▄▆▄▁█▅▂▄▃▄▆▅▄▅▆▆▄▆▁▂▇▅▅▆▃▄▆▂▃▄▄▁▅▄▆▁▃▂▁▁▃▁▅▂▆▃▅▆▁▆▁▂▁▁▆▄▃▃▆▄▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,165 | 14,246 | -81 | 14,227 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 145.1MB | 159.4MB | -14.3MB | 166.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 207.2MB | 1549.9MB | -1342.7MB | 1305.6MB | 1805.8MB | |
| Heap Objects | 797,619 | 849,660 | -52041 | 886,727 | 2,707,946 | |

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
| 2026-05-29 | 48 | 14,166 | 148.6MB | 258.2MB |
| 2026-05-30 | 48 | 14,205 | 164.1MB | 277.7MB |
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 48 | 14,226 | 160.1MB | 355.0MB |
| 2026-06-02 | 48 | 14,148 | 157.1MB | 206.0MB |
| 2026-06-03 | 40 | 14,146 | 151.7MB | 191.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 4 | `runtime.mallocgc` | 7.51MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.worker` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 494.63MB |
| 2 | `reflect.unsafe_NewArray` | 209.89MB |
| 3 | `reflect.MakeSlice` | 135.0MB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 66.22MB |
| 5 | `experiment/local.(*Client).EvaluateV2` | 66.19MB |
| 6 | `internal/evaluation.mergeMetadata` | 62.02MB |
| 7 | `segmentio/kafka-go.makeLayout` | 47.77MB |
| 8 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 34.57MB |
| 10 | `experiment/local.topologicalSort` | 31.54MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 941/943 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 35/943 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/943 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.66MB | 937/943 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.31MB | 37/943 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/943 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/943 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/943 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 939/943 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/943 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.93GB | 934/943 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.27GB | 286/943 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.98GB | 285/943 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.33GB | 280/943 | `██████████░░░░░ 71%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.56GB | 895/943 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.33GB | 934/943 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.32GB | 282/943 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.84GB | 281/943 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.69GB | 932/943 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.26GB | 893/943 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
