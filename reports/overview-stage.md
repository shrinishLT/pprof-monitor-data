# Overview: stage
*Last updated: 2026-05-28 19:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T19:01 (654 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,252 | max: 28,205 | trend: stable (-0.48/hr))
```
▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▁▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁▁▁▃▁▃▆▂▁▄▁▇▁▁▂▂▁▂▁
```

**Heap InUse** (current: 128.1MB | avg: 172.1MB | max: 732.9MB | trend: stable (+0.02MB/hr))
```
▄▄▃▃▃▄▂▂▂▄▂▄▁▂▃▅▄▁▂▆▅▅█▂▅▂▅▂▃▂▅▃▁▄▄▁▅▅▃▄▂▃▁▅▄▄▂▅▂▂▃▅▃▃▄▂▁▂▁▁▂▃▁▃▃▅▄▃▄▄▅▂▃▃▄▃▂▂▁▁▅▃▂▃▂▅▅▅▆▂▁▃▄▂▄▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,174 | -110 | 14,252 | 28,205 | stable (-0.48/hr) |
| Heap InUse | 128.1MB | 175.0MB | -46.9MB | 172.1MB | 732.9MB | stable (+0.02MB/hr) |
| Heap Sys | 1309.4MB | 1309.1MB | +0.3MB | 1404.8MB | 1805.8MB | |
| Heap Objects | 624,787 | 1,081,605 | -456818 | 897,650 | 2,707,946 | |

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
| 2026-05-28 | 39 | 14,167 | 148.1MB | 203.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `reflect.mapassign_faststr0` | 2.0MB |
| 10 | `encoding/json.typeFields` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 93.06GB |
| 2 | `reflect.unsafe_NewArray` | 40.05GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 34.27GB |
| 4 | `reflect.MakeSlice` | 22.72GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 15.52GB |
| 6 | `segmentio/kafka-go.makeLayout` | 10.16GB |
| 7 | `bytes.growSlice` | 5.47GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 5.15GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.76GB |
| 10 | `database/sql.convertAssignRows` | 4.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 652/654 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.77MB | 21/654 | `████████░░░░░░░ 53%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.57MB | 14/654 | `███████░░░░░░░░ 50%` |
| 4 | `runtime.mallocgc` | 13.98MB | 648/654 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.98MB | 22/654 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/654 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/654 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/654 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 650/654 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/654 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.79GB | 645/654 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/654 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/654 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/654 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.21GB | 645/654 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.93GB | 629/654 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/654 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/654 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.15GB | 643/654 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.44GB | 629/654 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
