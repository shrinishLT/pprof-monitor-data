# Overview: stage
*Last updated: 2026-05-31 22:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-31T22:31 (805 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,236 | max: 28,205 | trend: stable (-0.46/hr))
```
▁▅▆▁▁▁▂▁▁▁▁▁▂▂▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁
```

**Heap InUse** (current: 124.1MB | avg: 168.7MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▂▂▆▁▁▃▂▄▁▁▁▁▃▃▇▃▂▂▄▇▃▂▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▃▃▂▁▁▁▁▁▂▁▂▂▁▃▄▁▁▄▄▂▂▂▄▂▄▂▁▃▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,072 | -4 | 14,236 | 28,205 | stable (-0.46/hr) |
| Heap InUse | 124.1MB | 179.7MB | -55.6MB | 168.7MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1026.4MB | 1026.4MB | +0.0MB | 1304.1MB | 1805.8MB | |
| Heap Objects | 579,437 | 1,290,185 | -710748 | 888,526 | 2,707,946 | |

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
| 2026-05-31 | 46 | 14,129 | 149.5MB | 213.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 93.98GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 76.82GB |
| 3 | `reflect.unsafe_NewArray` | 40.39GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 35.49GB |
| 5 | `reflect.MakeSlice` | 22.69GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.43GB |
| 7 | `database/sql.convertAssignRows` | 10.28GB |
| 8 | `segmentio/kafka-go.makeLayout` | 10.1GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.75GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 803/805 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.53MB | 31/805 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 18/805 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 799/805 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.3MB | 32/805 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/805 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/805 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/805 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 801/805 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/805 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.02GB | 796/805 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/805 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/805 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/805 | `████████████░░░ 80%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 42.24GB | 758/805 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.unsafe_NewArray` | 38.09GB | 796/805 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/805 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/805 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.29GB | 794/805 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.78GB | 756/805 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
