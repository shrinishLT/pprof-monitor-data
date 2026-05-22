# Overview: stage
*Last updated: 2026-05-22 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T06:00 (343 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,448 | avg: 14,314 | max: 28,205 | trend: INCREASING (+0.58/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 230.0MB | avg: 170.9MB | max: 732.9MB | trend: stable (+0.28MB/hr))
```
▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,448 | 14,063 | +385 | 14,314 | 28,205 | INCREASING (+0.58/hr) |
| Heap InUse | 230.0MB | 211.0MB | +19.0MB | 170.9MB | 732.9MB | stable (+0.28MB/hr) |
| Heap Sys | 1580.4MB | 1344.8MB | +235.6MB | 1312.1MB | 1793.6MB | |
| Heap Objects | 984,139 | 1,409,171 | -425032 | 883,553 | 2,432,873 | |

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
| 2026-05-22 | 15 | 14,121 | 193.7MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 45.28MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 14.83MB |
| 4 | `runtime.mallocgc` | 14.67MB |
| 5 | `database/sql.convertAssignRows` | 14.5MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 9 | `bufio.NewReaderSize` | 2.55MB |
| 10 | `bufio.NewWriterSize` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 25.25GB |
| 2 | `reflect.unsafe_NewArray` | 11.03GB |
| 3 | `reflect.MakeSlice` | 6.15GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 5.26GB |
| 5 | `segmentio/kafka-go.makeLayout` | 2.71GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 2.31GB |
| 7 | `fmt.Sprintf` | 1.97GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 1.46GB |
| 9 | `internal/reflectlite.unsafe_New` | 1.21GB |
| 10 | `compress/flate.NewWriter` | 1011.0MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 341/343 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/343 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.55MB | 337/343 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/343 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/343 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/343 | `████░░░░░░░░░░░ 33%` |
| 7 | `bytes.growSlice` | 10.64MB | 54/343 | `████░░░░░░░░░░░ 29%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/343 | `████░░░░░░░░░░░ 27%` |
| 9 | `database/sql.convertAssignRows` | 9.88MB | 8/343 | `████░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/343 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 103.92GB | 334/343 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/343 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/343 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/343 | `██████████░░░░░ 67%` |
| 5 | `reflect.unsafe_NewArray` | 44.9GB | 334/343 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.52GB | 319/343 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/343 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/343 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 25.16GB | 332/343 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.51GB | 319/343 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
