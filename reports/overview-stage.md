# Overview: stage
*Last updated: 2026-05-24 05:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T05:30 (438 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,065 | avg: 14,278 | max: 28,205 | trend: stable (-0.50/hr))
```
▃▃▁▁▁▁▁▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 201.9MB | avg: 173.3MB | max: 732.9MB | trend: stable (+0.19MB/hr))
```
▃▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▂▁▂▂▂▂▃▂▁▁▅▃▁▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▁▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▁▃▃▁▃▁▁▃▂▂▂▁▂▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,065 | 14,065 | +0 | 14,278 | 28,205 | stable (-0.50/hr) |
| Heap InUse | 201.9MB | 200.8MB | +1.1MB | 173.3MB | 732.9MB | stable (+0.19MB/hr) |
| Heap Sys | 1751.4MB | 1751.4MB | +0.0MB | 1389.6MB | 1793.6MB | |
| Heap Objects | 1,264,229 | 1,253,869 | +10360 | 893,686 | 2,697,132 | |

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
| 2026-05-24 | 12 | 14,123 | 182.2MB | 216.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `reflect.unsafe_NewArray` | 3.0MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `segmentio/kafka-go.makeLayout` | 1.54MB |
| 10 | `bufio.NewReaderSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 110.99GB |
| 2 | `reflect.unsafe_NewArray` | 48.22GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 45.61GB |
| 4 | `reflect.MakeSlice` | 26.69GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.16GB |
| 6 | `segmentio/kafka-go.makeLayout` | 11.88GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.56GB |
| 8 | `database/sql.convertAssignRows` | 5.93GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.81GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 436/438 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.38MB | 11/438 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.85MB | 8/438 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 432/438 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/438 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.68MB | 11/438 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.6MB | 19/438 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/438 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/438 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/438 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.1GB | 429/438 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/438 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/438 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/438 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.56GB | 429/438 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.46GB | 414/438 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/438 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/438 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.24GB | 427/438 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.66GB | 414/438 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
