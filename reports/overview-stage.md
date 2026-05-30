# Overview: stage
*Last updated: 2026-05-30 22:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T22:32 (757 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,119 | avg: 14,242 | max: 28,205 | trend: stable (-0.43/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▄▁▅▁▁▁▁▁▃▁▅▁▂▁▂▁▁▁▅▆▁▁▁▂▁▁▁▁▁▂▂▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁
```

**Heap InUse** (current: 155.3MB | avg: 169.9MB | max: 732.9MB | trend: stable (-0.01MB/hr))
```
▁▂▁▁▃▄▂▄▃▁▂▂▃▄▅▇▃▂▂▄▄▁▃▃▂▄▂▄▂▂▂▂▂▃▄▁▂▃▃▃▂▂▃▂▁▂▃▂▃▂▆▂▂▃▂▄▁▁▂▁▃▄▇▃▂▂▄▇▄▂▁▃▁▄▂▅▃▄▂▁▄▂▄▃▄▇█▂▃▂▃▃▂▃▇▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,119 | 14,868 | -749 | 14,242 | 28,205 | stable (-0.43/hr) |
| Heap InUse | 155.3MB | 253.4MB | -98.1MB | 169.9MB | 732.9MB | stable (-0.01MB/hr) |
| Heap Sys | 878.3MB | 877.9MB | +0.4MB | 1324.6MB | 1805.8MB | |
| Heap Objects | 907,222 | 1,271,951 | -364729 | 891,889 | 2,707,946 | |

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
| 2026-05-30 | 46 | 14,208 | 164.3MB | 277.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.6GB |
| 2 | `segmentio/kafka-go.makePartitions` | 50.7GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 27.5GB |
| 4 | `reflect.unsafe_NewArray` | 21.67GB |
| 5 | `reflect.MakeSlice` | 12.27GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.9GB |
| 7 | `database/sql.convertAssignRows` | 7.93GB |
| 8 | `segmentio/kafka-go.makeLayout` | 5.49GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.54GB |
| 10 | `compress/flate.NewWriter` | 2.85GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 755/757 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.78MB | 29/757 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.4MB | 17/757 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 751/757 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.47MB | 30/757 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/757 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/757 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/757 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 753/757 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/757 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.0GB | 748/757 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/757 | `████████████░░░ 80%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/757 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/757 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.37GB | 710/757 | `██████░░░░░░░░░ 45%` |
| 6 | `reflect.unsafe_NewArray` | 38.52GB | 748/757 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/757 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/757 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.53GB | 746/757 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.87GB | 708/757 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
