# Overview: stage
*Last updated: 2026-05-30 18:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-30T18:00 (748 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,426 | avg: 14,242 | max: 28,205 | trend: stable (-0.45/hr))
```
▂▁▃▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▃▄▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▂▂▂▁▅▁▆▁▁▁▁▁▄▁▆▁▂▁▂▁▁▁▇█▁▁▁▂▁▁▁▁▁▂▃▄▄▁▁▆▃▁▁▁▁▁▁▁▃▂▂▃▁▂▁▂▁▁▆▄
```

**Heap InUse** (current: 277.7MB | avg: 170.0MB | max: 732.9MB | trend: stable (-0.01MB/hr))
```
▄▂▂▅▂▂▃▃▃▁▂▁▁▃▄▂▄▃▁▂▂▃▄▅▇▃▂▂▄▄▁▃▃▂▄▂▄▂▂▂▂▂▃▄▁▂▃▃▃▂▂▃▂▁▂▃▂▃▂▆▂▂▃▂▄▁▁▂▁▃▄▇▃▂▂▄▇▄▂▁▃▁▄▂▅▃▄▂▁▄▂▄▃▄▇█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,426 | 14,606 | -180 | 14,242 | 28,205 | stable (-0.45/hr) |
| Heap InUse | 277.7MB | 259.9MB | +17.8MB | 170.0MB | 732.9MB | stable (-0.01MB/hr) |
| Heap Sys | 877.5MB | 877.2MB | +0.3MB | 1330.0MB | 1805.8MB | |
| Heap Objects | 1,155,591 | 870,738 | +284853 | 892,485 | 2,707,946 | |

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
| 2026-05-30 | 37 | 14,200 | 165.8MB | 277.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 6 | `reflect.unsafe_NewArray` | 3.0MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.9GB |
| 2 | `segmentio/kafka-go.makePartitions` | 42.56GB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 25.81GB |
| 4 | `reflect.unsafe_NewArray` | 18.16GB |
| 5 | `reflect.MakeSlice` | 10.27GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.39GB |
| 7 | `database/sql.convertAssignRows` | 7.44GB |
| 8 | `segmentio/kafka-go.makeLayout` | 4.59GB |
| 9 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 3.32GB |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 2.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 746/748 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.78MB | 29/748 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.4MB | 17/748 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 742/748 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.47MB | 30/748 | `████░░░░░░░░░░░ 31%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/748 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/748 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/748 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 744/748 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/748 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.51GB | 739/748 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/748 | `███████████░░░░ 79%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/748 | `███████████░░░░ 79%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/748 | `███████████░░░░ 78%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 40.15GB | 701/748 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 38.75GB | 739/748 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/748 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/748 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.65GB | 737/748 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.75GB | 699/748 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
