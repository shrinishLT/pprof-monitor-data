# Overview: stage
*Last updated: 2026-05-23 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T02:00 (383 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,070 | avg: 14,299 | max: 28,205 | trend: stable (-0.00/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 189.5MB | avg: 172.2MB | max: 732.9MB | trend: stable (+0.24MB/hr))
```
▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▁▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▁▁▁▃▂▁▁▂▁▂▁▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,070 | 14,066 | +4 | 14,299 | 28,205 | stable (-0.00/hr) |
| Heap InUse | 189.5MB | 177.7MB | +11.8MB | 172.2MB | 732.9MB | stable (+0.24MB/hr) |
| Heap Sys | 1589.2MB | 1589.2MB | +0.0MB | 1340.6MB | 1793.6MB | |
| Heap Objects | 1,135,813 | 949,408 | +186405 | 888,837 | 2,432,873 | |

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
| 2026-05-23 | 5 | 14,072 | 182.9MB | 211.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `segmentio/kafka-go.makePartitions` | 2.0MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 1.04MB |
| 10 | `bufio.NewReaderSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 61.34GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 29.96GB |
| 3 | `reflect.unsafe_NewArray` | 26.66GB |
| 4 | `reflect.MakeSlice` | 14.82GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 13.17GB |
| 6 | `segmentio/kafka-go.makeLayout` | 6.6GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.28GB |
| 8 | `database/sql.convertAssignRows` | 3.89GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.29GB |
| 10 | `internal/reflectlite.unsafe_New` | 2.98GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 381/383 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.11MB | 8/383 | `███████░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.56MB | 377/383 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.46MB | 5/383 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/383 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/383 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/383 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.88MB | 8/383 | `████░░░░░░░░░░░ 26%` |
| 9 | `bytes.growSlice` | 9.56MB | 63/383 | `███░░░░░░░░░░░░ 26%` |
| 10 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/383 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 97.49GB | 374/383 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/383 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/383 | `██████████░░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/383 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 42.13GB | 374/383 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.14GB | 359/383 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/383 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/383 | `█████░░░░░░░░░░ 36%` |
| 9 | `reflect.MakeSlice` | 23.59GB | 372/383 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.49GB | 359/383 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
