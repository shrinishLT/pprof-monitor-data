# Overview: stage
*Last updated: 2026-05-28 17:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T17:02 (650 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,181 | avg: 14,253 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▅▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂
```

**Heap InUse** (current: 151.1MB | avg: 172.2MB | max: 732.9MB | trend: stable (+0.03MB/hr))
```
▃▄▃▂▄▄▃▃▃▄▂▂▂▄▂▄▁▂▃▅▄▁▂▆▅▅█▂▅▂▅▂▃▂▅▃▁▄▄▁▅▅▃▄▂▃▁▅▄▄▂▅▂▂▃▅▃▃▄▂▁▂▁▁▂▃▁▃▃▅▄▃▄▄▅▂▃▃▄▃▂▂▁▁▅▃▂▃▂▅▅▅▆▂▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,181 | 14,077 | +104 | 14,253 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 151.1MB | 111.6MB | +39.5MB | 172.2MB | 732.9MB | stable (+0.03MB/hr) |
| Heap Sys | 1308.8MB | 1310.2MB | -1.4MB | 1405.3MB | 1805.8MB | |
| Heap Objects | 848,161 | 335,874 | +512287 | 898,147 | 2,707,946 | |

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
| 2026-05-28 | 35 | 14,169 | 147.9MB | 203.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 31.25MB |
| 3 | `database/sql.convertAssignRows` | 19.0MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 5 | `runtime.mallocgc` | 11.51MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.53MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.mapassign_faststr0` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 89.47GB |
| 2 | `reflect.unsafe_NewArray` | 38.43GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 34.19GB |
| 4 | `reflect.MakeSlice` | 21.84GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.51GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.77GB |
| 7 | `bytes.growSlice` | 5.43GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.14GB |
| 9 | `database/sql.convertAssignRows` | 4.63GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 4.58GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 648/650 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.77MB | 21/650 | `████████░░░░░░░ 53%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/650 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 14.0MB | 644/650 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.98MB | 22/650 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/650 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/650 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/650 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 646/650 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/650 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.84GB | 641/650 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/650 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/650 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/650 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.23GB | 641/650 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.98GB | 625/650 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/650 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/650 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.16GB | 639/650 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.46GB | 625/650 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
