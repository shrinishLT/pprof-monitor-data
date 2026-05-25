# Overview: stage
*Last updated: 2026-05-25 18:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T18:03 (511 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,759 | avg: 14,271 | max: 28,205 | trend: stable (-0.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█
```

**Heap InUse** (current: 338.8MB | avg: 175.3MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▃▂▁▃▁▂▁▂▁▂▄▃▁▃▁▂▃▂▂▂▁▃▃▄▂▁▃▁▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█
```

## Current Status

Goroutines: `████████████░░░░░░░░ 62%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,759 | 17,343 | +416 | 14,271 | 28,205 | stable (-0.42/hr) |
| Heap InUse | 338.8MB | 320.2MB | +18.6MB | 175.3MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1741.1MB | 1742.4MB | -1.3MB | 1441.2MB | 1793.6MB | |
| Heap Objects | 1,687,862 | 1,597,665 | +90197 | 901,516 | 2,697,132 | |

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
| 2026-05-25 | 37 | 14,320 | 194.7MB | 338.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 15.57MB |
| 3 | `runtime.mallocgc` | 14.67MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 8.06MB |
| 7 | `bufio.NewWriterSize` | 7.54MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `segmentio/kafka-go.makePartitions` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 176.76GB |
| 2 | `reflect.unsafe_NewArray` | 76.96GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 74.77GB |
| 4 | `reflect.MakeSlice` | 42.75GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 33.2GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.99GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.89GB |
| 8 | `database/sql.convertAssignRows` | 9.7GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 9.21GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.66GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 509/511 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/511 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/511 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 505/511 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/511 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/511 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/511 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.63MB | 23/511 | `███░░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/511 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/511 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 103.12GB | 502/511 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/511 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/511 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/511 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.65GB | 502/511 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.0GB | 487/511 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/511 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/511 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 24.94GB | 500/511 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.27GB | 487/511 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
