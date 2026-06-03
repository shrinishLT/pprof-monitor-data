# Overview: stage
*Last updated: 2026-06-03 23:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T23:02 (950 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,226 | max: 28,205 | trend: stable (-0.38/hr))
```
▂▁▁▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅▁▁▁▁▁
```

**Heap InUse** (current: 166.8MB | avg: 166.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▁▂▃▃▃▂▂▃▄▁▂▃▁▄▄▂▃▃▃▁▃▄▁▁▁▁▂▃▃▄▃▁▅▃▂▃▂▃▄▃▂▃▄▄▃▄▁▂▄▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▁▄▂▃▄▁▄▁▁▁▁▄▃▂▂▄▃▂▂█▃▁▃▄▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,076 | -8 | 14,226 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 166.8MB | 178.2MB | -11.4MB | 166.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 899.7MB | 899.4MB | +0.3MB | 1301.8MB | 1805.8MB | |
| Heap Objects | 1,193,651 | 1,268,870 | -75219 | 888,087 | 2,707,946 | |

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
| 2026-06-03 | 47 | 14,146 | 155.0MB | 260.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.58MB |
| 4 | `compress/flate.NewWriter` | 4.41MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 6 | `aws/endpoints.init` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.59GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 6.07GB |
| 3 | `segmentio/kafka-go.makePartitions` | 5.89GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 2.99GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 2.96GB |
| 6 | `internal/evaluation.mergeMetadata` | 2.91GB |
| 7 | `reflect.unsafe_NewArray` | 2.62GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 1.88GB |
| 9 | `database/sql.convertAssignRows` | 1.66GB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 1.56GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 948/950 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/950 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/950 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.61MB | 944/950 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/950 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/950 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/950 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/950 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 946/950 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/950 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.23GB | 941/950 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 69.62GB | 293/950 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 69.33GB | 292/950 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 68.67GB | 287/950 | `██████████░░░░░ 70%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.3GB | 901/950 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.07GB | 940/950 | `██████░░░░░░░░░ 43%` |
| 7 | `experiment/local.topologicalSort` | 35.72GB | 282/950 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 35.59GB | 288/950 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.67GB | 933/950 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.14GB | 899/950 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
