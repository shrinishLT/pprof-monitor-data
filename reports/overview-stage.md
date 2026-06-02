# Overview: stage
*Last updated: 2026-06-02 06:31 IST*
*Data range: 2026-05-15T16:03 to 2026-06-02T06:30 (869 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,309 | avg: 14,234 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁
```

**Heap InUse** (current: 192.5MB | avg: 167.9MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▁▂▁▂▂▂▁▁▁▁▁▁▁▂▁▁▂▃▁▁▃▃▂▁▁▃▁▃▁▁▂▁▁▂▁▂▁▁▁▂▂▁▂▁▂▃▄▄▁▃▂▂▂▂▃▁▁▂▁▂▃▁▁▁▁▂▁▂▁█▃▅▂▂▃▁▁▂▂▃▃▁▂▂▂▂▁▁▂▂▁▁▂▁▃▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,309 | 14,074 | +235 | 14,234 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 192.5MB | 187.7MB | +4.8MB | 167.9MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1549.9MB | 1061.8MB | +488.1MB | 1286.3MB | 1805.8MB | |
| Heap Objects | 1,125,292 | 1,384,813 | -259521 | 887,632 | 2,707,946 | |

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
| 2026-06-02 | 14 | 14,157 | 155.9MB | 192.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.94MB |
| 3 | `runtime.mallocgc` | 13.6MB |
| 4 | `database/sql.convertAssignRows` | 10.0MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bytes.growSlice` | 7.03MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `dotlapse-event-service/project.ApplyPagination` | 4.34MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 10 | `bufio.NewWriterSize` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 151.6GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 104.17GB |
| 3 | `reflect.unsafe_NewArray` | 65.32GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 48.38GB |
| 5 | `reflect.MakeSlice` | 36.64GB |
| 6 | `segmentio/kafka-go.makeLayout` | 16.29GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 15.69GB |
| 8 | `database/sql.convertAssignRows` | 14.13GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 7.69GB |
| 10 | `internal/reflectlite.unsafe_New` | 7.35GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 867/869 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.3MB | 34/869 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.24MB | 22/869 | `██████░░░░░░░░░ 41%` |
| 4 | `runtime.mallocgc` | 13.67MB | 863/869 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.14MB | 36/869 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/869 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/869 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/869 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 865/869 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/869 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 90.65GB | 860/869 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/869 | `███████████░░░░ 78%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/869 | `███████████░░░░ 78%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/869 | `███████████░░░░ 77%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 45.85GB | 822/869 | `███████░░░░░░░░ 50%` |
| 6 | `reflect.unsafe_NewArray` | 39.2GB | 860/869 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/869 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/869 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 21.92GB | 858/869 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.52GB | 820/869 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
