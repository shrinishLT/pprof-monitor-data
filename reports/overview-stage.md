# Overview: stage
*Last updated: 2026-05-23 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T09:31 (398 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,294 | max: 28,205 | trend: stable (-0.14/hr))
```
▆▄▂▂▁▁▁▂▁▁▁▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁
```

**Heap InUse** (current: 194.4MB | avg: 172.3MB | max: 732.9MB | trend: stable (+0.21MB/hr))
```
▄▄▅▃▃▅▃▄▄▃▁▂▄▂▄▁▃▃▁▃▄▂▃▃▃▅▃▅▄▁▄▃▅▅▃▄▁▄▁▄▅▄▃▁▁▁▃▂▄▁▁▅▃▂▃▄▄▂▃▃▄▄▄▃▁▂█▅▂▂▄▁▃▃▂▅▃▂▄▃▃▅▁▂▁▁▂▄▄▃▃▄▁▁▂▄
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,074 | -8 | 14,294 | 28,205 | stable (-0.14/hr) |
| Heap InUse | 194.4MB | 159.4MB | +35.0MB | 172.3MB | 732.9MB | stable (+0.21MB/hr) |
| Heap Sys | 1750.9MB | 1750.9MB | +0.0MB | 1353.2MB | 1793.6MB | |
| Heap Objects | 1,164,648 | 700,265 | +464383 | 885,672 | 2,432,873 | |

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
| 2026-05-23 | 20 | 14,151 | 176.6MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.03MB |
| 9 | `net/http.init.func16` | 1.03MB |
| 10 | `segmentio/kafka-go.makeLayout` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 74.93GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 42.79GB |
| 3 | `reflect.unsafe_NewArray` | 32.54GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 18.93GB |
| 5 | `reflect.MakeSlice` | 18.06GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.06GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.12GB |
| 8 | `database/sql.convertAssignRows` | 5.51GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.97GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.64GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 396/398 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.68MB | 10/398 | `██████░░░░░░░░░ 45%` |
| 3 | `runtime.mallocgc` | 14.56MB | 392/398 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.49MB | 7/398 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/398 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/398 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/398 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/398 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/398 | `███░░░░░░░░░░░░ 25%` |
| 10 | `database/sql.convertAssignRows` | 9.35MB | 10/398 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.38GB | 389/398 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/398 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/398 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/398 | `██████████░░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.66GB | 389/398 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.98GB | 374/398 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/398 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/398 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.32GB | 387/398 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.42GB | 374/398 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
