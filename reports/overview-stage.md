# Overview: stage
*Last updated: 2026-05-24 06:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T06:00 (439 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,672 | avg: 14,279 | max: 28,205 | trend: stable (-0.47/hr))
```
▃▁▁▁▁▁▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▂▁▁▁▁▁▅
```

**Heap InUse** (current: 231.2MB | avg: 173.5MB | max: 732.9MB | trend: stable (+0.19MB/hr))
```
▃▂▁▁▁▂▁▃▁▁▃▂▁▂▃▂▁▂▂▂▂▃▂▁▁▅▃▁▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▁▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▁▃▃▁▃▁▁▃▂▂▂▁▂▂▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,672 | 14,065 | +607 | 14,279 | 28,205 | stable (-0.47/hr) |
| Heap InUse | 231.2MB | 201.9MB | +29.3MB | 173.5MB | 732.9MB | stable (+0.19MB/hr) |
| Heap Sys | 1751.3MB | 1751.4MB | -0.1MB | 1390.4MB | 1793.6MB | |
| Heap Objects | 911,177 | 1,264,229 | -353052 | 893,726 | 2,697,132 | |

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
| 2026-05-24 | 13 | 14,165 | 186.0MB | 231.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 16.2MB |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 15.02MB |
| 4 | `runtime.mallocgc` | 14.67MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `database/sql.convertAssignRows` | 8.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 5.51MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 9 | `bytes.growSlice` | 3.02MB |
| 10 | `bufio.NewReaderSize` | 2.54MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 111.92GB |
| 2 | `reflect.unsafe_NewArray` | 48.62GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 48.47GB |
| 4 | `reflect.MakeSlice` | 26.91GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 21.42GB |
| 6 | `segmentio/kafka-go.makeLayout` | 11.98GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.94GB |
| 8 | `database/sql.convertAssignRows` | 6.29GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 5.86GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.42GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 437/439 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.02MB | 12/439 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.67MB | 9/439 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.57MB | 433/439 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/439 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.29MB | 12/439 | `█████░░░░░░░░░░ 33%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.6MB | 19/439 | `████░░░░░░░░░░░ 28%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/439 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/439 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/439 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.14GB | 430/439 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/439 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/439 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/439 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.57GB | 430/439 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.48GB | 415/439 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/439 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/439 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.25GB | 428/439 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.67GB | 415/439 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
