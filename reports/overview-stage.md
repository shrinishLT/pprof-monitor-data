# Overview: stage
*Last updated: 2026-05-24 17:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T17:01 (461 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,272 | max: 28,205 | trend: decreasing (-0.58/hr))
```
▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▂▁▁▁▁▁▅▂▁▁▁▁▁▁▁▁▁▁▁▃▁▁▃▁▂▁▁▁▁
```

**Heap InUse** (current: 205.7MB | avg: 173.6MB | max: 732.9MB | trend: stable (+0.17MB/hr))
```
▂▁▁▅▃▁▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,063 | +2 | 14,272 | 28,205 | decreasing (-0.58/hr) |
| Heap InUse | 205.7MB | 191.7MB | +14.0MB | 173.6MB | 732.9MB | stable (+0.17MB/hr) |
| Heap Sys | 1751.7MB | 1751.7MB | +0.0MB | 1407.6MB | 1793.6MB | |
| Heap Objects | 1,320,187 | 1,141,184 | +179003 | 890,883 | 2,697,132 | |

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
| 2026-05-24 | 35 | 14,144 | 180.4MB | 263.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 548.84kB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 131.78GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 60.54GB |
| 3 | `reflect.unsafe_NewArray` | 57.27GB |
| 4 | `reflect.MakeSlice` | 31.67GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 26.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 14.13GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.72GB |
| 8 | `database/sql.convertAssignRows` | 7.8GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.89GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.39GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 459/461 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 13/461 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.19MB | 10/461 | `███████░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.58MB | 455/461 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/461 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.54MB | 13/461 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.22MB | 20/461 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/461 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/461 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/461 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.41GB | 452/461 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/461 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/461 | `██████████░░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/461 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 42.14GB | 452/461 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.4GB | 437/461 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/461 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/461 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.55GB | 450/461 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.09GB | 437/461 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
