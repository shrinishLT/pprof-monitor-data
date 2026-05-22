# Overview: stage
*Last updated: 2026-05-22 23:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T23:32 (378 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,302 | max: 28,205 | trend: stable (+0.09/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 219.0MB | avg: 172.0MB | max: 732.9MB | trend: stable (+0.24MB/hr))
```
▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▁▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▁▁▁▃▂▁▁▂▁▂▁▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,071 | -3 | 14,302 | 28,205 | stable (+0.09/hr) |
| Heap InUse | 219.0MB | 159.6MB | +59.4MB | 172.0MB | 732.9MB | stable (+0.24MB/hr) |
| Heap Sys | 1589.1MB | 1589.1MB | +0.0MB | 1337.3MB | 1793.6MB | |
| Heap Objects | 1,512,468 | 759,527 | +752941 | 887,013 | 2,432,873 | |

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

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 1.51MB |
| 8 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 9 | `bufio.NewReaderSize` | 1.03MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 56.94GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.96GB |
| 3 | `reflect.unsafe_NewArray` | 24.7GB |
| 4 | `reflect.MakeSlice` | 13.72GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.17GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.13GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.28GB |
| 8 | `database/sql.convertAssignRows` | 3.89GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.07GB |
| 10 | `fmt.Sprintf` | 2.86GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 376/378 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/378 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.56MB | 372/378 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/378 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/378 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/378 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/378 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.88MB | 8/378 | `████░░░░░░░░░░░ 26%` |
| 9 | `bytes.growSlice` | 9.56MB | 63/378 | `███░░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/378 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 98.0GB | 369/378 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/378 | `██████████░░░░░ 72%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/378 | `██████████░░░░░ 72%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/378 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 42.35GB | 369/378 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.28GB | 354/378 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/378 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/378 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.72GB | 367/378 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.55GB | 354/378 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
