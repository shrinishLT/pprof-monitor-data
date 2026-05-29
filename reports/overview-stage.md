# Overview: stage
*Last updated: 2026-05-29 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-29T22:31 (709 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,073 | avg: 14,244 | max: 28,205 | trend: stable (-0.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▅▁▁▁▁▁▃▁▆▁▂▁▂▁▁
```

**Heap InUse** (current: 121.4MB | avg: 170.3MB | max: 732.9MB | trend: stable (-0.01MB/hr))
```
▂▁▂▁▁▂▃▁▃▃▄▄▂▃▄▄▂▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆█▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁▂▃▃▄▂▃▃▃▁▂▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,073 | 14,067 | +6 | 14,244 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 121.4MB | 153.4MB | -32.0MB | 170.3MB | 732.9MB | stable (-0.01MB/hr) |
| Heap Sys | 773.4MB | 773.5MB | -0.1MB | 1357.1MB | 1805.8MB | |
| Heap Objects | 614,643 | 993,876 | -379233 | 893,187 | 2,707,946 | |

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
| 2026-05-29 | 46 | 14,158 | 148.9MB | 258.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `regexp.onePassCopy` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.54GB |
| 2 | `segmentio/kafka-go.makePartitions` | 7.25GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 5.75GB |
| 4 | `reflect.unsafe_NewArray` | 3.15GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.84GB |
| 6 | `reflect.MakeSlice` | 1.76GB |
| 7 | `database/sql.convertAssignRows` | 1.67GB |
| 8 | `segmentio/kafka-go.makeLayout` | 796.2MB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 769.74MB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 642.34MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 707/709 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.64MB | 24/709 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.6MB | 15/709 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 13.73MB | 703/709 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.26MB | 25/709 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/709 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/709 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/709 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 705/709 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/709 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 93.09GB | 700/709 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/709 | `███████████░░░░ 76%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/709 | `███████████░░░░ 76%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/709 | `███████████░░░░ 75%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.47GB | 662/709 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 40.3GB | 700/709 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/709 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/709 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 22.52GB | 698/709 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86GB | 660/709 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
