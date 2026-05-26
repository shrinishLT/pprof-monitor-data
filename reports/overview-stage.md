# Overview: stage
*Last updated: 2026-05-26 11:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T11:03 (545 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,268 | max: 28,205 | trend: stable (-0.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 200.1MB | avg: 176.1MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▂▃▂▃▁▇█▆▂▃▂▂▂▃▂▃▃▃▂▃▁▂▃▄▃▁▂▁▃▃▆▄▁▂▁▁▂▁▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,070 | -5 | 14,268 | 28,205 | stable (-0.41/hr) |
| Heap InUse | 200.1MB | 136.1MB | +64.0MB | 176.1MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1749.8MB | 1750.8MB | -1.0MB | 1460.4MB | 1793.6MB | |
| Heap Objects | 1,220,633 | 303,813 | +916820 | 906,261 | 2,697,132 | |

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
| 2026-05-26 | 23 | 14,139 | 183.7MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 5.29MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `bufio.NewReaderSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 207.4GB |
| 2 | `reflect.unsafe_NewArray` | 90.25GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 87.34GB |
| 4 | `reflect.MakeSlice` | 50.21GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 38.9GB |
| 6 | `segmentio/kafka-go.makeLayout` | 22.23GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.79GB |
| 8 | `database/sql.convertAssignRows` | 11.4GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.76GB |
| 10 | `internal/reflectlite.unsafe_New` | 10.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 543/545 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.62MB | 12/545 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/545 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 539/545 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/545 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.78MB | 16/545 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/545 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/545 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/545 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/545 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 108.78GB | 536/545 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/545 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/545 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/545 | `█████████░░░░░░ 64%` |
| 5 | `reflect.unsafe_NewArray` | 47.13GB | 536/545 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.26GB | 521/545 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/545 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/545 | `████░░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 26.31GB | 534/545 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.29GB | 521/545 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
