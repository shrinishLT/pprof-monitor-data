# Overview: stage
*Last updated: 2026-05-26 18:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-26T18:01 (557 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,067 | avg: 14,266 | max: 28,205 | trend: stable (-0.42/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 146.0MB | avg: 175.9MB | max: 732.9MB | trend: stable (+0.13MB/hr))
```
▄▃▄▄▃▄▂▂▂▂▂▃▄▃▃▂▂▄▄▄▃▂▄▂▃▇▇▄▂▂▂▂▂▃▃▂▄▃▄▄▃▂▂▃▄▃▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,067 | 14,497 | -430 | 14,266 | 28,205 | stable (-0.42/hr) |
| Heap InUse | 146.0MB | 172.3MB | -26.3MB | 175.9MB | 732.9MB | stable (+0.13MB/hr) |
| Heap Sys | 575.6MB | 574.9MB | +0.7MB | 1452.5MB | 1805.8MB | |
| Heap Objects | 964,527 | 994,193 | -29666 | 908,019 | 2,707,946 | |

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
| 2026-05-26 | 35 | 14,160 | 177.9MB | 299.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 7.51MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `reflect.unsafe_NewArray` | 1.51MB |
| 9 | `reflect.mapassign_faststr0` | 1.5MB |
| 10 | `encoding/json.typeFields` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 4.47GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 2.21GB |
| 3 | `reflect.unsafe_NewArray` | 1.94GB |
| 4 | `reflect.MakeSlice` | 1.1GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 1001.13MB |
| 6 | `segmentio/kafka-go.makeLayout` | 478.13MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 334.51MB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 295.04MB |
| 9 | `database/sql.convertAssignRows` | 293.51MB |
| 10 | `compress/flate.NewWriter` | 246.8MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 555/557 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/557 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8MB | 17/557 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.52MB | 551/557 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.0MB | 18/557 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/557 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/557 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/557 | `███░░░░░░░░░░░░ 25%` |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.3MB | 25/557 | `███░░░░░░░░░░░░ 25%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 553/557 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 108.73GB | 548/557 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/557 | `█████████░░░░░░ 65%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/557 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/557 | `█████████░░░░░░ 64%` |
| 5 | `reflect.unsafe_NewArray` | 47.11GB | 548/557 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.31GB | 532/557 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/557 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/557 | `████░░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 26.3GB | 546/557 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.32GB | 532/557 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.0x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
