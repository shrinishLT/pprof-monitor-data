# Overview: stage
*Last updated: 2026-06-01 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-01T11:30 (831 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,232 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▃▁▂▂▁▂▁▂▁▁▅▄▃▃▂▁▁▁▁█▁▁▂▁▁▁▁▁▁▁▁▄▁▄▁▃▄▂▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▂▃▅▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 147.9MB | avg: 168.2MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▁▅▃▃▂▁▃▂▃▂▃▇█▁▃▂▂▃▁▂▆▂▂▃▁▃▃▂▂▃▁▃▁▂▂▃▅▄▁▃▁▂▃▂▁▁▁▁▁▂▁▂▂▁▃▄▁▁▄▄▂▂▂▄▂▄▂▁▃▁▁▃▁▃▁▂▁▂▃▁▂▁▃▄▅▆▂▄▂▂▃▂▄▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,068 | -3 | 14,232 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 147.9MB | 133.8MB | +14.1MB | 168.2MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1063.1MB | 1063.0MB | +0.1MB | 1296.0MB | 1805.8MB | |
| Heap Objects | 901,571 | 691,250 | +210321 | 886,942 | 2,707,946 | |

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
| 2026-06-01 | 24 | 14,124 | 156.4MB | 240.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `bufio.NewReaderSize` | 1.02MB |
| 10 | `regexp.onePassCopy` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 117.33GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 89.92GB |
| 3 | `reflect.unsafe_NewArray` | 50.52GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 41.73GB |
| 5 | `reflect.MakeSlice` | 28.38GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 13.47GB |
| 7 | `segmentio/kafka-go.makeLayout` | 12.66GB |
| 8 | `database/sql.convertAssignRows` | 12.08GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.94GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 829/831 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.45MB | 32/831 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.29MB | 20/831 | `██████░░░░░░░░░ 44%` |
| 4 | `runtime.mallocgc` | 13.68MB | 825/831 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.19MB | 34/831 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/831 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/831 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/831 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 827/831 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/831 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 88.6GB | 822/831 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/831 | `████████████░░░ 80%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/831 | `████████████░░░ 80%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/831 | `███████████░░░░ 79%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 43.57GB | 784/831 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.unsafe_NewArray` | 38.33GB | 822/831 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/831 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/831 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.43GB | 820/831 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.42GB | 782/831 | `███░░░░░░░░░░░░ 21%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
