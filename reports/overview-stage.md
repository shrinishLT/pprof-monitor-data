# Overview: stage
*Last updated: 2026-05-23 12:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T12:30 (404 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,151 | avg: 14,292 | max: 28,205 | trend: stable (-0.20/hr))
```
▁▂▁▁▁▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 168.4MB | avg: 172.3MB | max: 732.9MB | trend: stable (+0.21MB/hr))
```
▃▄▄▃▁▂▄▂▄▁▃▃▁▃▄▂▃▃▃▅▃▅▄▁▄▃▅▅▃▄▁▄▁▄▅▄▃▁▁▁▃▂▄▁▁▅▃▂▃▄▄▂▃▃▄▄▄▃▁▂█▅▂▂▄▁▃▃▂▅▃▂▄▃▃▅▁▂▁▁▂▄▄▃▃▄▁▁▂▄▅▂▃▂▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,151 | 14,114 | +37 | 14,292 | 28,205 | stable (-0.20/hr) |
| Heap InUse | 168.4MB | 151.5MB | +16.9MB | 172.3MB | 732.9MB | stable (+0.21MB/hr) |
| Heap Sys | 1751.2MB | 1750.8MB | +0.4MB | 1359.1MB | 1793.6MB | |
| Heap Objects | 798,752 | 590,249 | +208503 | 886,081 | 2,432,873 | |

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
| 2026-05-23 | 26 | 14,146 | 176.5MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.5MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 80.32GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.38GB |
| 3 | `reflect.unsafe_NewArray` | 34.85GB |
| 4 | `reflect.MakeSlice` | 19.37GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.19GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.65GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.21GB |
| 8 | `database/sql.convertAssignRows` | 5.58GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.23GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 402/404 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.68MB | 10/404 | `██████░░░░░░░░░ 45%` |
| 3 | `runtime.mallocgc` | 14.57MB | 398/404 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.49MB | 7/404 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/404 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/404 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/404 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/404 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/404 | `███░░░░░░░░░░░░ 25%` |
| 10 | `database/sql.convertAssignRows` | 9.35MB | 10/404 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.1GB | 395/404 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/404 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/404 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/404 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.54GB | 395/404 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.02GB | 380/404 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/404 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/404 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.25GB | 393/404 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.45GB | 380/404 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
