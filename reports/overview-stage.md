# Overview: stage
*Last updated: 2026-05-27 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-27T19:31 (608 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,283 | avg: 14,258 | max: 28,205 | trend: stable (-0.47/hr))
```
▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▅▂▁▁▁▁▁█▅▁▁▁▁▁▁▂▁▁▁▁▄▁▅▆▁▁▁▁▆▁▁▁▄▆▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▇▁▁▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▄▃▃▁▃
```

**Heap InUse** (current: 135.5MB | avg: 173.9MB | max: 732.9MB | trend: stable (+0.07MB/hr))
```
▃▄▃▃▄▅▃▄▄▅▄▅▃▃▄▅▄▃▄▂▅▄█▅▂▃▃▂▃▂▂▂▄▂▃▄▃▅▇▂▂▁▃▃▂▂▃▃▂▂▃▃▂▂▁▃▁▃▁▂▂▄▃▁▂▄▃▃▅▂▄▂▄▂▂▂▃▂▁▃▃▁▃▄▂▃▂▂▁▃▃▃▂▄▁▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,283 | 14,065 | +218 | 14,258 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 135.5MB | 119.5MB | +16.0MB | 173.9MB | 732.9MB | stable (+0.07MB/hr) |
| Heap Sys | 1307.7MB | 1308.0MB | -0.3MB | 1412.1MB | 1805.8MB | |
| Heap Objects | 583,274 | 537,827 | +45447 | 904,226 | 2,707,946 | |

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
| 2026-05-27 | 40 | 14,173 | 151.8MB | 232.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.52MB |
| 9 | `reflect.unsafe_NewArray` | 1.5MB |
| 10 | `compress/flate.(*dictDecoder).init` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 50.66GB |
| 2 | `reflect.unsafe_NewArray` | 21.73GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.54GB |
| 4 | `reflect.MakeSlice` | 12.42GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.38GB |
| 6 | `segmentio/kafka-go.makeLayout` | 5.45GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.83GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 2.62GB |
| 9 | `database/sql.convertAssignRows` | 2.51GB |
| 10 | `internal/reflectlite.unsafe_New` | 2.5GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 606/608 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82MB | 18/608 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/608 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.17MB | 602/608 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.97MB | 19/608 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/608 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/608 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/608 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 604/608 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/608 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.87GB | 599/608 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/608 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/608 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/608 | `██████████░░░░░ 69%` |
| 5 | `reflect.unsafe_NewArray` | 44.13GB | 599/608 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.17GB | 583/608 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/608 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/608 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.64GB | 597/608 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.95GB | 583/608 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.6x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
