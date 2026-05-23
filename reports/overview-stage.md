# Overview: stage
*Last updated: 2026-05-23 14:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T14:30 (408 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,161 | avg: 14,290 | max: 28,205 | trend: stable (-0.24/hr))
```
▁▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 368.1MB | avg: 172.7MB | max: 732.9MB | trend: stable (+0.21MB/hr))
```
▁▁▂▁▂▁▂▂▁▂▃▂▂▂▂▃▂▃▃▁▃▂▃▃▂▃▁▂▁▃▃▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▃▁▂▂▂▂▃▂▁▁▅▃▂▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▂▂▂▁█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 20%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,161 | 14,185 | -24 | 14,290 | 28,205 | stable (-0.24/hr) |
| Heap InUse | 368.1MB | 140.9MB | +227.2MB | 172.7MB | 732.9MB | stable (+0.21MB/hr) |
| Heap Sys | 1751.4MB | 1752.4MB | -1.0MB | 1362.9MB | 1793.6MB | |
| Heap Objects | 2,697,132 | 307,938 | +2389194 | 889,211 | 2,697,132 | |

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
| 2026-05-23 | 30 | 14,145 | 181.7MB | 368.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 46.36MB |
| 2 | `database/sql.convertAssignRows` | 46.0MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 41.41MB |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 5 | `runtime.mallocgc` | 14.67MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 7.58MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 84.02GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 44.15GB |
| 3 | `reflect.unsafe_NewArray` | 36.44GB |
| 4 | `reflect.MakeSlice` | 20.24GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.58GB |
| 6 | `segmentio/kafka-go.makeLayout` | 9.04GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.35GB |
| 8 | `database/sql.convertAssignRows` | 5.72GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.4GB |
| 10 | `internal/reflectlite.unsafe_New` | 4.06GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 406/408 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.38MB | 11/408 | `███████░░░░░░░░ 52%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.85MB | 8/408 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 402/408 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/408 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.68MB | 11/408 | `█████░░░░░░░░░░ 34%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.08MB | 18/408 | `████░░░░░░░░░░░ 30%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/408 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/408 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/408 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 95.96GB | 399/408 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/408 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/408 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/408 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.48GB | 399/408 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.06GB | 384/408 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/408 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/408 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.22GB | 397/408 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.47GB | 384/408 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
