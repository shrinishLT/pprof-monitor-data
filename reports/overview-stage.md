# Overview: stage
*Last updated: 2026-05-25 03:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T03:31 (482 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,264 | max: 28,205 | trend: decreasing (-0.70/hr))
```
▁▄▁▁▇▅▁▁▂▁▁▁▁▂▁▁▁▂▁▁▂▂▁▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁
```

**Heap InUse** (current: 188.1MB | avg: 173.9MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▂▃▂▂▁▁▃▂▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,179 | -113 | 14,264 | 28,205 | decreasing (-0.70/hr) |
| Heap InUse | 188.1MB | 230.1MB | -42.0MB | 173.9MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1750.9MB | 1750.8MB | +0.1MB | 1422.6MB | 1793.6MB | |
| Heap Objects | 1,102,981 | 1,564,168 | -461187 | 894,505 | 2,697,132 | |

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
| 2026-05-25 | 8 | 14,093 | 183.4MB | 230.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `regexp.(*bitState).reset` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 150.6GB |
| 2 | `reflect.unsafe_NewArray` | 65.52GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 60.54GB |
| 4 | `reflect.MakeSlice` | 36.36GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 26.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 16.19GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.74GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 7.85GB |
| 9 | `database/sql.convertAssignRows` | 7.83GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.33GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 480/482 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.86MB | 13/482 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.19MB | 10/482 | `███████░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.58MB | 476/482 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/482 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.54MB | 13/482 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.22MB | 20/482 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/482 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/482 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/482 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.38GB | 473/482 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/482 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/482 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/482 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 43.0GB | 473/482 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.28GB | 458/482 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/482 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/482 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.03GB | 471/482 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.49GB | 458/482 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
