# Overview: stage
*Last updated: 2026-05-22 09:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T09:31 (350 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,069 | avg: 14,310 | max: 28,205 | trend: stable (+0.44/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 164.3MB | avg: 170.9MB | max: 732.9MB | trend: stable (+0.26MB/hr))
```
▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂▂▁▂▁▂▂▂▁▁▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,069 | 14,210 | -141 | 14,310 | 28,205 | stable (+0.44/hr) |
| Heap InUse | 164.3MB | 190.3MB | -26.0MB | 170.9MB | 732.9MB | stable (+0.26MB/hr) |
| Heap Sys | 1582.0MB | 1581.7MB | +0.3MB | 1317.4MB | 1793.6MB | |
| Heap Objects | 832,313 | 945,872 | -113559 | 882,026 | 2,432,873 | |

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
| 2026-05-22 | 22 | 14,130 | 186.5MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `bufio.NewWriterSize` | 1.52MB |
| 10 | `regexp.(*bitState).reset` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 31.55GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 15.19GB |
| 3 | `reflect.unsafe_NewArray` | 13.74GB |
| 4 | `reflect.MakeSlice` | 7.67GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.66GB |
| 6 | `segmentio/kafka-go.makeLayout` | 3.39GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.17GB |
| 8 | `fmt.Sprintf` | 2.16GB |
| 9 | `database/sql.convertAssignRows` | 2.01GB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 1.76GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 348/350 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/350 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.55MB | 344/350 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/350 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/350 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/350 | `████░░░░░░░░░░░ 33%` |
| 7 | `bytes.growSlice` | 10.36MB | 56/350 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/350 | `████░░░░░░░░░░░ 27%` |
| 9 | `database/sql.convertAssignRows` | 9.88MB | 8/350 | `████░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/350 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 102.38GB | 341/350 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/350 | `██████████░░░░░ 69%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/350 | `██████████░░░░░ 69%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/350 | `██████████░░░░░ 68%` |
| 5 | `reflect.unsafe_NewArray` | 44.24GB | 341/350 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.93GB | 326/350 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/350 | `█████░░░░░░░░░░ 35%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/350 | `█████░░░░░░░░░░ 35%` |
| 9 | `reflect.MakeSlice` | 24.78GB | 339/350 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.26GB | 326/350 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
