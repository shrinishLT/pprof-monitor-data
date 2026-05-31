# Overview: stage
*Last updated: 2026-05-31 13:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-31T13:03 (786 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,129 | avg: 14,239 | max: 28,205 | trend: stable (-0.44/hr))
```
▂▁▄▁▅▁▁▁▁▁▃▁▅▁▂▁▂▁▁▁▅▆▁▁▁▂▁▁▁▁▁▂▂▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 118.9MB | avg: 169.0MB | max: 732.9MB | trend: stable (-0.02MB/hr))
```
▂▁▂▂▂▃▁▁▂▂▃▂▂▂▂▁▂▂▁▂▂▆▁▁▃▂▄▁▁▁▁▃▃▇▃▂▂▄▇▃▂▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▃▃▂▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,129 | 14,245 | -116 | 14,239 | 28,205 | stable (-0.44/hr) |
| Heap InUse | 118.9MB | 138.0MB | -19.1MB | 169.0MB | 732.9MB | stable (-0.02MB/hr) |
| Heap Sys | 1026.3MB | 1026.0MB | +0.3MB | 1310.8MB | 1805.8MB | |
| Heap Objects | 427,119 | 596,480 | -169361 | 888,082 | 2,707,946 | |

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
| 2026-05-31 | 27 | 14,140 | 147.3MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 3.5MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 76.94GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 72.69GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 33.6GB |
| 4 | `reflect.unsafe_NewArray` | 33.03GB |
| 5 | `reflect.MakeSlice` | 18.54GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.84GB |
| 7 | `database/sql.convertAssignRows` | 9.75GB |
| 8 | `segmentio/kafka-go.makeLayout` | 8.26GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.29GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 3.87GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 784/786 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.53MB | 31/786 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 18/786 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 780/786 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.3MB | 32/786 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/786 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/786 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/786 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 782/786 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/786 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.08GB | 777/786 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/786 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/786 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/786 | `████████████░░░ 80%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 41.38GB | 739/786 | `███████░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 38.12GB | 777/786 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/786 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/786 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.3GB | 775/786 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.36GB | 737/786 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
