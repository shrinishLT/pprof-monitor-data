# Overview: stage
*Last updated: 2026-05-26 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T07:01 (537 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,086 | avg: 14,271 | max: 28,205 | trend: stable (-0.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 136.6MB | avg: 176.4MB | max: 732.9MB | trend: stable (+0.16MB/hr))
```
▃▁▁▂▃▂▁▁▃▃▁▂▅▃▁▂▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▃▃▂▂▁▁▃▃▄▂▁▄▁▂▆▇▃▁▁▁▁▁▂▃▁▃▂▄▃▂▁▁▃▃▂▃▂▇█▆▂▃▂▂▂▄▂▃▃▃▂▃▁▂▃▄▃▁▂▁▄▃▆▄▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,086 | 14,433 | -347 | 14,271 | 28,205 | stable (-0.37/hr) |
| Heap InUse | 136.6MB | 231.9MB | -95.3MB | 176.4MB | 732.9MB | stable (+0.16MB/hr) |
| Heap Sys | 1750.8MB | 1749.6MB | +1.2MB | 1456.1MB | 1793.6MB | |
| Heap Objects | 257,313 | 1,236,502 | -979189 | 909,794 | 2,697,132 | |

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
| 2026-05-26 | 15 | 14,168 | 197.1MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.01MB |
| 8 | `bufio.NewReaderSize` | 1.03MB |
| 9 | `regexp.(*bitState).reset` | 1.03MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 200.14GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 87.33GB |
| 3 | `reflect.unsafe_NewArray` | 87.13GB |
| 4 | `reflect.MakeSlice` | 48.42GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 38.89GB |
| 6 | `segmentio/kafka-go.makeLayout` | 21.47GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 12.78GB |
| 8 | `database/sql.convertAssignRows` | 11.39GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.39GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.8GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 535/537 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.62MB | 12/537 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08MB | 16/537 | `██████░░░░░░░░░ 46%` |
| 4 | `runtime.mallocgc` | 14.59MB | 531/537 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/537 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.78MB | 16/537 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/537 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/537 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/537 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/537 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 107.34GB | 528/537 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/537 | `█████████░░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/537 | `█████████░░░░░░ 66%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/537 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.5GB | 528/537 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 45.62GB | 513/537 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/537 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/537 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.96GB | 526/537 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.0GB | 513/537 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
