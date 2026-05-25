# Overview: stage
*Last updated: 2026-05-25 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T15:00 (505 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,258 | max: 28,205 | trend: decreasing (-0.74/hr))
```
▁▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
```

**Heap InUse** (current: 193.0MB | avg: 174.5MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▃▂▄▂▁▂▄▃▁▃▁▂▁▂▁▂▄▃▁▄▁▂▃▂▃▂▁▃▃▄▂▁▃▁▁▃▃▂▁▁▃▃▁▂▅▃▁▂▁▁▃▃▃▂▃▃▂▃▂▁▁▁▁▃▃▂▂▁▁▃▃▄▃▁▄▁▃▇█▃▁▁▂▁▁▂▃▁▃▃▄▄▂▁▁▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,215 | -145 | 14,258 | 28,205 | decreasing (-0.74/hr) |
| Heap InUse | 193.0MB | 150.6MB | +42.4MB | 174.5MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1751.4MB | 1751.2MB | +0.2MB | 1437.6MB | 1793.6MB | |
| Heap Objects | 1,126,869 | 544,331 | +582538 | 897,203 | 2,697,132 | |

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
| 2026-05-25 | 31 | 14,127 | 186.3MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `reflect.mapassign_faststr0` | 3.5MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 171.28GB |
| 2 | `reflect.unsafe_NewArray` | 74.57GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 73.8GB |
| 4 | `reflect.MakeSlice` | 41.45GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 32.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.39GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.73GB |
| 8 | `database/sql.convertAssignRows` | 9.55GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.93GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.38GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 503/505 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/505 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/505 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 499/505 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/505 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/505 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/505 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/505 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/505 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/505 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.26GB | 496/505 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/505 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/505 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/505 | `██████████░░░░░ 69%` |
| 5 | `reflect.unsafe_NewArray` | 44.27GB | 496/505 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.62GB | 481/505 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/505 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/505 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.73GB | 494/505 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.1GB | 481/505 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
