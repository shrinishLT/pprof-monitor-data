# Overview: prod
*Last updated: 2026-05-18 08:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-18T08:02 (124 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,290 | avg: 15,178 | max: 84,644 | trend: decreasing (-40.41/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 130.8MB | avg: 206.4MB | max: 1896.6MB | trend: decreasing (-2.54MB/hr))
```
▄▃▄▆▃▃▅▅▃▃▄▄▁▂▁▂▁▂▄▁▂▃▂▁▁▁▁▂▂▂▁▂▂▂▂▂▁▁▁▂▂▃▂▃▃▂▁▂▂▁▂▇▆▄▆▃▃▁▂▃▄▁▂▁▁▂▁▂▁▂▁▂▂▁▁▁▂▂▂▁▁▁▁▂▂▁▁▁▁▁▅█▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,290 | 14,702 | -412 | 15,178 | 84,644 | decreasing (-40.41/hr) |
| Heap InUse | 130.8MB | 129.2MB | +1.6MB | 206.4MB | 1896.6MB | decreasing (-2.54MB/hr) |
| Heap Sys | 4699.4MB | 4699.5MB | -0.1MB | 4182.9MB | 5842.7MB | |
| Heap Objects | 531,910 | 308,835 | +223075 | 921,573 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 17 | 14,429 | 162.2MB | 404.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `bufio.NewReaderSize` | 2.01MB |
| 8 | `compress/flate.NewWriter` | 1.76MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 10 | `encoding/json.typeFields` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 122.9GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 106.67GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.46GB |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 74.18GB |
| 5 | `experiment/local.topologicalSort` | 49.06GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 48.73GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 37.95GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 23.54GB |
| 9 | `segmentio/kafka-go.makePartitions` | 22.12GB |
| 10 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.16GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 36.75MB | 7/124 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 122/124 | `██████████████░ 99%` |
| 3 | `net/http.(*Transport).dialConn` | 30.0MB | 1/124 | `████████████░░░ 81%` |
| 4 | `runtime.mallocgc` | 20.46MB | 122/124 | `████████░░░░░░░ 55%` |
| 5 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB | 2/124 | `███████░░░░░░░░ 50%` |
| 6 | `database/sql.convertAssignRows` | 17.44MB | 8/124 | `███████░░░░░░░░ 47%` |
| 7 | `crypto/tls.Client` | 13.01MB | 3/124 | `█████░░░░░░░░░░ 35%` |
| 8 | `bytes.growSlice` | 12.23MB | 57/124 | `████░░░░░░░░░░░ 33%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 12.01MB | 7/124 | `████░░░░░░░░░░░ 32%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB | 29/124 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.0GB | 117/124 | `███████████████ 100%` |
| 2 | `internal/evaluation.mergeMetadata` | 36.6GB | 113/124 | `██████████░░░░░ 67%` |
| 3 | `fmt.(*buffer).writeString` | 24.13GB | 16/124 | `██████░░░░░░░░░ 44%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.58GB | 115/124 | `██████░░░░░░░░░ 41%` |
| 5 | `internal/evaluation.(*Engine).Evaluate` | 21.82GB | 119/124 | `██████░░░░░░░░░ 40%` |
| 6 | `experiment/local.(*Client).EvaluateV2` | 21.76GB | 119/124 | `██████░░░░░░░░░ 40%` |
| 7 | `reflect.growslice` | 20.37GB | 36/124 | `█████░░░░░░░░░░ 37%` |
| 8 | `jackskj/carta.getUniqueId` | 17.48GB | 25/124 | `████░░░░░░░░░░░ 32%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.01GB | 5/124 | `████░░░░░░░░░░░ 29%` |
| 10 | `experiment/local.topologicalSort` | 15.18GB | 101/124 | `████░░░░░░░░░░░ 28%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.6x avg)
