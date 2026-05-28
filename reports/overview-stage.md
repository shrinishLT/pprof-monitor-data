# Overview: stage
*Last updated: 2026-05-28 10:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T10:03 (636 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,076 | avg: 14,253 | max: 28,205 | trend: decreasing (-0.50/hr))
```
▁▁▂▁▁▁▁▃▁▅▅▁▁▁▁▅▁▁▁▃▅▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▆▁▁▄▄▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▃▂▃▁▃▃▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▅▁▁▁▁▁▁▁
```

**Heap InUse** (current: 136.9MB | avg: 172.6MB | max: 732.9MB | trend: stable (+0.04MB/hr))
```
▃▃▂▂▄▂▃▄▃▆█▂▂▁▃▃▂▂▃▄▃▂▃▃▂▂▂▃▂▃▁▂▂▄▃▁▂▅▄▄▆▂▄▂▄▂▂▂▄▃▁▃▃▁▄▄▂▃▂▂▁▄▄▃▂▄▁▂▂▄▃▂▃▂▁▂▁▁▂▃▁▃▃▄▃▂▃▃▄▂▂▂▃▂▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,076 | 14,077 | -1 | 14,253 | 28,205 | decreasing (-0.50/hr) |
| Heap InUse | 136.9MB | 127.1MB | +9.8MB | 172.6MB | 732.9MB | stable (+0.04MB/hr) |
| Heap Sys | 1308.2MB | 1308.2MB | +0.0MB | 1407.5MB | 1805.8MB | |
| Heap Objects | 773,757 | 620,839 | +152918 | 899,730 | 2,707,946 | |

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
| 2026-05-28 | 21 | 14,127 | 145.0MB | 185.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `kafka-go/protocol.newPage` | 1.6MB |
| 10 | `encoding/json.(*decodeState).objectInterface` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 76.85GB |
| 2 | `reflect.unsafe_NewArray` | 32.99GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 31.09GB |
| 4 | `reflect.MakeSlice` | 18.74GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.09GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.38GB |
| 7 | `bytes.growSlice` | 5.25GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.66GB |
| 9 | `database/sql.convertAssignRows` | 4.21GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 3.94GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 634/636 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.2MB | 20/636 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/636 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.05MB | 630/636 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.69MB | 21/636 | `█████░░░░░░░░░░ 34%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/636 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/636 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/636 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 632/636 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/636 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.2GB | 627/636 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/636 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/636 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/636 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.4GB | 627/636 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.21GB | 611/636 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/636 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/636 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.24GB | 625/636 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.55GB | 611/636 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
