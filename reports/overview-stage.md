# Overview: stage
*Last updated: 2026-05-23 06:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T06:00 (391 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,660 | avg: 14,297 | max: 28,205 | trend: stable (-0.06/hr))
```
▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 210.6MB | avg: 172.2MB | max: 732.9MB | trend: stable (+0.22MB/hr))
```
▁▁▁▁█▁▁▂▂▂▁▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▁▁▁▃▂▁▁▂▁▂▁▁▂▁▁▂▁▁▂▁▁▁▁▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,660 | 14,074 | +586 | 14,297 | 28,205 | stable (-0.06/hr) |
| Heap InUse | 210.6MB | 205.0MB | +5.6MB | 172.2MB | 732.9MB | stable (+0.22MB/hr) |
| Heap Sys | 1750.2MB | 1590.4MB | +159.8MB | 1346.1MB | 1793.6MB | |
| Heap Objects | 847,655 | 1,291,115 | -443460 | 886,159 | 2,432,873 | |

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
| 2026-05-23 | 13 | 14,157 | 177.1MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 14.95MB |
| 3 | `runtime.mallocgc` | 14.67MB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 12.89MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `database/sql.convertAssignRows` | 9.0MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bufio.NewReaderSize` | 4.06MB |
| 9 | `bytes.growSlice` | 4.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 68.68GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 33.04GB |
| 3 | `reflect.unsafe_NewArray` | 29.84GB |
| 4 | `reflect.MakeSlice` | 16.57GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 14.56GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.39GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.74GB |
| 8 | `database/sql.convertAssignRows` | 4.28GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.65GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.32GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 389/391 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.87MB | 9/391 | `██████░░░░░░░░░ 46%` |
| 3 | `runtime.mallocgc` | 14.56MB | 385/391 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.2MB | 6/391 | `█████░░░░░░░░░░ 38%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/391 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/391 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/391 | `████░░░░░░░░░░░ 27%` |
| 8 | `database/sql.convertAssignRows` | 9.78MB | 9/391 | `████░░░░░░░░░░░ 26%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/391 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/391 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.82GB | 382/391 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/391 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/391 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/391 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 41.85GB | 382/391 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.93GB | 367/391 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/391 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/391 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.43GB | 380/391 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.4GB | 367/391 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
