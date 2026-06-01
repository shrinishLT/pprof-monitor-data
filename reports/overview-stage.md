# Overview: stage
*Last updated: 2026-06-01 05:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-01T05:32 (819 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,233 | avg: 14,233 | max: 28,205 | trend: stable (-0.47/hr))
```
▃▄▁▁▅▃▁▁▁▁▁▁▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▂
```

**Heap InUse** (current: 184.3MB | avg: 168.3MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▇▃▂▁▄▇▃▁▁▃▁▄▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▂▃▂▁▁▁▁▁▂▁▂▂▁▃▄▁▁▄▄▂▂▂▄▂▄▂▁▃▁▁▃▁▃▁▂▁▂▃▁▂▁▃▄
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,233 | 14,066 | +167 | 14,233 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 184.3MB | 179.7MB | +4.6MB | 168.3MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1026.4MB | 1026.4MB | +0.0MB | 1299.4MB | 1805.8MB | |
| Heap Objects | 1,252,865 | 1,262,344 | -9479 | 887,231 | 2,707,946 | |

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
| 2026-06-01 | 12 | 14,111 | 146.6MB | 184.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.5MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 106.65GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 76.82GB |
| 3 | `reflect.unsafe_NewArray` | 45.91GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 35.49GB |
| 5 | `reflect.MakeSlice` | 25.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 11.46GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 11.45GB |
| 8 | `database/sql.convertAssignRows` | 10.3GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.39GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.18GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 817/819 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.53MB | 31/819 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.3MB | 18/819 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 813/819 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.3MB | 32/819 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/819 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/819 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/819 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 815/819 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/819 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.25GB | 810/819 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/819 | `████████████░░░ 81%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/819 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/819 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 42.86GB | 772/819 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.unsafe_NewArray` | 38.18GB | 810/819 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/819 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/819 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.34GB | 808/819 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.08GB | 770/819 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
