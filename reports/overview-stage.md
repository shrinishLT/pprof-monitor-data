# Overview: stage
*Last updated: 2026-05-27 02:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T02:32 (574 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,255 | avg: 14,263 | max: 28,205 | trend: stable (-0.45/hr))
```
▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▇█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 183.1MB | avg: 175.1MB | max: 732.9MB | trend: stable (+0.11MB/hr))
```
▄▄▄▃▂▄▂▃▇▇▄▂▂▂▂▂▃▃▂▄▃▄▄▃▂▂▃▄▃▃▂▇█▆▃▃▃▃▃▄▃▄▃▄▃▄▂▃▄▅▄▂▃▂▄▃▆▄▂▃▂▂▃▂▂▂▄▂▂▃▂▄▆▂▂▁▂▃▂▂▂▃▂▂▂▃▂▂▁▃▁▂▁▂▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,255 | 14,458 | -203 | 14,263 | 28,205 | stable (-0.45/hr) |
| Heap InUse | 183.1MB | 144.8MB | +38.3MB | 175.1MB | 732.9MB | stable (+0.11MB/hr) |
| Heap Sys | 557.2MB | 558.8MB | -1.6MB | 1426.1MB | 1805.8MB | |
| Heap Objects | 1,190,470 | 748,301 | +442169 | 907,156 | 2,707,946 | |

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
| 2026-05-26 | 46 | 14,155 | 171.1MB | 299.9MB |
| 2026-05-27 | 6 | 14,178 | 139.5MB | 183.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `reflect.unsafe_New` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 19.86GB |
| 2 | `reflect.unsafe_NewArray` | 8.57GB |
| 3 | `reflect.MakeSlice` | 4.84GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 3.17GB |
| 5 | `segmentio/kafka-go.makeLayout` | 2.12GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.4GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 1.04GB |
| 8 | `internal/reflectlite.unsafe_New` | 1.0GB |
| 9 | `compress/flate.NewWriter` | 825.9MB |
| 10 | `fmt.Sprintf` | 599.97MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 572/574 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/574 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8MB | 17/574 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.33MB | 568/574 | `█████░░░░░░░░░░ 39%` |
| 5 | `database/sql.convertAssignRows` | 13.0MB | 18/574 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/574 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/574 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/574 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 570/574 | `███░░░░░░░░░░░░ 25%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.98MB | 26/574 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 105.84GB | 565/574 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/574 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/574 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/574 | `██████████░░░░░ 66%` |
| 5 | `reflect.unsafe_NewArray` | 45.86GB | 565/574 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.97GB | 549/574 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/574 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/574 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.6GB | 563/574 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.73GB | 549/574 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
