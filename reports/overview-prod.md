# Overview: prod
*Last updated: 2026-05-18 09:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T09:33 (127 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,953 | avg: 15,193 | max: 84,644 | trend: decreasing (-36.19/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂
```

**Heap InUse** (current: 223.1MB | avg: 206.2MB | max: 1896.6MB | trend: decreasing (-2.38MB/hr))
```
▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁▁▄▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,953 | 16,314 | +639 | 15,193 | 84,644 | decreasing (-36.19/hr) |
| Heap InUse | 223.1MB | 233.0MB | -9.9MB | 206.2MB | 1896.6MB | decreasing (-2.38MB/hr) |
| Heap Sys | 4690.0MB | 4699.7MB | -9.7MB | 4195.0MB | 5842.7MB | |
| Heap Objects | 817,701 | 1,095,582 | -277881 | 919,707 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 20 | 14,637 | 167.4MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.11MB |
| 3 | `internal/evaluation.mergeMetadata` | 18.5MB |
| 4 | `runtime.mallocgc` | 9.6MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `experiment/local.(*Client).EvaluateV2` | 8.92MB |
| 7 | `bufio.NewWriterSize` | 7.53MB |
| 8 | `internal/evaluation.(*Engine).Evaluate` | 6.88MB |
| 9 | `bufio.NewReaderSize` | 6.52MB |
| 10 | `experiment/local.topologicalSort` | 6.07MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 155.6GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 109.52GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 94.31GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 93.73GB |
| 5 | `experiment/local.topologicalSort` | 62.19GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 50.06GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 48.45GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 29.8GB |
| 9 | `segmentio/kafka-go.makePartitions` | 24.21GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.89GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/127 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 125/127 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/127 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.19MB | 125/127 | `████████░░░░░░░ 54%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/127 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/127 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/127 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.41MB | 59/127 | `█████░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 10.88MB | 8/127 | `████░░░░░░░░░░░ 29%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB | 30/127 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 55.36GB | 120/127 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 39.18GB | 116/127 | `██████████░░░░░ 70%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/127 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 23.31GB | 122/127 | `██████░░░░░░░░░ 42%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 23.27GB | 118/127 | `██████░░░░░░░░░ 42%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 23.26GB | 122/127 | `██████░░░░░░░░░ 42%` |
| 7 | `reflect.growslice` | 20.37GB | 36/127 | `█████░░░░░░░░░░ 36%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/127 | `████░░░░░░░░░░░ 31%` |
| 9 | `experiment/local.topologicalSort` | 16.31GB | 104/127 | `████░░░░░░░░░░░ 29%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 16.24GB | 72/127 | `████░░░░░░░░░░░ 29%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
