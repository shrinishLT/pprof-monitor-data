# Overview: stage
*Last updated: 2026-05-25 02:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T02:00 (479 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,265 | max: 28,205 | trend: decreasing (-0.69/hr))
```
▁▂▂▁▄▁▁▇▅▁▁▂▁▁▁▁▂▁▁▁▂▁▁▂▂▁▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 206.0MB | avg: 173.7MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▂▃▂▂▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,065 | +0 | 14,265 | 28,205 | decreasing (-0.69/hr) |
| Heap InUse | 206.0MB | 147.2MB | +58.8MB | 173.7MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1751.4MB | 1751.4MB | +0.0MB | 1420.5MB | 1793.6MB | |
| Heap Objects | 1,289,932 | 564,885 | +725047 | 892,062 | 2,697,132 | |

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
| 2026-05-25 | 5 | 14,086 | 170.0MB | 206.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 147.93GB |
| 2 | `reflect.unsafe_NewArray` | 64.35GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 60.54GB |
| 4 | `reflect.MakeSlice` | 35.72GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 26.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 15.89GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.73GB |
| 8 | `database/sql.convertAssignRows` | 7.82GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.72GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.21GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 477/479 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 13/479 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.19MB | 10/479 | `███████░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.58MB | 473/479 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/479 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.54MB | 13/479 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.22MB | 20/479 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/479 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/479 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/479 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.06GB | 470/479 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/479 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/479 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/479 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.86GB | 470/479 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.16GB | 455/479 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/479 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/479 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.95GB | 468/479 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.43GB | 455/479 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
