# Overview: stage
*Last updated: 2026-05-22 16:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T16:30 (364 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,118 | avg: 14,305 | max: 28,205 | trend: stable (+0.23/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 194.7MB | avg: 171.5MB | max: 732.9MB | trend: stable (+0.25MB/hr))
```
▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,118 | 14,066 | +52 | 14,305 | 28,205 | stable (+0.23/hr) |
| Heap InUse | 194.7MB | 195.6MB | -0.9MB | 171.5MB | 732.9MB | stable (+0.25MB/hr) |
| Heap Sys | 1584.3MB | 1584.4MB | -0.1MB | 1327.7MB | 1793.6MB | |
| Heap Objects | 1,078,569 | 1,219,100 | -140531 | 885,754 | 2,432,873 | |

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
| 2026-05-22 | 36 | 14,151 | 186.1MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.unsafe_NewArray` | 2.01MB |
| 9 | `bufio.NewReaderSize` | 1.55MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 44.15GB |
| 2 | `reflect.unsafe_NewArray` | 19.18GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.73GB |
| 4 | `reflect.MakeSlice` | 10.69GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.79GB |
| 6 | `segmentio/kafka-go.makeLayout` | 4.76GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.52GB |
| 8 | `fmt.Sprintf` | 2.42GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 2.41GB |
| 10 | `database/sql.convertAssignRows` | 2.34GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 362/364 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/364 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.55MB | 358/364 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/364 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/364 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/364 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/364 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.88MB | 8/364 | `████░░░░░░░░░░░ 26%` |
| 9 | `bytes.growSlice` | 9.8MB | 60/364 | `████░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/364 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 99.85GB | 355/364 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/364 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/364 | `██████████░░░░░ 71%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/364 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.15GB | 355/364 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.86GB | 340/364 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/364 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/364 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 24.17GB | 353/364 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.8GB | 340/364 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
