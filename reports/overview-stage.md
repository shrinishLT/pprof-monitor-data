# Overview: stage
*Last updated: 2026-05-26 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T06:31 (536 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,433 | avg: 14,271 | max: 28,205 | trend: stable (-0.36/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 231.9MB | avg: 176.5MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▁▃▁▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█▆▂▃▂▂▂▄▂▃▃▃▂▃▁▂▃▄▃▁▂▁▄▃▆▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,433 | 14,660 | -227 | 14,271 | 28,205 | stable (-0.36/hr) |
| Heap InUse | 231.9MB | 299.9MB | -68.0MB | 176.5MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1749.6MB | 1749.4MB | +0.2MB | 1455.6MB | 1793.6MB | |
| Heap Objects | 1,236,502 | 849,921 | +386581 | 911,011 | 2,697,132 | |

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
| 2026-05-26 | 14 | 14,174 | 201.5MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 15.2MB |
| 4 | `runtime.mallocgc` | 14.67MB |
| 5 | `database/sql.convertAssignRows` | 12.0MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bytes.growSlice` | 3.01MB |
| 9 | `bufio.NewReaderSize` | 2.54MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 199.19GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 87.25GB |
| 3 | `reflect.unsafe_NewArray` | 86.7GB |
| 4 | `reflect.MakeSlice` | 48.21GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 38.86GB |
| 6 | `segmentio/kafka-go.makeLayout` | 21.37GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.77GB |
| 8 | `database/sql.convertAssignRows` | 11.38GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.35GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 534/536 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.62MB | 12/536 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/536 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 530/536 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/536 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.78MB | 16/536 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/536 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/536 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/536 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/536 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.16GB | 527/536 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/536 | `██████████░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/536 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/536 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.42GB | 527/536 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.53GB | 512/536 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/536 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/536 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.92GB | 525/536 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.96GB | 512/536 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
