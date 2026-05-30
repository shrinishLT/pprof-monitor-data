# Overview: stage
*Last updated: 2026-05-30 09:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T09:30 (731 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,092 | avg: 14,244 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▁▁▃▁▃▇▂▁▄▁▇▁▁▂▃▁▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▆▁▁▁▁▁▄▁▆▁▂▁▂▁▁▁▇█▁▁▁▂▁▁▁▁▁▂▃▄▄▁▁▆▃▁▁
```

**Heap InUse** (current: 133.3MB | avg: 170.0MB | max: 732.9MB | trend: stable (-0.01MB/hr))
```
▂▁▁▅▂▂▃▂▅▄▅▅▂▁▃▄▂▄▂▂▆▂▃▃▄▃▁▂▁▁▄▄▂▅▃▁▂▂▃▄▆▇▃▃▂▄▄▁▃▃▂▄▂▅▂▂▂▂▂▃▄▁▂▃▃▄▂▃▃▃▁▂▃▂▃▂▆▂▂▄▃▄▁▁▂▁▃▄█▃▂▂▄▇▄▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,092 | 14,071 | +21 | 14,244 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 133.3MB | 176.8MB | -43.5MB | 170.0MB | 732.9MB | stable (-0.01MB/hr) |
| Heap Sys | 876.4MB | 876.4MB | +0.0MB | 1340.5MB | 1805.8MB | |
| Heap Objects | 672,141 | 1,277,444 | -605303 | 891,378 | 2,707,946 | |

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
| 2026-05-30 | 20 | 14,202 | 161.5MB | 258.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `dotlapse-event-service/workerpool.(*Worker).Start.func1` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 40.61GB |
| 2 | `segmentio/kafka-go.makePartitions` | 27.11GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 18.71GB |
| 4 | `reflect.unsafe_NewArray` | 11.61GB |
| 5 | `reflect.MakeSlice` | 6.59GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.08GB |
| 7 | `database/sql.convertAssignRows` | 5.38GB |
| 8 | `segmentio/kafka-go.makeLayout` | 2.92GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 2.43GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 1.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 729/731 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.89MB | 28/731 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.31MB | 16/731 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.69MB | 725/731 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.5MB | 29/731 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/731 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/731 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/731 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 727/731 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/731 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.79GB | 722/731 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/731 | `███████████░░░░ 78%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/731 | `███████████░░░░ 78%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/731 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.08GB | 684/731 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 39.31GB | 722/731 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/731 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/731 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 21.96GB | 720/731 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.7GB | 682/731 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
