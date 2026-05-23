# Overview: stage
*Last updated: 2026-05-23 08:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T08:30 (396 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,295 | max: 28,205 | trend: stable (-0.10/hr))
```
▁▆▆▄▂▂▁▁▁▂▁▁▁▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁
```

**Heap InUse** (current: 141.1MB | avg: 172.2MB | max: 732.9MB | trend: stable (+0.22MB/hr))
```
▂▃▄▄▅▃▃▅▃▄▄▃▁▂▄▂▄▁▃▃▁▃▄▂▃▃▃▅▃▅▄▁▄▃▅▅▃▄▁▄▁▄▅▄▃▁▁▁▃▂▄▁▁▅▃▂▃▄▄▂▃▃▄▄▄▃▁▂█▅▂▂▄▁▃▃▂▅▃▂▄▃▃▅▁▂▁▁▂▄▄▃▃▄▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,180 | -116 | 14,295 | 28,205 | stable (-0.10/hr) |
| Heap InUse | 141.1MB | 142.9MB | -1.8MB | 172.2MB | 732.9MB | stable (+0.22MB/hr) |
| Heap Sys | 1750.9MB | 1750.7MB | +0.2MB | 1351.2MB | 1793.6MB | |
| Heap Objects | 496,068 | 420,444 | +75624 | 885,436 | 2,432,873 | |

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
| 2026-05-23 | 18 | 14,160 | 176.6MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 73.12GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 42.72GB |
| 3 | `reflect.unsafe_NewArray` | 31.75GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 18.89GB |
| 5 | `reflect.MakeSlice` | 17.63GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.86GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.11GB |
| 8 | `database/sql.convertAssignRows` | 5.5GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.89GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 394/396 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.68MB | 10/396 | `██████░░░░░░░░░ 45%` |
| 3 | `runtime.mallocgc` | 14.56MB | 390/396 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.49MB | 7/396 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/396 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/396 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/396 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/396 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/396 | `███░░░░░░░░░░░░ 25%` |
| 10 | `database/sql.convertAssignRows` | 9.35MB | 10/396 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.49GB | 387/396 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/396 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/396 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/396 | `██████████░░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.71GB | 387/396 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.96GB | 372/396 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/396 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/396 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.35GB | 385/396 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.42GB | 372/396 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
