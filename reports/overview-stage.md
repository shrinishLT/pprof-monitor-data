# Overview: stage
*Last updated: 2026-05-23 15:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T15:02 (409 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,124 | avg: 14,290 | max: 28,205 | trend: stable (-0.25/hr))
```
▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 194.2MB | avg: 172.8MB | max: 732.9MB | trend: stable (+0.21MB/hr))
```
▁▂▁▂▁▂▂▁▂▃▂▂▂▂▃▂▃▃▁▃▂▃▃▂▃▁▂▁▃▃▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▃▁▂▂▂▂▃▂▁▁▅▃▂▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,124 | 14,161 | -37 | 14,290 | 28,205 | stable (-0.25/hr) |
| Heap InUse | 194.2MB | 368.1MB | -173.9MB | 172.8MB | 732.9MB | stable (+0.21MB/hr) |
| Heap Sys | 1751.5MB | 1751.4MB | +0.1MB | 1363.9MB | 1793.6MB | |
| Heap Objects | 1,059,858 | 2,697,132 | -1637274 | 889,629 | 2,697,132 | |

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
| 2026-05-23 | 31 | 14,145 | 182.1MB | 368.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.53MB |
| 9 | `bufio.NewWriterSize` | 1.52MB |
| 10 | `bytes.growSlice` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 84.94GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 45.17GB |
| 3 | `reflect.unsafe_NewArray` | 36.83GB |
| 4 | `reflect.MakeSlice` | 20.46GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.96GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.14GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.46GB |
| 8 | `database/sql.convertAssignRows` | 5.82GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.45GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.1GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 407/409 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.38MB | 11/409 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.85MB | 8/409 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 403/409 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/409 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.68MB | 11/409 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.08MB | 18/409 | `████░░░░░░░░░░░ 30%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/409 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/409 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/409 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.94GB | 400/409 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/409 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/409 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/409 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.47GB | 400/409 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.08GB | 385/409 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/409 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/409 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.21GB | 398/409 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.48GB | 385/409 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
