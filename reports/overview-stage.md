# Overview: stage
*Last updated: 2026-05-22 12:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T12:00 (355 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,308 | max: 28,205 | trend: stable (+0.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 186.6MB | avg: 171.1MB | max: 732.9MB | trend: stable (+0.26MB/hr))
```
▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂▂▁▁▁▁▂▁▂▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,258 | -193 | 14,308 | 28,205 | stable (+0.34/hr) |
| Heap InUse | 186.6MB | 226.6MB | -40.0MB | 171.1MB | 732.9MB | stable (+0.26MB/hr) |
| Heap Sys | 1582.5MB | 1581.7MB | +0.8MB | 1321.2MB | 1793.6MB | |
| Heap Objects | 1,090,326 | 1,408,034 | -317708 | 883,851 | 2,432,873 | |

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
| 2026-05-22 | 27 | 14,131 | 186.1MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.6MB |
| 9 | `bufio.NewReaderSize` | 1.55MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 36.03GB |
| 2 | `reflect.unsafe_NewArray` | 15.68GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 15.19GB |
| 4 | `reflect.MakeSlice` | 8.78GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.66GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.87GB |
| 7 | `fmt.Sprintf` | 2.21GB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.18GB |
| 9 | `database/sql.convertAssignRows` | 2.02GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 1.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 353/355 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/355 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.55MB | 349/355 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/355 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/355 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/355 | `████░░░░░░░░░░░ 33%` |
| 7 | `bytes.growSlice` | 10.36MB | 56/355 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/355 | `████░░░░░░░░░░░ 27%` |
| 9 | `database/sql.convertAssignRows` | 9.88MB | 8/355 | `████░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/355 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 101.4GB | 346/355 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/355 | `██████████░░░░░ 70%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/355 | `██████████░░░░░ 70%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/355 | `██████████░░░░░ 69%` |
| 5 | `reflect.unsafe_NewArray` | 43.82GB | 346/355 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.53GB | 331/355 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/355 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/355 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.54GB | 344/355 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.08GB | 331/355 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
