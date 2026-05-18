# Overview: prod
*Last updated: 2026-05-18 09:03 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T09:03 (126 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,314 | avg: 15,179 | max: 84,644 | trend: decreasing (-38.40/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂
```

**Heap InUse** (current: 233.0MB | avg: 206.0MB | max: 1896.6MB | trend: decreasing (-2.45MB/hr))
```
▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,314 | 14,176 | +2138 | 15,179 | 84,644 | decreasing (-38.40/hr) |
| Heap InUse | 233.0MB | 134.1MB | +98.9MB | 206.0MB | 1896.6MB | decreasing (-2.45MB/hr) |
| Heap Sys | 4699.7MB | 4699.4MB | +0.3MB | 4191.1MB | 5842.7MB | |
| Heap Objects | 1,095,582 | 614,464 | +481118 | 920,516 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 19 | 14,515 | 164.4MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.08MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `runtime.mallocgc` | 8.58MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 7 | `bufio.NewReaderSize` | 3.51MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `bufio.NewWriterSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 129.46GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 109.52GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 78.47GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 78.06GB |
| 5 | `experiment/local.topologicalSort` | 51.63GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 50.06GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 40.02GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 24.79GB |
| 9 | `segmentio/kafka-go.makePartitions` | 23.57GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.68GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/126 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 124/126 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/126 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.27MB | 124/126 | `████████░░░░░░░ 55%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/126 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/126 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/126 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.29MB | 58/126 | `█████░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 10.88MB | 8/126 | `████░░░░░░░░░░░ 29%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB | 30/126 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.9GB | 119/126 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 38.17GB | 115/126 | `██████████░░░░░ 69%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/126 | `██████░░░░░░░░░ 43%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 23.04GB | 117/126 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 22.73GB | 121/126 | `██████░░░░░░░░░ 41%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 22.67GB | 121/126 | `██████░░░░░░░░░ 41%` |
| 7 | `reflect.growslice` | 20.37GB | 36/126 | `█████░░░░░░░░░░ 37%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/126 | `████░░░░░░░░░░░ 31%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/126 | `████░░░░░░░░░░░ 29%` |
| 10 | `experiment/local.topologicalSort` | 15.87GB | 103/126 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
