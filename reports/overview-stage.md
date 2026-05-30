# Overview: stage
*Last updated: 2026-05-30 08:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T08:30 (729 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,302 | avg: 14,244 | max: 28,205 | trend: stable (-0.46/hr))
```
▁▁▁▁▁▃▁▃▇▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▆▁▁▁▁▁▄▁▆▁▂▁▂▁▁▁▇█▁▁▁▂▁▁▁▁▁▂▃▄▄▁▁▆▃
```

**Heap InUse** (current: 254.8MB | avg: 170.0MB | max: 732.9MB | trend: stable (-0.01MB/hr))
```
▂▂▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆▇▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁▂▃▃▄▂▃▃▃▁▂▃▂▃▂▆▂▂▄▃▄▁▁▂▁▃▄█▃▂▂▄▇
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,302 | 14,534 | -232 | 14,244 | 28,205 | stable (-0.46/hr) |
| Heap InUse | 254.8MB | 188.2MB | +66.6MB | 170.0MB | 732.9MB | stable (-0.01MB/hr) |
| Heap Sys | 876.3MB | 875.6MB | +0.7MB | 1341.8MB | 1805.8MB | |
| Heap Objects | 873,962 | 1,180,458 | -306496 | 891,150 | 2,707,946 | |

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
| 2026-05-30 | 18 | 14,216 | 162.2MB | 258.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 28.5MB |
| 3 | `runtime.mallocgc` | 13.6MB |
| 4 | `database/sql.convertAssignRows` | 9.5MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.55MB |
| 8 | `bytes.growSlice` | 3.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 10 | `reflect.unsafe_NewArray` | 3.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 39.19GB |
| 2 | `segmentio/kafka-go.makePartitions` | 25.33GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 18.1GB |
| 4 | `reflect.unsafe_NewArray` | 10.84GB |
| 5 | `reflect.MakeSlice` | 6.15GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.88GB |
| 7 | `database/sql.convertAssignRows` | 5.21GB |
| 8 | `segmentio/kafka-go.makeLayout` | 2.73GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.35GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 727/729 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.89MB | 28/729 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.31MB | 16/729 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.69MB | 723/729 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.5MB | 29/729 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/729 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/729 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/729 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 725/729 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/729 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.97GB | 720/729 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/729 | `███████████░░░░ 78%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/729 | `███████████░░░░ 78%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/729 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.08GB | 682/729 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 39.38GB | 720/729 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/729 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/729 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 22.0GB | 718/729 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.7GB | 680/729 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
