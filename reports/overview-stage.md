# Overview: stage
*Last updated: 2026-05-30 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T07:00 (726 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,092 | avg: 14,244 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▁▁▁▁▁▁▁▃▁▃▇▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▆▁▁▁▁▁▄▁▆▁▂▁▂▁▁▁▇█▁▁▁▂▁▁▁▁▁▂▃▄▄▁
```

**Heap InUse** (current: 134.2MB | avg: 169.9MB | max: 732.9MB | trend: stable (-0.02MB/hr))
```
▂▃▃▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆▇▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁▂▃▃▄▂▃▃▃▁▂▃▂▃▂▆▂▂▄▃▄▁▁▂▁▃▄█▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,092 | 14,413 | -321 | 14,244 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 134.2MB | 164.6MB | -30.4MB | 169.9MB | 732.9MB | stable (-0.02MB/hr) |
| Heap Sys | 876.2MB | 876.1MB | +0.1MB | 1343.7MB | 1805.8MB | |
| Heap Objects | 703,584 | 730,987 | -27403 | 891,016 | 2,707,946 | |

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
| 2026-05-30 | 15 | 14,198 | 156.2MB | 258.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.5MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.28GB |
| 2 | `segmentio/kafka-go.makePartitions` | 22.62GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.2GB |
| 4 | `reflect.unsafe_NewArray` | 9.72GB |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.57GB |
| 6 | `reflect.MakeSlice` | 5.49GB |
| 7 | `database/sql.convertAssignRows` | 4.94GB |
| 8 | `segmentio/kafka-go.makeLayout` | 2.45GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.23GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.96GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 724/726 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.54MB | 27/726 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.31MB | 16/726 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.69MB | 720/726 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.57MB | 28/726 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/726 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/726 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/726 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 722/726 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/726 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 91.25GB | 717/726 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/726 | `███████████░░░░ 78%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/726 | `███████████░░░░ 78%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/726 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.09GB | 679/726 | `██████░░░░░░░░░ 43%` |
| 6 | `reflect.unsafe_NewArray` | 39.51GB | 717/726 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/726 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/726 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 22.07GB | 715/726 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.7GB | 677/726 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
