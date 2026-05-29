# Overview: stage
*Last updated: 2026-05-30 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T04:31 (721 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,243 | max: 28,205 | trend: stable (-0.49/hr))
```
▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▅▁▁▁▁▁▃▁▆▁▂▁▂▁▁▁▆▇▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 109.5MB | avg: 169.9MB | max: 732.9MB | trend: stable (-0.02MB/hr))
```
▂▃▄▄▂▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆█▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁▂▃▃▄▂▃▃▃▁▂▃▂▃▂▆▂▂▄▃▄▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,072 | -7 | 14,243 | 28,205 | stable (-0.49/hr) |
| Heap InUse | 109.5MB | 124.4MB | -14.9MB | 169.9MB | 732.9MB | stable (-0.02MB/hr) |
| Heap Sys | 771.8MB | 771.8MB | +0.0MB | 1347.4MB | 1805.8MB | |
| Heap Objects | 388,646 | 584,754 | -196108 | 891,275 | 2,707,946 | |

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
| 2026-05-30 | 10 | 14,155 | 145.0MB | 231.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `compress/flate.NewWriter` | 1.76MB |
| 7 | `segmentio/kafka-go.makePartitions` | 1.51MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |
| 10 | `regexp.onePassCopy` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 25.04GB |
| 2 | `segmentio/kafka-go.makePartitions` | 18.15GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 11.49GB |
| 4 | `reflect.unsafe_NewArray` | 7.77GB |
| 5 | `reflect.MakeSlice` | 4.4GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.7GB |
| 7 | `database/sql.convertAssignRows` | 3.32GB |
| 8 | `segmentio/kafka-go.makeLayout` | 1.97GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 1.51GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.27GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 719/721 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.04MB | 25/721 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.6MB | 15/721 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 13.69MB | 715/721 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.92MB | 26/721 | `████░░░░░░░░░░░ 32%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/721 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/721 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/721 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 717/721 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/721 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.74GB | 712/721 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/721 | `███████████░░░░ 77%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/721 | `███████████░░░░ 77%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/721 | `███████████░░░░ 76%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.16GB | 674/721 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 39.72GB | 712/721 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/721 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/721 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 22.19GB | 710/721 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.73GB | 672/721 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
