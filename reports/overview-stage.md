# Overview: stage
*Last updated: 2026-05-22 18:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T18:30 (368 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,449 | avg: 14,304 | max: 28,205 | trend: stable (+0.18/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 160.2MB | avg: 171.5MB | max: 732.9MB | trend: stable (+0.24MB/hr))
```
▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▂▂▂▂▁▁▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,449 | 14,078 | +371 | 14,304 | 28,205 | stable (+0.18/hr) |
| Heap InUse | 160.2MB | 138.1MB | +22.1MB | 171.5MB | 732.9MB | stable (+0.24MB/hr) |
| Heap Sys | 1586.1MB | 1584.8MB | +1.3MB | 1330.5MB | 1793.6MB | |
| Heap Objects | 377,357 | 442,346 | -64989 | 884,534 | 2,432,873 | |

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
| 2026-05-22 | 40 | 14,153 | 184.5MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 6.17MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 7 | `bufio.NewReaderSize` | 3.05MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `reflect.unsafe_NewArray` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 47.82GB |
| 2 | `reflect.unsafe_NewArray` | 20.76GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 18.03GB |
| 4 | `reflect.MakeSlice` | 11.56GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.93GB |
| 6 | `segmentio/kafka-go.makeLayout` | 5.15GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 2.59GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.56GB |
| 9 | `fmt.Sprintf` | 2.52GB |
| 10 | `database/sql.convertAssignRows` | 2.39GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 366/368 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/368 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.56MB | 362/368 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/368 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/368 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/368 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/368 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.88MB | 8/368 | `████░░░░░░░░░░░ 26%` |
| 9 | `bytes.growSlice` | 9.67MB | 61/368 | `███░░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/368 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.26GB | 359/368 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/368 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/368 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/368 | `██████████░░░░░ 71%` |
| 5 | `reflect.unsafe_NewArray` | 42.9GB | 359/368 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.6GB | 344/368 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/368 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/368 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.02GB | 357/368 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.68GB | 344/368 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
