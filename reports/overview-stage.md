# Overview: stage
*Last updated: 2026-05-25 16:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-25T16:32 (508 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,086 | avg: 14,258 | max: 28,205 | trend: decreasing (-0.74/hr))
```
▁▁▁▃▁▁▁▁▁▂▁▃▁▁▂▁▁▂▁▁▃▁▂▂▁▁█▃▂▁▁▁▁▁▁▁▁▁▁▅▁▁▄▁▃▂▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▁▂▁▁▁▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃▂▁
```

**Heap InUse** (current: 198.7MB | avg: 174.7MB | max: 732.9MB | trend: stable (+0.15MB/hr))
```
▂▁▂▄▃▁▃▁▂▁▂▁▂▄▃▁▄▁▂▃▂▃▂▁▃▃▄▂▁▃▁▁▃▃▂▁▁▃▃▁▂▅▃▁▂▁▁▃▃▃▂▃▃▂▃▂▁▁▁▁▃▃▂▂▁▁▃▃▄▃▁▄▁▃▇█▃▁▁▂▁▁▂▃▁▃▃▄▄▂▁▁▃▄▃▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,086 | 14,163 | -77 | 14,258 | 28,205 | decreasing (-0.74/hr) |
| Heap InUse | 198.7MB | 188.7MB | +10.0MB | 174.7MB | 732.9MB | stable (+0.15MB/hr) |
| Heap Sys | 1750.5MB | 1750.5MB | +0.0MB | 1439.4MB | 1793.6MB | |
| Heap Objects | 1,207,700 | 1,054,017 | +153683 | 899,001 | 2,697,132 | |

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
| 2026-05-25 | 34 | 14,132 | 187.7MB | 315.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 174.1GB |
| 2 | `reflect.unsafe_NewArray` | 75.76GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 74.46GB |
| 4 | `reflect.MakeSlice` | 42.12GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 33.06GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.71GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 10.82GB |
| 8 | `database/sql.convertAssignRows` | 9.63GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 9.07GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.52GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 506/508 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 17.75MB | 11/508 | `███████░░░░░░░░ 48%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66MB | 14/508 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.59MB | 502/508 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/508 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.93MB | 14/508 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/508 | `████░░░░░░░░░░░ 27%` |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.81MB | 21/508 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/508 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/508 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.68GB | 499/508 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/508 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/508 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/508 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.46GB | 499/508 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.81GB | 484/508 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/508 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/508 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.83GB | 497/508 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.18GB | 484/508 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
