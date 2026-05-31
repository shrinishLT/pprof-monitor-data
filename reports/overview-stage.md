# Overview: stage
*Last updated: 2026-06-01 03:00 IST*
*Data range: 2026-05-15T16:03 to 2026-06-01T03:00 (814 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,066 | avg: 14,234 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▁▁▂▂▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁
```

**Heap InUse** (current: 179.7MB | avg: 168.4MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▁▁▁▃▃▇▃▂▁▄▇▃▁▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▃▃▂▁▁▁▁▁▂▁▂▂▁▃▄▁▁▄▄▂▂▂▄▂▄▂▁▃▁▁▃▁▃▁▂▁▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,066 | 14,185 | -119 | 14,234 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 179.7MB | 154.0MB | +25.7MB | 168.4MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1025.8MB | 1025.5MB | +0.3MB | 1301.0MB | 1805.8MB | |
| Heap Objects | 1,271,091 | 881,825 | +389266 | 887,654 | 2,707,946 | |

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
| 2026-05-27 | 47 | 14,177 | 151.2MB | 232.3MB |
| 2026-05-28 | 48 | 14,161 | 148.6MB | 218.1MB |
| 2026-05-29 | 48 | 14,166 | 148.6MB | 258.2MB |
| 2026-05-30 | 48 | 14,205 | 164.1MB | 277.7MB |
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 7 | 14,094 | 144.9MB | 179.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 102.12GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 76.82GB |
| 3 | `reflect.unsafe_NewArray` | 43.96GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 35.49GB |
| 5 | `reflect.MakeSlice` | 24.66GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.44GB |
| 7 | `segmentio/kafka-go.makeLayout` | 10.97GB |
| 8 | `database/sql.convertAssignRows` | 10.3GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.16GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.96GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 812/814 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.53MB | 31/814 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 18/814 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 808/814 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.3MB | 32/814 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/814 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/814 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/814 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 810/814 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/814 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.14GB | 805/814 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/814 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/814 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/814 | `████████████░░░ 80%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 42.64GB | 767/814 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.unsafe_NewArray` | 38.14GB | 805/814 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/814 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/814 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.32GB | 803/814 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.98GB | 765/814 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
