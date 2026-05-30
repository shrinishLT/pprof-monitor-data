# Overview: stage
*Last updated: 2026-05-31 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-31T05:00 (770 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,419 | avg: 14,241 | max: 28,205 | trend: stable (-0.44/hr))
```
▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▄▁▅▁▁▁▁▁▃▁▅▁▂▁▂▁▁▁▅▆▁▁▁▂▁▁▁▁▁▂▂▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄
```

**Heap InUse** (current: 145.0MB | avg: 169.5MB | max: 732.9MB | trend: stable (-0.02MB/hr))
```
▃▅▇▃▂▁▄▄▁▂▂▂▃▁▄▂▂▁▂▂▂▃▁▁▂▂▃▂▂▂▂▁▂▂▁▂▂▆▁▁▃▂▄▁▁▁▁▃▃▇▃▂▂▄▇▃▂▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,419 | 14,074 | +345 | 14,241 | 28,205 | stable (-0.44/hr) |
| Heap InUse | 145.0MB | 147.1MB | -2.1MB | 169.5MB | 732.9MB | stable (-0.02MB/hr) |
| Heap Sys | 877.7MB | 878.0MB | -0.3MB | 1317.1MB | 1805.8MB | |
| Heap Objects | 565,053 | 832,020 | -266967 | 891,429 | 2,707,946 | |

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
| 2026-05-31 | 11 | 14,139 | 149.7MB | 174.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.5MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 62.39GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 59.6GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 27.5GB |
| 4 | `reflect.unsafe_NewArray` | 26.83GB |
| 5 | `reflect.MakeSlice` | 15.06GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.93GB |
| 7 | `database/sql.convertAssignRows` | 7.96GB |
| 8 | `segmentio/kafka-go.makeLayout` | 6.71GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.54GB |
| 10 | `compress/flate.NewWriter` | 3.24GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 768/770 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.78MB | 29/770 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.4MB | 17/770 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 764/770 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.47MB | 30/770 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/770 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/770 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/770 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 766/770 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/770 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.46GB | 761/770 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/770 | `████████████░░░ 80%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/770 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/770 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.72GB | 723/770 | `██████░░░░░░░░░ 46%` |
| 6 | `reflect.unsafe_NewArray` | 38.28GB | 761/770 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/770 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/770 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.39GB | 759/770 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.04GB | 721/770 | `███░░░░░░░░░░░░ 20%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
