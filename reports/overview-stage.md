# Overview: stage
*Last updated: 2026-05-28 21:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T21:32 (659 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,110 | avg: 14,251 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▁▁▁▁▁▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▂▁▂▁▃▁▁▁▁
```

**Heap InUse** (current: 160.1MB | avg: 172.0MB | max: 732.9MB | trend: stable (+0.02MB/hr))
```
▄▂▂▂▄▂▄▁▂▃▅▄▁▂▆▅▅█▂▅▂▅▂▃▂▅▃▁▄▄▁▅▅▃▄▂▃▁▅▄▄▂▅▂▂▃▅▃▃▄▂▁▂▁▁▂▃▁▃▃▅▄▃▄▄▅▂▃▃▄▃▂▂▁▁▅▃▂▃▂▅▅▅▆▂▁▃▄▂▄▂▂▇▂▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,110 | 14,149 | -39 | 14,251 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 160.1MB | 145.8MB | +14.3MB | 172.0MB | 732.9MB | stable (+0.02MB/hr) |
| Heap Sys | 202.6MB | 267.9MB | -65.3MB | 1397.6MB | 1805.8MB | |
| Heap Objects | 1,078,604 | 894,247 | +184357 | 898,008 | 2,707,946 | |

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
| 2026-05-28 | 44 | 14,165 | 149.3MB | 218.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 4 | `runtime.mallocgc` | 7.58MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 248.83MB |
| 2 | `reflect.unsafe_NewArray` | 122.0MB |
| 3 | `reflect.MakeSlice` | 70.0MB |
| 4 | `segmentio/kafka-go.makeLayout` | 38.69MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `compress/flate.NewWriter` | 29.97MB |
| 7 | `fmt.Sprintf` | 24.07MB |
| 8 | `internal/reflectlite.unsafe_New` | 17.5MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 12.06MB |
| 10 | `reflect.mapassign_faststr0` | 12.0MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 657/659 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/659 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/659 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.94MB | 653/659 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/659 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/659 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/659 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/659 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 655/659 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/659 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.17GB | 650/659 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/659 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/659 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/659 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.94GB | 650/659 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.79GB | 632/659 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/659 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/659 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.0GB | 648/659 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 630/659 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
