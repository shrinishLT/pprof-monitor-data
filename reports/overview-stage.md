# Overview: stage
*Last updated: 2026-05-28 04:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-28T04:33 (625 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,080 | avg: 14,254 | max: 28,205 | trend: decreasing (-0.50/hr))
```
▁▁▁▁▁█▅▁▁▁▁▁▁▂▁▁▁▁▄▁▅▆▁▁▁▁▆▁▁▁▄▆▁▁▁▁▁▁▁▁▂▁▁▅▃▂▁▂▇▁▁▄▅▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▆▁▁▃▄▃▃▁▃▄▂▃▁▄▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 172.4MB | avg: 173.1MB | max: 732.9MB | trend: stable (+0.05MB/hr))
```
▃▄▂▅▄█▅▂▃▃▂▃▂▂▂▄▂▃▄▃▅▇▂▂▁▃▃▂▂▃▃▂▂▃▃▂▂▁▃▁▃▁▂▂▄▃▁▂▄▃▃▅▂▄▂▄▂▂▂▃▂▁▃▃▁▃▄▂▃▂▂▁▃▃▃▂▄▁▂▂▄▃▂▃▂▁▁▁▁▁▃▁▃▃▄▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,080 | 14,138 | -58 | 14,254 | 28,205 | decreasing (-0.50/hr) |
| Heap InUse | 172.4MB | 185.4MB | -13.0MB | 173.1MB | 732.9MB | stable (+0.05MB/hr) |
| Heap Sys | 1307.7MB | 1307.7MB | +0.0MB | 1409.2MB | 1805.8MB | |
| Heap Objects | 1,141,476 | 1,284,947 | -143471 | 901,031 | 2,707,946 | |

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
| 2026-05-28 | 10 | 14,079 | 141.3MB | 185.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `encoding/json.typeFields` | 1.0MB |
| 9 | `aws/endpoints.init` | 1.0MB |
| 10 | `reflect.unsafe_NewArray` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 66.89GB |
| 2 | `reflect.unsafe_NewArray` | 28.73GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.55GB |
| 4 | `reflect.MakeSlice` | 16.35GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 8.38GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.28GB |
| 7 | `bytes.growSlice` | 5.06GB |
| 8 | `fips140/sha256.New` | 3.5GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.44GB |
| 10 | `bufio.NewWriterSize` | 3.3GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 623/625 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.82MB | 18/625 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.76MB | 13/625 | `███████░░░░░░░░ 51%` |
| 4 | `runtime.mallocgc` | 14.1MB | 619/625 | `█████░░░░░░░░░░ 38%` |
| 5 | `database/sql.convertAssignRows` | 12.97MB | 19/625 | `█████░░░░░░░░░░ 35%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/625 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/625 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/625 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 621/625 | `███░░░░░░░░░░░░ 25%` |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 8.75MB | 2/625 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.7GB | 616/625 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/625 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/625 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/625 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.62GB | 616/625 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.47GB | 600/625 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/625 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/625 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.36GB | 614/625 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.65GB | 600/625 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
