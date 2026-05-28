# Overview: stage
*Last updated: 2026-05-28 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T06:31 (629 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,480 | avg: 14,255 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▇▄▁▁▁▁▁▁▂▁▁▁▁▃▁▅▅▁▁▁▁▅▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅
```

**Heap InUse** (current: 182.9MB | avg: 173.0MB | max: 732.9MB | trend: stable (+0.04MB/hr))
```
▄█▅▂▃▃▂▃▂▂▂▄▂▃▄▃▅▇▂▂▁▃▃▂▂▃▃▂▂▃▃▂▂▁▃▁▃▁▂▂▄▃▁▂▄▃▃▅▂▄▂▄▂▂▂▃▂▁▃▃▁▃▄▂▃▂▂▁▃▃▃▂▄▁▂▂▄▃▂▃▂▁▁▁▁▁▃▁▃▃▄▃▂▃▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,480 | 14,728 | -248 | 14,255 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 182.9MB | 172.5MB | +10.4MB | 173.0MB | 732.9MB | stable (+0.04MB/hr) |
| Heap Sys | 1307.5MB | 1307.1MB | +0.4MB | 1408.6MB | 1805.8MB | |
| Heap Objects | 1,093,029 | 828,909 | +264120 | 901,121 | 2,707,946 | |

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
| 2026-05-28 | 14 | 14,154 | 147.6MB | 185.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 32.24MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `database/sql.convertAssignRows` | 11.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 4.58MB |
| 8 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 70.55GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 30.69GB |
| 3 | `reflect.unsafe_NewArray` | 30.29GB |
| 4 | `reflect.MakeSlice` | 17.23GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.94GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.69GB |
| 7 | `bytes.growSlice` | 5.21GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.61GB |
| 9 | `database/sql.convertAssignRows` | 4.17GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 3.62GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 627/629 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.2MB | 20/629 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/629 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.08MB | 623/629 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.69MB | 21/629 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/629 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/629 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/629 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 625/629 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/629 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.5GB | 620/629 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/629 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/629 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/629 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.53GB | 620/629 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.34GB | 604/629 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/629 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/629 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.31GB | 618/629 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.6GB | 604/629 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
