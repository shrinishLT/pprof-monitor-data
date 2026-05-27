# Overview: stage
*Last updated: 2026-05-27 23:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T23:31 (615 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,257 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁█▅▁▁▁▁▁▁▂▁▁▁▁▄▁▅▆▁▁▁▁▆▁▁▁▄▆▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▇▁▁▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▄▃▃▁▃▄▂▃▁▄▁▁
```

**Heap InUse** (current: 108.4MB | avg: 173.6MB | max: 732.9MB | trend: stable (+0.06MB/hr))
```
▄▄▅▄▅▃▃▄▅▄▃▄▂▅▄█▅▂▃▃▂▃▂▂▂▄▂▃▄▃▅▇▂▂▁▃▃▂▂▃▃▂▂▃▃▂▂▁▃▁▃▁▂▂▄▃▁▂▄▃▃▅▂▄▂▄▂▂▂▃▂▁▃▃▁▃▄▂▃▂▂▁▃▃▃▂▄▁▂▂▄▃▂▃▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,127 | -57 | 14,257 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 108.4MB | 125.4MB | -17.0MB | 173.6MB | 732.9MB | stable (+0.06MB/hr) |
| Heap Sys | 1308.1MB | 1308.1MB | +0.0MB | 1410.9MB | 1805.8MB | |
| Heap Objects | 336,625 | 556,093 | -219468 | 903,077 | 2,707,946 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.0MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 57.88GB |
| 2 | `reflect.unsafe_NewArray` | 24.81GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.54GB |
| 4 | `reflect.MakeSlice` | 14.13GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.38GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.25GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 2.98GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.85GB |
| 9 | `internal/reflectlite.unsafe_New` | 2.84GB |
| 10 | `database/sql.convertAssignRows` | 2.52GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 613/615 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82MB | 18/615 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/615 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.14MB | 609/615 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.97MB | 19/615 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/615 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/615 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/615 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 611/615 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/615 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.33GB | 606/615 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/615 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/615 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/615 | `██████████░░░░░ 69%` |
| 5 | `reflect.unsafe_NewArray` | 43.89GB | 606/615 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.87GB | 590/615 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/615 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/615 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.51GB | 604/615 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.83GB | 590/615 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
