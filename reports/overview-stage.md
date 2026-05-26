# Overview: stage
*Last updated: 2026-05-26 06:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T06:01 (535 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,660 | avg: 14,271 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 299.9MB | avg: 176.4MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▂▁▃▁▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█▆▂▃▂▂▂▄▂▃▃▃▂▃▁▂▃▄▃▁▂▁▄▃▆
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 16%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,660 | 14,063 | +597 | 14,271 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 299.9MB | 198.5MB | +101.4MB | 176.4MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1749.4MB | 1749.6MB | -0.2MB | 1455.0MB | 1793.6MB | |
| Heap Objects | 849,921 | 1,222,067 | -372146 | 910,403 | 2,697,132 | |

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
| 2026-05-26 | 13 | 14,154 | 199.1MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `database/sql.convertAssignRows` | 11.5MB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 10.84MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `bufio.NewReaderSize` | 4.55MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 3.5MB |
| 9 | `bytes.growSlice` | 3.01MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 198.35GB |
| 2 | `reflect.unsafe_NewArray` | 86.35GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 77.79GB |
| 4 | `reflect.MakeSlice` | 48.03GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 34.56GB |
| 6 | `segmentio/kafka-go.makeLayout` | 21.28GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.35GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 10.31GB |
| 9 | `database/sql.convertAssignRows` | 10.15GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.72GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 533/535 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/535 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.21MB | 15/535 | `███████░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 529/535 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/535 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.83MB | 15/535 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/535 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/535 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/535 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/535 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 106.99GB | 526/535 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/535 | `██████████░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/535 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/535 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.34GB | 526/535 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.45GB | 511/535 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/535 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/535 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.88GB | 524/535 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.93GB | 511/535 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
