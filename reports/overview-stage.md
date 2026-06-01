# Overview: stage
*Last updated: 2026-06-01 22:02 IST*
*Data range: 2026-05-15T16:03 to 2026-06-01T22:02 (852 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,235 | max: 28,205 | trend: stable (-0.39/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁█▁▁▁▁▁▁▁
```

**Heap InUse** (current: 165.2MB | avg: 168.1MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▂▂▂▁▂▂▂▂▂▁▂▁▂▂▂▃▃▁▂▁▂▂▂▁▁▁▁▁▁▁▂▁▁▂▃▁▁▃▃▂▁▁▃▁▃▁▁▂▁▁▂▁▂▁▁▁▂▂▁▂▁▂▃▄▄▁▃▂▂▂▂▃▁▁▂▁▂▃▁▁▁▁▂▁▂▁█▃▅▂▂▃▁▁▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,147 | -83 | 14,235 | 28,205 | stable (-0.39/hr) |
| Heap InUse | 165.2MB | 147.5MB | +17.7MB | 168.1MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1061.8MB | 1061.6MB | +0.2MB | 1290.2MB | 1805.8MB | |
| Heap Objects | 1,121,722 | 829,791 | +291931 | 886,784 | 2,707,946 | |

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
| 2026-06-01 | 45 | 14,234 | 159.6MB | 355.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `reflect.mapassign_faststr0` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 1.51MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 136.37GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 93.35GB |
| 3 | `reflect.unsafe_NewArray` | 58.79GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 43.31GB |
| 5 | `reflect.MakeSlice` | 32.94GB |
| 6 | `segmentio/kafka-go.makeLayout` | 14.71GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 14.06GB |
| 8 | `database/sql.convertAssignRows` | 12.64GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.91GB |
| 10 | `internal/reflectlite.unsafe_New` | 6.61GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 850/852 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.37MB | 33/852 | `███████░░░░░░░░ 50%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.75MB | 21/852 | `██████░░░░░░░░░ 42%` |
| 4 | `runtime.mallocgc` | 13.68MB | 846/852 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 11.17MB | 35/852 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/852 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/852 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/852 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 848/852 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/852 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 89.56GB | 843/852 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/852 | `███████████░░░░ 79%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/852 | `███████████░░░░ 79%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/852 | `███████████░░░░ 78%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 44.84GB | 805/852 | `███████░░░░░░░░ 50%` |
| 6 | `reflect.unsafe_NewArray` | 38.74GB | 843/852 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/852 | `██████░░░░░░░░░ 40%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/852 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.MakeSlice` | 21.66GB | 841/852 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.03GB | 803/852 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
