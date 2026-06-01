# Overview: stage
*Last updated: 2026-06-01 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-01T06:30 (821 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,534 | avg: 14,234 | max: 28,205 | trend: stable (-0.45/hr))
```
▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▂▃▅
```

**Heap InUse** (current: 240.0MB | avg: 168.4MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▂▁▄▇▃▁▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▂▃▂▁▁▁▁▁▂▁▂▂▁▃▄▁▁▄▄▂▂▂▄▂▄▂▁▃▁▁▃▁▃▁▂▁▂▃▁▂▁▃▄▅▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 13%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,534 | 14,405 | +129 | 14,234 | 28,205 | stable (-0.45/hr) |
| Heap InUse | 240.0MB | 224.5MB | +15.5MB | 168.4MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1062.8MB | 1063.6MB | -0.8MB | 1298.8MB | 1805.8MB | |
| Heap Objects | 853,294 | 759,778 | +93516 | 887,035 | 2,707,946 | |

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
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 14 | 14,162 | 158.8MB | 240.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 3 | `runtime.mallocgc` | 13.6MB |
| 4 | `database/sql.convertAssignRows` | 12.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 5.52MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 108.42GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 89.48GB |
| 3 | `reflect.unsafe_NewArray` | 46.68GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 41.52GB |
| 5 | `reflect.MakeSlice` | 26.23GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.39GB |
| 7 | `database/sql.convertAssignRows` | 12.01GB |
| 8 | `segmentio/kafka-go.makeLayout` | 11.65GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.48GB |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 5.29GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 819/821 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.45MB | 32/821 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.29MB | 20/821 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 815/821 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.19MB | 34/821 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/821 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/821 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/821 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 817/821 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/821 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.29GB | 812/821 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/821 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/821 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/821 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 42.97GB | 774/821 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.unsafe_NewArray` | 38.2GB | 812/821 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/821 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/821 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.35GB | 810/821 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.14GB | 772/821 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
