# Overview: stage
*Last updated: 2026-05-28 08:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T08:32 (633 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,254 | max: 28,205 | trend: stable (-0.49/hr))
```
▁▁▁▁▁▂▁▁▁▁▃▁▅▅▁▁▁▁▅▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁
```

**Heap InUse** (current: 163.6MB | avg: 172.8MB | max: 732.9MB | trend: stable (+0.04MB/hr))
```
▄▃▂▃▃▂▂▄▂▃▄▃▆█▂▂▁▃▃▂▂▃▄▃▂▃▃▂▂▂▃▂▃▁▂▂▄▃▁▂▅▄▄▆▂▄▂▄▂▂▂▄▃▁▃▃▁▄▄▂▃▂▂▁▄▄▃▂▄▁▂▂▄▃▂▃▂▁▂▁▁▂▃▁▃▃▄▃▂▃▃▄▂▂▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,069 | +5 | 14,254 | 28,205 | stable (-0.49/hr) |
| Heap InUse | 163.6MB | 141.6MB | +22.0MB | 172.8MB | 732.9MB | stable (+0.04MB/hr) |
| Heap Sys | 1308.2MB | 1308.2MB | +0.0MB | 1408.0MB | 1805.8MB | |
| Heap Objects | 1,074,283 | 798,769 | +275514 | 900,618 | 2,707,946 | |

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
| 2026-05-28 | 18 | 14,136 | 146.8MB | 185.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.04MB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 74.09GB |
| 2 | `reflect.unsafe_NewArray` | 31.82GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.09GB |
| 4 | `reflect.MakeSlice` | 18.1GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.09GB |
| 7 | `bytes.growSlice` | 5.24GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.65GB |
| 9 | `database/sql.convertAssignRows` | 4.21GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 3.8GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 631/633 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.2MB | 20/633 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/633 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.07MB | 627/633 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.69MB | 21/633 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/633 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/633 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/633 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 629/633 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/633 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.32GB | 624/633 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/633 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/633 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/633 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.45GB | 624/633 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.26GB | 608/633 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/633 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/633 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.27GB | 622/633 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.57GB | 608/633 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
