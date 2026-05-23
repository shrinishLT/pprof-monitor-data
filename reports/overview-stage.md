# Overview: stage
*Last updated: 2026-05-23 06:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T06:30 (392 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,463 | avg: 14,297 | max: 28,205 | trend: stable (-0.05/hr))
```
▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 192.5MB | avg: 172.3MB | max: 732.9MB | trend: stable (+0.22MB/hr))
```
▁▁▁█▁▁▂▂▂▁▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▁▂▁▂▂▁▂▁▂▂▁▂▁▂▁▂▂▂▁▁▁▁▁▁▂▁▁▂▁▁▁▂▂▁▁▁▂▂▂▁▁▁▃▂▁▁▂▁▂▁▁▂▁▁▂▁▁▂▁▁▁▁▁▂▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,463 | 14,660 | -197 | 14,297 | 28,205 | stable (-0.05/hr) |
| Heap InUse | 192.5MB | 210.6MB | -18.1MB | 172.3MB | 732.9MB | stable (+0.22MB/hr) |
| Heap Sys | 1750.8MB | 1750.2MB | +0.6MB | 1347.1MB | 1793.6MB | |
| Heap Objects | 707,506 | 847,655 | -140149 | 885,703 | 2,432,873 | |

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
| 2026-05-23 | 14 | 14,178 | 178.2MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 15.0MB |
| 4 | `runtime.mallocgc` | 14.67MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `database/sql.convertAssignRows` | 5.5MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 8 | `bytes.growSlice` | 3.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 10 | `bufio.NewReaderSize` | 3.05MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 69.53GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 42.65GB |
| 3 | `reflect.unsafe_NewArray` | 30.2GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 18.86GB |
| 5 | `reflect.MakeSlice` | 16.78GB |
| 6 | `segmentio/kafka-go.makeLayout` | 7.49GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.09GB |
| 8 | `database/sql.convertAssignRows` | 5.48GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 3.71GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.37GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 390/392 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.68MB | 10/392 | `██████░░░░░░░░░ 45%` |
| 3 | `runtime.mallocgc` | 14.56MB | 386/392 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.49MB | 7/392 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/392 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/392 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/392 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/392 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/392 | `███░░░░░░░░░░░░ 25%` |
| 10 | `database/sql.convertAssignRows` | 9.35MB | 10/392 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.75GB | 383/392 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/392 | `███████████░░░░ 73%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/392 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/392 | `██████████░░░░░ 72%` |
| 5 | `reflect.unsafe_NewArray` | 41.82GB | 383/392 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 39.93GB | 368/392 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/392 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/392 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.41GB | 381/392 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.4GB | 368/392 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
