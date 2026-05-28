# Overview: stage
*Last updated: 2026-05-28 18:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T18:02 (652 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,096 | avg: 14,252 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▂▁
```

**Heap InUse** (current: 125.0MB | avg: 172.1MB | max: 732.9MB | trend: stable (+0.02MB/hr))
```
▃▂▄▄▃▃▃▄▂▂▂▄▂▄▁▂▃▅▄▁▂▆▅▅█▂▅▂▅▂▃▂▅▃▁▄▄▁▅▅▃▄▂▃▁▅▄▄▂▅▂▂▃▅▃▃▄▂▁▂▁▁▂▃▁▃▃▅▄▃▄▄▅▂▃▃▄▃▂▂▁▁▅▃▂▃▂▅▅▅▆▂▁▃▄▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,096 | 14,252 | -156 | 14,252 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 125.0MB | 169.7MB | -44.7MB | 172.1MB | 732.9MB | stable (+0.02MB/hr) |
| Heap Sys | 1309.3MB | 1308.9MB | +0.4MB | 1405.1MB | 1805.8MB | |
| Heap Objects | 543,117 | 1,018,151 | -475034 | 897,786 | 2,707,946 | |

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
| 2026-05-28 | 37 | 14,170 | 147.9MB | 203.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `encoding/json.typeFields` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 91.31GB |
| 2 | `reflect.unsafe_NewArray` | 39.26GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 34.27GB |
| 4 | `reflect.MakeSlice` | 22.3GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.51GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.97GB |
| 7 | `bytes.growSlice` | 5.45GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.15GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.67GB |
| 10 | `database/sql.convertAssignRows` | 4.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 650/652 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.77MB | 21/652 | `████████░░░░░░░ 53%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/652 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.99MB | 646/652 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.98MB | 22/652 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/652 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/652 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/652 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 648/652 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/652 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.81GB | 643/652 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/652 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/652 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/652 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.22GB | 643/652 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.96GB | 627/652 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/652 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/652 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.15GB | 641/652 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.45GB | 627/652 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
