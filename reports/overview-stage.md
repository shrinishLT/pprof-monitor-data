# Overview: stage
*Last updated: 2026-06-03 20:33 IST*
*Data range: 2026-05-15T16:03 to 2026-06-03T20:33 (945 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,529 | avg: 14,227 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▂▁▁▁▁▅▁▁▄▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▁▃▁▃▄▁█▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▁▁▂▂▁▃▁▅▁▁▁▁▁▁▁▁▁▁▁▁▃▁▄▁▂▁▁▂▄▁▁▁▂▁▁▅
```

**Heap InUse** (current: 260.4MB | avg: 166.9MB | max: 732.9MB | trend: stable (-0.04MB/hr))
```
▂▂▃▄▄▁▂▃▃▃▂▂▃▄▁▂▃▁▄▄▂▃▃▃▁▃▄▁▁▁▁▂▃▃▄▃▁▅▃▂▃▂▃▄▃▂▃▄▄▃▄▁▂▄▃▄▄▂▃▄▂▂▃▃▁▃▃▄▁▂▂▁▁▂▁▃▁▄▂▃▄▁▄▁▁▁▁▄▃▂▂▄▃▂▂█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 14%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,529 | 14,119 | +410 | 14,227 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 260.4MB | 137.3MB | +123.1MB | 166.9MB | 732.9MB | stable (-0.04MB/hr) |
| Heap Sys | 903.3MB | 192.2MB | +711.1MB | 1304.0MB | 1805.8MB | |
| Heap Objects | 1,134,483 | 824,723 | +309760 | 886,923 | 2,707,946 | |

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
| 2026-06-03 | 42 | 14,155 | 153.9MB | 260.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 8.5MB |
| 4 | `runtime.mallocgc` | 6.08MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 6 | `database/sql.convertAssignRows` | 5.5MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 3.5MB |
| 8 | `bytes.growSlice` | 3.02MB |
| 9 | `aws/endpoints.init` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 6.41GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 3.1GB |
| 3 | `segmentio/kafka-go.makePartitions` | 1.47GB |
| 4 | `experiment/local.(*Client).EvaluateV2` | 1.15GB |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 1.15GB |
| 6 | `internal/evaluation.mergeMetadata` | 1.14GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 956.52MB |
| 8 | `database/sql.convertAssignRows` | 859.54MB |
| 9 | `reflect.unsafe_NewArray` | 654.69MB |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 618.67MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 943/945 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.96MB | 36/945 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.29MB | 24/945 | `███████░░░░░░░░ 47%` |
| 4 | `runtime.mallocgc` | 13.65MB | 939/945 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.13MB | 38/945 | `████░░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/945 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/945 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/945 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 941/945 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/945 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.73GB | 936/945 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 70.78GB | 288/945 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.49GB | 287/945 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 69.84GB | 282/945 | `██████████░░░░░ 71%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 51.51GB | 896/945 | `███████░░░░░░░░ 52%` |
| 6 | `reflect.unsafe_NewArray` | 42.24GB | 936/945 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.2GB | 283/945 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.84GB | 281/945 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.67GB | 933/945 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 23.24GB | 894/945 | `███░░░░░░░░░░░░ 23%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
