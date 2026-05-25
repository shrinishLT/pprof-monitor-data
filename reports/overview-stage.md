# Overview: stage
*Last updated: 2026-05-25 09:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T09:01 (493 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,262 | max: 28,205 | trend: decreasing (-0.69/hr))
```
▁▁▂▁▁▁▂▁▁▂▂▁▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁
```

**Heap InUse** (current: 135.3MB | avg: 174.4MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▂▃▂▂▁▁▂▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▂▃▂▂▁▁▃▂▃▂▁▃▁▂▆▆▃▁▁▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,066 | +1 | 14,262 | 28,205 | decreasing (-0.69/hr) |
| Heap InUse | 135.3MB | 162.2MB | -26.9MB | 174.4MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1751.2MB | 1751.2MB | +0.0MB | 1429.9MB | 1793.6MB | |
| Heap Objects | 368,148 | 764,527 | -396379 | 895,303 | 2,697,132 | |

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
| 2026-05-25 | 19 | 14,150 | 189.5MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `reflect.unsafe_NewArray` | 2.52MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `bufio.NewWriterSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 160.53GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 72.61GB |
| 3 | `reflect.unsafe_NewArray` | 69.91GB |
| 4 | `reflect.MakeSlice` | 38.83GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 32.25GB |
| 6 | `segmentio/kafka-go.makeLayout` | 17.24GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.55GB |
| 8 | `database/sql.convertAssignRows` | 9.4GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.38GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.82GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 491/493 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/493 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/493 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.58MB | 487/493 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/493 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/493 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/493 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/493 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/493 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/493 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.67GB | 484/493 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/493 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/493 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/493 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.57GB | 484/493 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.87GB | 469/493 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/493 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/493 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.34GB | 482/493 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.76GB | 469/493 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
