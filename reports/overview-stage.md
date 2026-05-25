# Overview: stage
*Last updated: 2026-05-25 14:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T14:03 (503 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,168 | avg: 14,259 | max: 28,205 | trend: decreasing (-0.74/hr))
```
▂▁▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 153.5MB | avg: 174.5MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▂▃▃▁▃▁▁▃▂▂▂▁▂▃▃▂▁▃▁▁▂▂▂▁▁▃▃▁▂▄▃▁▁▁▁▂▃▃▂▃▃▂▃▁▁▁▁▁▂▃▂▂▁▁▃▂▃▂▁▃▁▂▆▆▃▁▁▁▁▁▂▂▁▃▂▃▃▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,168 | 14,068 | +100 | 14,259 | 28,205 | decreasing (-0.74/hr) |
| Heap InUse | 153.5MB | 179.1MB | -25.6MB | 174.5MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1751.0MB | 1751.2MB | -0.2MB | 1436.3MB | 1793.6MB | |
| Heap Objects | 580,040 | 954,346 | -374306 | 897,448 | 2,697,132 | |

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
| 2026-05-25 | 29 | 14,126 | 187.3MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `bytes.growSlice` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 169.57GB |
| 2 | `reflect.unsafe_NewArray` | 73.88GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 73.65GB |
| 4 | `reflect.MakeSlice` | 41.05GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 32.72GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.21GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.71GB |
| 8 | `database/sql.convertAssignRows` | 9.53GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.84GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.29GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 501/503 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/503 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/503 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 497/503 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/503 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/503 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/503 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/503 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/503 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/503 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.98GB | 494/503 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/503 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/503 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/503 | `██████████░░░░░ 69%` |
| 5 | `reflect.unsafe_NewArray` | 44.15GB | 494/503 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.5GB | 479/503 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/503 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/503 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.66GB | 492/503 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.04GB | 479/503 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
