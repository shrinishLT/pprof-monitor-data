# Overview: stage
*Last updated: 2026-05-26 14:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T14:01 (551 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,528 | avg: 14,268 | max: 28,205 | trend: stable (-0.40/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 280.8MB | avg: 176.3MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▂▃▂▃▁▇█▆▂▃▂▂▂▃▂▃▃▃▂▃▁▂▃▄▃▁▂▁▃▃▆▄▁▂▁▁▂▁▁▁▃▁▁▂▁▄▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,528 | 14,471 | +57 | 14,268 | 28,205 | stable (-0.40/hr) |
| Heap InUse | 280.8MB | 231.5MB | +49.3MB | 176.3MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1805.8MB | 1748.3MB | +57.5MB | 1463.7MB | 1805.8MB | |
| Heap Objects | 2,707,946 | 1,386,826 | +1321120 | 908,635 | 2,707,946 | |

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
| 2026-05-26 | 29 | 14,163 | 185.4MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 32.39MB |
| 3 | `database/sql.convertAssignRows` | 17.5MB |
| 4 | `runtime.mallocgc` | 14.67MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 6.03MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bufio.NewReaderSize` | 3.54MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 212.7GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 92.67GB |
| 3 | `reflect.unsafe_NewArray` | 92.52GB |
| 4 | `reflect.MakeSlice` | 51.51GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 41.29GB |
| 6 | `segmentio/kafka-go.makeLayout` | 22.8GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.54GB |
| 8 | `database/sql.convertAssignRows` | 12.09GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 11.03GB |
| 10 | `internal/reflectlite.unsafe_New` | 10.41GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 549/551 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/551 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/551 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 545/551 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.06MB | 17/551 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/551 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/551 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/551 | `███░░░░░░░░░░░░ 25%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/551 | `███░░░░░░░░░░░░ 25%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 547/551 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 109.91GB | 542/551 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/551 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/551 | `█████████░░░░░░ 64%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/551 | `█████████░░░░░░ 64%` |
| 5 | `reflect.unsafe_NewArray` | 47.62GB | 542/551 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.74GB | 527/551 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/551 | `████░░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/551 | `████░░░░░░░░░░░ 32%` |
| 9 | `reflect.MakeSlice` | 26.59GB | 540/551 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.51GB | 527/551 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
