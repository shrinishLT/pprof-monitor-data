# Overview: stage
*Last updated: 2026-05-29 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T03:31 (671 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,091 | avg: 14,248 | max: 28,205 | trend: decreasing (-0.51/hr))
```
▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 112.6MB | avg: 171.4MB | max: 732.9MB | trend: stable (+0.01MB/hr))
```
▁▃▆▅▅█▃▅▂▅▂▃▂▅▃▂▄▄▁▅▅▃▄▂▃▁▅▅▄▂▅▂▃▃▅▄▃▄▂▁▂▂▁▂▄▂▄▄▅▄▃▄▄▅▂▃▃▄▃▂▃▂▁▆▃▂▃▂▆▅▆▆▂▁▃▄▂▅▂▃▇▂▃▄▄▃▁▃▁▁▄▅▂▅▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,091 | 14,072 | +19 | 14,248 | 28,205 | decreasing (-0.51/hr) |
| Heap InUse | 112.6MB | 149.2MB | -36.6MB | 171.4MB | 732.9MB | stable (+0.01MB/hr) |
| Heap Sys | 408.3MB | 409.2MB | -0.9MB | 1377.2MB | 1805.8MB | |
| Heap Objects | 416,703 | 912,490 | -495787 | 896,977 | 2,707,946 | |

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
| 2026-05-29 | 8 | 14,077 | 140.0MB | 189.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `encoding/json.(*decodeState).literalStore` | 1.54MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 9.86GB |
| 2 | `reflect.unsafe_NewArray` | 4.3GB |
| 3 | `reflect.MakeSlice` | 2.31GB |
| 4 | `segmentio/kafka-go.makeLayout` | 1.05GB |
| 5 | `v3/newrelic.newAnalyticsEvents` | 559.99MB |
| 6 | `internal/reflectlite.unsafe_New` | 480.04MB |
| 7 | `compress/flate.NewWriter` | 380.78MB |
| 8 | `fmt.Sprintf` | 355.59MB |
| 9 | `v3/newrelic.newLogEvents` | 322.05MB |
| 10 | `kafka-go/protocol.bytesToString` | 259.01MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 669/671 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.33MB | 22/671 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/671 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.85MB | 665/671 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.72MB | 23/671 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/671 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/671 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/671 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 667/671 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/671 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.48GB | 662/671 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/671 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/671 | `██████████░░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/671 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 42.21GB | 662/671 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.79GB | 632/671 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/671 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/671 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.59GB | 660/671 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 630/671 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
