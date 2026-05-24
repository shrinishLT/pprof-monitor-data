# Overview: stage
*Last updated: 2026-05-24 08:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T08:32 (444 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,064 | avg: 14,278 | max: 28,205 | trend: stable (-0.49/hr))
```
▁▁▁▁▁▂▁▂▁▄▁▂▁▂▁▁▁▁▁▃█▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▄▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▁▁▂▁▁▁▁▁▂▁▁▁▁▁▅▂▁▁▁▁
```

**Heap InUse** (current: 152.0MB | avg: 173.4MB | max: 732.9MB | trend: stable (+0.18MB/hr))
```
▂▁▃▁▁▃▂▁▂▃▂▁▂▂▂▂▃▂▁▁▅▃▁▁▃▁▂▂▁▃▂▁▃▂▂▃▁▁▁▁▁▃▃▂▂▃▁▁▁▂▃▂▂▁▁▁▂▂▁█▂▃▁▃▂▁▂▃▂▁▂▁▁▁▁▁▁▃▃▁▃▁▁▃▂▂▂▁▂▂▃▂▁▃▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,064 | 14,113 | -49 | 14,278 | 28,205 | stable (-0.49/hr) |
| Heap InUse | 152.0MB | 143.5MB | +8.5MB | 173.4MB | 732.9MB | stable (+0.18MB/hr) |
| Heap Sys | 1751.4MB | 1751.4MB | +0.0MB | 1394.4MB | 1793.6MB | |
| Heap Objects | 637,438 | 440,673 | +196765 | 891,938 | 2,697,132 | |

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
| 2026-05-24 | 18 | 14,161 | 180.8MB | 231.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.mapassign_faststr0` | 2.0MB |
| 8 | `reflect.unsafe_NewArray` | 2.0MB |
| 9 | `segmentio/kafka-go.makePartitions` | 1.5MB |
| 10 | `bufio.NewReaderSize` | 1.03MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 116.49GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.2GB |
| 3 | `reflect.unsafe_NewArray` | 50.61GB |
| 4 | `reflect.MakeSlice` | 28.06GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 25.72GB |
| 6 | `segmentio/kafka-go.makeLayout` | 12.5GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.38GB |
| 8 | `database/sql.convertAssignRows` | 7.49GB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 6.11GB |
| 10 | `internal/reflectlite.unsafe_New` | 5.66GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 442/444 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.02MB | 12/444 | `███████░░░░░░░░ 51%` |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 17.67MB | 9/444 | `███████░░░░░░░░ 48%` |
| 4 | `runtime.mallocgc` | 14.58MB | 438/444 | `█████░░░░░░░░░░ 39%` |
| 5 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/444 | `█████░░░░░░░░░░ 38%` |
| 6 | `database/sql.convertAssignRows` | 12.29MB | 12/444 | `█████░░░░░░░░░░ 33%` |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.22MB | 20/444 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*Transport).dialConn` | 10.0MB | 2/444 | `████░░░░░░░░░░░ 27%` |
| 9 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/444 | `███░░░░░░░░░░░░ 25%` |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/444 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 96.35GB | 435/444 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/444 | `███████████░░░░ 74%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/444 | `███████████░░░░ 73%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/444 | `██████████░░░░░ 73%` |
| 5 | `reflect.unsafe_NewArray` | 41.67GB | 435/444 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.69GB | 420/444 | `██████░░░░░░░░░ 42%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/444 | `█████░░░░░░░░░░ 37%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/444 | `█████░░░░░░░░░░ 37%` |
| 9 | `reflect.MakeSlice` | 23.3GB | 433/444 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 17.77GB | 420/444 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.2x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.2x avg)
