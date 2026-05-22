# Overview: stage
*Last updated: 2026-05-22 14:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T14:00 (359 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,071 | avg: 14,307 | max: 28,205 | trend: stable (+0.31/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 200.6MB | avg: 171.3MB | max: 732.9MB | trend: stable (+0.26MB/hr))
```
▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂▂▁▁▁▁▂▁▂▁▁▂▁▁▁▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,071 | 14,536 | -465 | 14,307 | 28,205 | stable (+0.31/hr) |
| Heap InUse | 200.6MB | 208.1MB | -7.5MB | 171.3MB | 732.9MB | stable (+0.26MB/hr) |
| Heap Sys | 1583.4MB | 1582.2MB | +1.2MB | 1324.1MB | 1793.6MB | |
| Heap Objects | 1,225,280 | 1,116,594 | +108686 | 884,667 | 2,432,873 | |

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
| 2026-05-22 | 31 | 14,148 | 186.2MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `bufio.NewWriterSize` | 1.52MB |
| 10 | `reflect.mapassign_faststr0` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 39.69GB |
| 2 | `reflect.unsafe_NewArray` | 17.25GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 16.38GB |
| 4 | `reflect.MakeSlice` | 9.64GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 7.18GB |
| 6 | `segmentio/kafka-go.makeLayout` | 4.26GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.33GB |
| 8 | `fmt.Sprintf` | 2.3GB |
| 9 | `database/sql.convertAssignRows` | 2.18GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 2.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 357/359 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/359 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.55MB | 353/359 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/359 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/359 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/359 | `████░░░░░░░░░░░ 33%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/359 | `████░░░░░░░░░░░ 27%` |
| 8 | `bytes.growSlice` | 9.93MB | 59/359 | `████░░░░░░░░░░░ 27%` |
| 9 | `database/sql.convertAssignRows` | 9.88MB | 8/359 | `████░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/359 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 100.68GB | 350/359 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/359 | `██████████░░░░░ 71%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/359 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/359 | `██████████░░░░░ 70%` |
| 5 | `reflect.unsafe_NewArray` | 43.51GB | 350/359 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.22GB | 335/359 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/359 | `█████░░░░░░░░░░ 36%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/359 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.37GB | 348/359 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.95GB | 335/359 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
