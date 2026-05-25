# Overview: stage
*Last updated: 2026-05-25 15:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T15:32 (506 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,304 | avg: 14,258 | max: 28,205 | trend: decreasing (-0.73/hr))
```
▁▂▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃
```

**Heap InUse** (current: 216.3MB | avg: 174.6MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▂▄▂▁▂▄▃▁▃▁▂▁▂▁▂▄▃▁▄▁▂▃▂▃▂▁▃▃▄▂▁▃▁▁▃▃▂▁▁▃▃▁▂▅▃▁▂▁▁▃▃▃▂▃▃▂▃▂▁▁▁▁▃▃▂▂▁▁▃▃▄▃▁▄▁▃▇█▃▁▁▂▁▁▂▃▁▃▃▄▄▂▁▁▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,304 | 14,070 | +234 | 14,258 | 28,205 | decreasing (-0.73/hr) |
| Heap InUse | 216.3MB | 193.0MB | +23.3MB | 174.6MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1750.2MB | 1751.4MB | -1.2MB | 1438.2MB | 1793.6MB | |
| Heap Objects | 1,343,149 | 1,126,869 | +216280 | 898,084 | 2,697,132 | |

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
| 2026-05-25 | 32 | 14,133 | 187.3MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.53MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `reflect.unsafe_NewArray` | 1.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 172.35GB |
| 2 | `reflect.unsafe_NewArray` | 75.02GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 73.8GB |
| 4 | `reflect.MakeSlice` | 41.7GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 32.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.51GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.73GB |
| 8 | `database/sql.convertAssignRows` | 9.56GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.98GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.43GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 504/506 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/506 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/506 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 500/506 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/506 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/506 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/506 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/506 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/506 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/506 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.4GB | 497/506 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/506 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/506 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/506 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.33GB | 497/506 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.68GB | 482/506 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/506 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/506 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.76GB | 495/506 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.13GB | 482/506 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
