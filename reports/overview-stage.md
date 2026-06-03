# Overview: stage
*Last updated: 2026-06-03 16:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T16:32 (937 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,234 | avg: 14,227 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▇▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 184.5MB | avg: 166.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁█▃▅▂▂▃▁▁▁▂▂▃▁▂▂▂▂▁▁▂▂▁▁▂▁▃▃▂▂▂▂▁▂▂▁▁▁▁▁▂▂▃▂▁▃▂▁▂▁▂▃▂▂▂▃▃▂▃▁▁▃▂▂▃▁▂▃▁▁▂▂▁▂▂▃▁▁▁▁▁▁▁▂▁▃▁▂▃▁▃▁▁▁▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,234 | 14,078 | +156 | 14,227 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 184.5MB | 120.9MB | +63.6MB | 166.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 1550.4MB | 1550.7MB | -0.3MB | 1305.4MB | 1805.8MB | |
| Heap Objects | 1,223,386 | 444,437 | +778949 | 887,071 | 2,707,946 | |

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
| 2026-06-03 | 34 | 14,139 | 151.3MB | 191.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `reflect.unsafe_NewArray` | 2.52MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.5MB |
| 9 | `reflect.unsafe_New` | 1.5MB |
| 10 | `bytes.growSlice` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 213.09GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 129.12GB |
| 3 | `reflect.unsafe_NewArray` | 91.9GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 60.38GB |
| 5 | `reflect.MakeSlice` | 51.65GB |
| 6 | `segmentio/kafka-go.makeLayout` | 22.87GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 19.51GB |
| 8 | `database/sql.convertAssignRows` | 17.56GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 10.8GB |
| 10 | `internal/reflectlite.unsafe_New` | 10.36GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 935/937 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 35/937 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/937 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.67MB | 931/937 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.31MB | 37/937 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/937 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/937 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/937 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 933/937 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/937 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.41GB | 928/937 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/937 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/937 | `██████████░░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/937 | `██████████░░░░░ 72%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.12GB | 890/937 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.11GB | 928/937 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/937 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/937 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.56GB | 926/937 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.05GB | 888/937 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
