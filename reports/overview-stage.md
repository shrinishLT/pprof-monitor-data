# Overview: stage
*Last updated: 2026-05-28 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T09:31 (635 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,077 | avg: 14,253 | max: 28,205 | trend: stable (-0.50/hr))
```
▁▁▁▂▁▁▁▁▃▁▅▅▁▁▁▁▅▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁
```

**Heap InUse** (current: 127.1MB | avg: 172.7MB | max: 732.9MB | trend: stable (+0.04MB/hr))
```
▂▃▃▂▂▄▂▃▄▃▆█▂▂▁▃▃▂▂▃▄▃▂▃▃▂▂▂▃▂▃▁▂▂▄▃▁▂▅▄▄▆▂▄▂▄▂▂▂▄▃▁▃▃▁▄▄▂▃▂▂▁▄▄▃▂▄▁▂▂▄▃▂▃▂▁▂▁▁▂▃▁▃▃▄▃▂▃▃▄▂▂▂▃▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,077 | 14,080 | -3 | 14,253 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 127.1MB | 139.2MB | -12.1MB | 172.7MB | 732.9MB | stable (+0.04MB/hr) |
| Heap Sys | 1308.2MB | 1308.2MB | +0.0MB | 1407.6MB | 1805.8MB | |
| Heap Objects | 620,839 | 742,932 | -122093 | 899,929 | 2,707,946 | |

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
| 2026-05-28 | 20 | 14,130 | 145.4MB | 185.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `reflect.mapassign_faststr0` | 3.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.0MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 75.89GB |
| 2 | `reflect.unsafe_NewArray` | 32.6GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.09GB |
| 4 | `reflect.MakeSlice` | 18.51GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.29GB |
| 7 | `bytes.growSlice` | 5.25GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.65GB |
| 9 | `database/sql.convertAssignRows` | 4.21GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 3.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 633/635 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.2MB | 20/635 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/635 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.06MB | 629/635 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.69MB | 21/635 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/635 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/635 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/635 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 631/635 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/635 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.24GB | 626/635 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/635 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/635 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/635 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.41GB | 626/635 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.23GB | 610/635 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/635 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/635 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.25GB | 624/635 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.55GB | 610/635 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
