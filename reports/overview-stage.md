# Overview: stage
*Last updated: 2026-06-03 02:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T02:02 (908 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,289 | avg: 14,230 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 159.5MB | avg: 167.5MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▂▂▁▂▁▂▃▄▄▁▃▂▂▂▂▃▁▁▂▁▂▃▁▁▁▁▂▁▂▁█▃▅▂▂▃▁▁▂▂▃▃▁▂▂▂▂▁▁▂▂▁▁▂▁▃▃▂▂▂▂▁▂▂▁▁▁▁▁▂▂▃▂▁▃▂▁▂▁▂▃▂▂▂▃▃▂▃▁▁▃▂▂▃▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,289 | 14,069 | +220 | 14,230 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 159.5MB | 145.7MB | +13.8MB | 167.5MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1550.2MB | 1550.4MB | -0.2MB | 1297.6MB | 1805.8MB | |
| Heap Objects | 934,279 | 848,034 | +86245 | 890,020 | 2,707,946 | |

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
| 2026-06-01 | 48 | 14,226 | 160.1MB | 355.0MB |
| 2026-06-02 | 48 | 14,148 | 157.1MB | 206.0MB |
| 2026-06-03 | 5 | 14,112 | 168.6MB | 191.1MB |

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
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `regexp.onePassCopy` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 186.97GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 111.64GB |
| 3 | `reflect.unsafe_NewArray` | 80.56GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 51.93GB |
| 5 | `reflect.MakeSlice` | 45.29GB |
| 6 | `segmentio/kafka-go.makeLayout` | 20.09GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 16.87GB |
| 8 | `database/sql.convertAssignRows` | 15.2GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 9.47GB |
| 10 | `internal/reflectlite.unsafe_New` | 9.08GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 906/908 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 35/908 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/908 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.67MB | 902/908 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.31MB | 37/908 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/908 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/908 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/908 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 904/908 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/908 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 94.08GB | 899/908 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/908 | `███████████░░░░ 76%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/908 | `███████████░░░░ 75%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/908 | `███████████░░░░ 75%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 48.72GB | 861/908 | `███████░░░░░░░░ 51%` |
| 6 | `reflect.unsafe_NewArray` | 40.68GB | 899/908 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/908 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/908 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 22.75GB | 897/908 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.9GB | 859/908 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
