# Overview: stage
*Last updated: 2026-05-23 15:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T15:32 (410 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,068 | avg: 14,289 | max: 28,205 | trend: stable (-0.26/hr))
```
▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 205.2MB | avg: 172.9MB | max: 732.9MB | trend: stable (+0.21MB/hr))
```
▂▁▂▁▂▂▁▂▃▂▂▂▂▃▂▃▃▁▃▂▃▃▂▃▁▂▁▃▃▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▃▁▂▂▂▂▃▂▁▁▅▃▂▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,068 | 14,124 | -56 | 14,289 | 28,205 | stable (-0.26/hr) |
| Heap InUse | 205.2MB | 194.2MB | +11.0MB | 172.9MB | 732.9MB | stable (+0.21MB/hr) |
| Heap Sys | 1751.5MB | 1751.5MB | +0.0MB | 1364.8MB | 1793.6MB | |
| Heap Objects | 1,326,453 | 1,059,858 | +266595 | 890,694 | 2,697,132 | |

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
| 2026-05-23 | 32 | 14,142 | 182.9MB | 368.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `reflect.unsafe_NewArray` | 2.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `bufio.NewReaderSize` | 1.53MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 85.83GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 45.32GB |
| 3 | `reflect.unsafe_NewArray` | 37.22GB |
| 4 | `reflect.MakeSlice` | 20.68GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.03GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.24GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.48GB |
| 8 | `database/sql.convertAssignRows` | 5.84GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.5GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.15GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 408/410 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.38MB | 11/410 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.85MB | 8/410 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 404/410 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/410 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.68MB | 11/410 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.08MB | 18/410 | `████░░░░░░░░░░░ 30%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/410 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/410 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/410 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.91GB | 401/410 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/410 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/410 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/410 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.46GB | 401/410 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.09GB | 386/410 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/410 | `█████░░░░░░░░░░ 38%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/410 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.2GB | 399/410 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.48GB | 386/410 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
