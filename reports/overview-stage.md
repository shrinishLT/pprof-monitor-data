# Overview: stage
*Last updated: 2026-05-23 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T04:31 (388 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,324 | avg: 14,297 | max: 28,205 | trend: stable (-0.06/hr))
```
▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 144.6MB | avg: 172.0MB | max: 732.9MB | trend: stable (+0.22MB/hr))
```
▁▁▁▁▁▁▁█▁▁▂▂▂▁▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▁▁▁▃▂▁▁▂▁▂▁▁▂▁▁▂▁▁▂▁▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,324 | 14,069 | +255 | 14,297 | 28,205 | stable (-0.06/hr) |
| Heap InUse | 144.6MB | 137.9MB | +6.7MB | 172.0MB | 732.9MB | stable (+0.22MB/hr) |
| Heap Sys | 1591.0MB | 1590.0MB | +1.0MB | 1343.8MB | 1793.6MB | |
| Heap Objects | 258,567 | 436,624 | -178057 | 885,665 | 2,432,873 | |

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
| 2026-05-23 | 10 | 14,120 | 172.5MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `bufio.NewWriterSize` | 2.54MB |
| 7 | `reflect.unsafe_NewArray` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `bufio.NewReaderSize` | 1.55MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 65.96GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.96GB |
| 3 | `reflect.unsafe_NewArray` | 28.65GB |
| 4 | `reflect.MakeSlice` | 15.92GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.17GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.1GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.3GB |
| 8 | `database/sql.convertAssignRows` | 3.91GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.52GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.19GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 386/388 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/388 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.56MB | 382/388 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/388 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/388 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/388 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/388 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.88MB | 8/388 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/388 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/388 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.05GB | 379/388 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/388 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/388 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/388 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 41.95GB | 379/388 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.0GB | 364/388 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/388 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/388 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.48GB | 377/388 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43GB | 364/388 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
