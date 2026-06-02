# Overview: stage
*Last updated: 2026-06-02 15:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-02T15:32 (887 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,853 | avg: 14,232 | max: 28,205 | trend: stable (-0.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▇▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▃
```

**Heap InUse** (current: 206.0MB | avg: 167.6MB | max: 732.9MB | trend: stable (-0.03MB/hr))
```
▁▁▃▃▂▁▁▃▁▃▁▁▂▁▁▂▁▂▁▁▁▂▂▁▂▁▂▃▄▄▁▃▂▂▂▂▃▁▁▂▁▂▃▁▁▁▁▂▁▂▁█▃▅▂▂▃▁▁▂▂▃▃▁▂▂▂▂▁▁▂▂▁▁▂▁▃▃▂▂▂▂▁▂▂▁▁▁▁▁▂▂▃▂▁▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,853 | 14,127 | +726 | 14,232 | 28,205 | stable (-0.38/hr) |
| Heap InUse | 206.0MB | 116.2MB | +89.8MB | 167.6MB | 732.9MB | stable (-0.03MB/hr) |
| Heap Sys | 1549.8MB | 1551.2MB | -1.4MB | 1291.6MB | 1805.8MB | |
| Heap Objects | 1,170,212 | 340,237 | +829975 | 886,442 | 2,707,946 | |

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
| 2026-05-24 | 48 | 14,127 | 179.7MB | 263.6MB |
| 2026-05-25 | 48 | 14,341 | 196.2MB | 338.8MB |
| 2026-05-26 | 46 | 14,155 | 171.1MB | 299.9MB |
| 2026-05-27 | 47 | 14,177 | 151.2MB | 232.3MB |
| 2026-05-28 | 48 | 14,161 | 148.6MB | 218.1MB |
| 2026-05-29 | 48 | 14,166 | 148.6MB | 258.2MB |
| 2026-05-30 | 48 | 14,205 | 164.1MB | 277.7MB |
| 2026-05-31 | 48 | 14,126 | 149.1MB | 213.6MB |
| 2026-06-01 | 48 | 14,226 | 160.1MB | 355.0MB |
| 2026-06-02 | 32 | 14,166 | 153.6MB | 206.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `compress/flate.NewWriter` | 5.29MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 7 | `bytes.growSlice` | 3.52MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 9 | `reflect.unsafe_NewArray` | 3.0MB |
| 10 | `bufio.NewReaderSize` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 167.95GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 108.08GB |
| 3 | `reflect.unsafe_NewArray` | 72.37GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 50.24GB |
| 5 | `reflect.MakeSlice` | 40.64GB |
| 6 | `segmentio/kafka-go.makeLayout` | 18.06GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 16.28GB |
| 8 | `database/sql.convertAssignRows` | 14.69GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 8.53GB |
| 10 | `internal/reflectlite.unsafe_New` | 8.11GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 885/887 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.23MB | 35/887 | `███████░░░░░░░░ 49%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.95MB | 23/887 | `███████░░░░░░░░ 49%` |
| 4 | `runtime.mallocgc` | 13.67MB | 881/887 | `█████░░░░░░░░░░ 37%` |
| 5 | `database/sql.convertAssignRows` | 12.31MB | 37/887 | `█████░░░░░░░░░░ 33%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/887 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/887 | `███░░░░░░░░░░░░ 25%` |
| 8 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/887 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 883/887 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/887 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 92.07GB | 878/887 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/887 | `███████████░░░░ 77%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/887 | `███████████░░░░ 77%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/887 | `███████████░░░░ 76%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 47.16GB | 840/887 | `███████░░░░░░░░ 51%` |
| 6 | `reflect.unsafe_NewArray` | 39.82GB | 878/887 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/887 | `█████░░░░░░░░░░ 39%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/887 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.MakeSlice` | 22.27GB | 876/887 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.15GB | 838/887 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
