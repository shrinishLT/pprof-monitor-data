# Overview: stage
*Last updated: 2026-06-02 20:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-02T20:32 (897 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,140 | avg: 14,231 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 188.1MB | avg: 167.5MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▁▁▂▁▁▂▁▂▁▁▁▂▂▁▂▁▂▃▄▄▁▃▂▂▂▂▃▁▁▂▁▂▃▁▁▁▁▂▁▂▁█▃▅▂▂▃▁▁▂▂▃▃▁▂▂▂▂▁▁▂▂▁▁▂▁▃▃▂▂▂▂▁▂▂▁▁▁▁▁▂▂▃▂▁▃▂▁▂▁▂▃▂▂▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,140 | 14,133 | +7 | 14,231 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 188.1MB | 171.1MB | +17.0MB | 167.5MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1550.3MB | 1550.5MB | -0.2MB | 1294.5MB | 1805.8MB | |
| Heap Objects | 1,293,436 | 1,071,671 | +221765 | 887,656 | 2,707,946 | |

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
| 2026-06-02 | 42 | 14,157 | 155.9MB | 206.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `reflect.unsafe_NewArray` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `encoding/json.typeFields` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 177.0GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 111.59GB |
| 3 | `reflect.unsafe_NewArray` | 76.31GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 51.9GB |
| 5 | `reflect.MakeSlice` | 42.86GB |
| 6 | `segmentio/kafka-go.makeLayout` | 19.03GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 16.85GB |
| 8 | `database/sql.convertAssignRows` | 15.18GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.96GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.55GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 895/897 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 35/897 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.95MB | 23/897 | `███████░░░░░░░░ 49%` |
| 4 | `runtime.mallocgc` | 13.67MB | 891/897 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.31MB | 37/897 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/897 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/897 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/897 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 893/897 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/897 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.99GB | 888/897 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/897 | `███████████░░░░ 76%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/897 | `███████████░░░░ 76%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/897 | `███████████░░░░ 75%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.91GB | 850/897 | `███████░░░░░░░░ 51%` |
| 6 | `reflect.unsafe_NewArray` | 40.21GB | 888/897 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/897 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/897 | `█████░░░░░░░░░░ 38%` |
| 9 | `reflect.MakeSlice` | 22.49GB | 886/897 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.51GB | 848/897 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
