# Overview: stage
*Last updated: 2026-05-29 00:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T00:30 (665 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,250 | max: 28,205 | trend: stable (-0.50/hr))
```
▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁
```

**Heap InUse** (current: 95.6MB | avg: 171.5MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
▄▁▂▃▅▄▁▃▆▅▅█▃▅▂▅▂▃▂▅▃▂▄▄▁▅▅▃▄▂▃▁▅▅▄▂▅▂▃▃▅▄▃▄▂▁▂▂▁▂▄▂▄▄▅▄▃▄▄▅▂▃▃▄▃▂▃▂▁▆▃▂▃▂▆▅▆▆▂▁▃▄▂▅▂▃▇▂▃▄▄▃▁▃▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,063 | +2 | 14,250 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 95.6MB | 94.6MB | +1.0MB | 171.5MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 202.3MB | 202.5MB | -0.2MB | 1386.8MB | 1805.8MB | |
| Heap Objects | 325,637 | 246,168 | +79469 | 895,923 | 2,707,946 | |

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
| 2026-05-29 | 2 | 14,064 | 95.1MB | 95.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 4 | `runtime.mallocgc` | 7.58MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `reflect.unsafe_NewArray` | 2.0MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 5.07GB |
| 2 | `reflect.unsafe_NewArray` | 2.2GB |
| 3 | `reflect.MakeSlice` | 1.18GB |
| 4 | `segmentio/kafka-go.makeLayout` | 552.44MB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 285.17MB |
| 6 | `internal/reflectlite.unsafe_New` | 251.02MB |
| 7 | `compress/flate.NewWriter` | 185.98MB |
| 8 | `v3/newrelic.newLogEvents` | 157.01MB |
| 9 | `kafka-go/protocol.(*decoder).read` | 132.01MB |
| 10 | `reflect.mapassign_faststr0` | 131.03MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 663/665 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/665 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/665 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.88MB | 659/665 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/665 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/665 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/665 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/665 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 661/665 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/665 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.3GB | 656/665 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/665 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/665 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/665 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.56GB | 656/665 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.79GB | 632/665 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/665 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/665 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.79GB | 654/665 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 630/665 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
