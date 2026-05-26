# Overview: stage
*Last updated: 2026-05-26 08:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T08:01 (539 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,072 | avg: 14,270 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁
```

**Heap InUse** (current: 156.6MB | avg: 176.4MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█▆▂▃▂▂▂▄▂▃▃▃▂▃▁▂▃▄▃▁▂▁▄▃▆▄▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,072 | 14,080 | -8 | 14,270 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 156.6MB | 178.0MB | -21.4MB | 176.4MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1749.8MB | 1749.8MB | +0.0MB | 1457.2MB | 1793.6MB | |
| Heap Objects | 660,129 | 970,630 | -310501 | 909,444 | 2,697,132 | |

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
| 2026-05-26 | 17 | 14,158 | 193.6MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 201.94GB |
| 2 | `reflect.unsafe_NewArray` | 87.9GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 87.33GB |
| 4 | `reflect.MakeSlice` | 48.89GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 38.89GB |
| 6 | `segmentio/kafka-go.makeLayout` | 21.66GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.78GB |
| 8 | `database/sql.convertAssignRows` | 11.39GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.47GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.88GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 537/539 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.62MB | 12/539 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/539 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 533/539 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/539 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.78MB | 16/539 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/539 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/539 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/539 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/539 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.69GB | 530/539 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/539 | `█████████░░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/539 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/539 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.65GB | 530/539 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.78GB | 515/539 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/539 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/539 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 26.05GB | 528/539 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.07GB | 515/539 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
