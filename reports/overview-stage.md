# Overview: stage
*Last updated: 2026-05-23 13:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-23T13:00 (405 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,088 | avg: 14,291 | max: 28,205 | trend: stable (-0.22/hr))
```
▂▁▁▁▁▂▁▁▁▂▃▁▂▁▂▁▁▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▃▃▁▁▁▁▂▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 174.0MB | avg: 172.3MB | max: 732.9MB | trend: stable (+0.20MB/hr))
```
▄▄▃▁▂▄▂▄▁▃▃▁▃▄▂▃▃▃▅▃▅▄▁▄▃▅▅▃▄▁▄▁▄▅▄▃▁▁▁▃▂▄▁▁▅▃▂▃▄▄▂▃▃▄▄▄▃▁▂█▅▂▂▄▁▃▃▂▅▃▂▄▃▃▅▁▂▁▁▂▄▄▃▃▄▁▁▂▄▅▂▃▂▁▂▃
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,088 | 14,151 | -63 | 14,291 | 28,205 | stable (-0.22/hr) |
| Heap InUse | 174.0MB | 168.4MB | +5.6MB | 172.3MB | 732.9MB | stable (+0.20MB/hr) |
| Heap Sys | 1751.1MB | 1751.2MB | -0.1MB | 1360.1MB | 1793.6MB | |
| Heap Objects | 906,595 | 798,752 | +107843 | 886,131 | 2,432,873 | |

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
| 2026-05-23 | 27 | 14,144 | 176.4MB | 223.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.04MB |
| 9 | `kafka-go/protocol.newPage` | 1.06MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.06MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 81.26GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.38GB |
| 3 | `reflect.unsafe_NewArray` | 35.25GB |
| 4 | `reflect.MakeSlice` | 19.6GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.19GB |
| 6 | `segmentio/kafka-go.makeLayout` | 8.75GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 6.21GB |
| 8 | `database/sql.convertAssignRows` | 5.58GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 4.27GB |
| 10 | `internal/reflectlite.unsafe_New` | 3.93GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 403/405 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 16.68MB | 10/405 | `██████░░░░░░░░░ 45%` |
| 3 | `runtime.mallocgc` | 14.57MB | 399/405 | `█████░░░░░░░░░░ 39%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 14.49MB | 7/405 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/405 | `█████░░░░░░░░░░ 38%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.58MB | 17/405 | `████░░░░░░░░░░░ 31%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/405 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/405 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/405 | `███░░░░░░░░░░░░ 25%` |
| 10 | `database/sql.convertAssignRows` | 9.35MB | 10/405 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.06GB | 396/405 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/405 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/405 | `███████████░░░░ 74%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/405 | `███████████░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.53GB | 396/405 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.03GB | 381/405 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/405 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/405 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.24GB | 394/405 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.45GB | 381/405 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
